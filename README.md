# Typing Test & Keyboard Analyzer

## Overview

This is a single-page web application designed to help users test and improve their typing speed and accuracy. A key feature of this application is the ability to track and compare performance across different physical keyboards. All test results are stored within the URL parameters, making it incredibly easy to save, share, and bookmark performance data without needing a backend server or local storage.

The application is also instrumented with the Datadog RUM (Real User Monitoring) SDK to provide insights into application performance and user behavior.

## Core Features

Random Text Passages: Presents users with a variety of random text samples for typing practice, including different sentence structures and punctuation.

Real-time Feedback: Provides instant visual feedback by highlighting correct characters in green and incorrect ones in red.

Live Statistics: Calculates and displays Words Per Minute (WPM), accuracy percentage, and total error count in real-time as the user types.

Timer: A countdown timer starts automatically as soon as the user begins typing. Test durations can be set to 30, 60, or 120 seconds.

Keyboard Tracking: Users can specify the keyboard model they are using before starting a test. This information is saved with the results.

URL-Based Data Storage: All test results, including WPM, accuracy, keyboard model, and the text sample used, are encoded into the URL for easy sharing and record-keeping.

Responsive Design: The interface is clean, distraction-free, and works well on desktop browsers.

## How to Use

Open the index.html file in a modern web browser.

Enter Your Keyboard Model: On the setup screen, type the name of the keyboard you are using into the "Keyboard Model" input field (e.g., "Keychron Q1", "Logitech MX Keys").

Select Test Duration: Choose your desired test length from the dropdown menu (30, 60, or 120 seconds).

Start the Test: Click the "Start Typing Test" button.

Begin Typing: The test screen will appear with a text prompt. Start typing the text. The timer will begin as soon as you type the first character.

View Results: Once the timer runs out or you complete the passage, you will be taken to the results screen.

Share or Restart: From the results screen, you can copy the unique URL to share your score or click "New Test" to try again.

URL-Based Data Storage
A unique feature of this application is its stateless design. After each test, the results are encoded into the URL's query parameters.

A sample result URL looks like this:

https://example.com/index.html?wpm=75&acc=98&kb=Keychron+Q1&ts=2023-10-27T18:30:00.000Z&text=VGhlIHF1aWNrIGJyb3duIGZveCBqdW1wcyBvdmVyIHRoZSBsYXp5IGRvZy4=

wpm: Words Per Minute

acc: Accuracy percentage

kb: Keyboard model (URL encoded)

ts: Timestamp of test completion (ISO format)

text: The text prompt used for the test (Base64 encoded)

This allows users to simply bookmark the URL to save a result or share it with others. Visiting a result URL will directly display the results screen for that specific test.

Technical Specifications
Frontend: Built with plain HTML, CSS, and JavaScript.

Styling: Uses Tailwind CSS for a clean and modern UI.

Dependencies: No external JavaScript libraries are required besides Tailwind CSS and the Datadog RUM SDK, both loaded from a CDN.

Compatibility: Designed for modern desktop browsers.

Datadog RUM Integration
The application is integrated with Datadog's Real User Monitoring (RUM) to capture performance data and user actions. This includes:

Session Tracking & Replay: Monitors user sessions to identify issues and understand user flows.

Custom Actions: Tracks key user interactions, such as:

start_test: When a user begins a new test.

test_completed: When a test is finished, along with the final WPM, accuracy, and keyboard model.

restart_test: When a user restarts a test mid-session.

copy_share_url: When the user copies their result URL.

This data provides valuable insights into how the application is being used and how it is performing in the wild.