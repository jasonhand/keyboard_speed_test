# 🚀 Datadog Typing Test & Keyboard Analyzer

A modern, interactive typing speed test application featuring Datadog documentation snippets. Test your typing speed while learning about Datadog's monitoring and analytics platform!

![Datadog Typing Test](https://img.shields.io/badge/Datadog-Typing%20Test-purple?style=for-the-badge&logo=datadog)

## ✨ Features

### 🎯 Core Functionality
- **30-second typing speed tests** with real-time WPM, accuracy, and error tracking
- **120+ Datadog documentation snippets** covering monitoring, APM, logs, infrastructure, and more
- **Real-time visual feedback** with purple highlighting for correct text and error indicators
- **Countdown timer** with purple flashing background warning when under 10 seconds
- **Live statistics** including Words Per Minute (WPM), accuracy percentage, and error count

### 🏆 Leaderboard System
- **Local leaderboard** with top 10 scores stored in browser
- **Shareable leaderboard URLs** for easy distribution
- **Persistent storage** using localStorage
- **Ranking system** with medals (🥇🥈🥉) for top performers
- **Sorting by WPM and accuracy** for fair competition

### 🎨 Modern UI/UX
- **Beautiful Datadog branding** with official purple color scheme (#632CA6)
- **Bits AI hero background** with dark overlay for readability
- **Responsive design** that works on desktop and mobile devices
- **Smooth animations** and hover effects throughout
- **Datadog logo accents** in corners with subtle opacity effects

### 🤖 Bits AI Integration
- **AI-powered toast notifications** after test completion
- **Smart suggestions** for next actions (start over, share results)
- **Datadog-branded messaging** with official logo
- **Auto-dismiss functionality** with manual override options

### 📊 Results & Sharing
- **Detailed results screen** with comprehensive statistics
- **Shareable URLs** containing test results and metadata
- **Datadog documentation links** for each test snippet
- **Copy-to-clipboard functionality** for easy sharing
- **Direct link to Datadog platform** for users to try the real thing

### 🔧 Technical Features
- **Datadog RUM integration** for analytics and monitoring
- **URL parameter handling** for sharing results and leaderboards
- **Progressive Web App** ready with modern JavaScript
- **Cross-browser compatibility** with fallback support
- **Accessibility features** with proper focus management

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required - everything is included!

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start typing immediately!

### Usage
1. **Enter your name** in the setup screen
2. **Click "Start Typing Test"** to begin
3. **Type the displayed text** as quickly and accurately as possible
4. **View your results** and compare with the leaderboard
5. **Share your score** using the generated URL
6. **Try again** to improve your speed!

## 🎯 How It Works

### Typing Test Mechanics
- **30-second time limit** for each test
- **WPM calculation** based on correct characters typed (5 characters = 1 word)
- **Accuracy tracking** with real-time visual feedback
- **Error counting** for incorrect characters
- **Auto-completion** when all text is typed

### Leaderboard System
- **Local storage** maintains top 10 scores
- **Automatic sorting** by WPM (primary) and accuracy (secondary)
- **Timestamp tracking** for each entry
- **URL encoding** for sharing leaderboards across devices

### Datadog Integration
- **120+ documentation snippets** from official Datadog docs
- **Direct links** to source documentation
- **Comprehensive coverage** of Datadog features and products
- **Educational content** that teaches while you type

## 🎨 Customization

### Colors & Branding
The app uses Datadog's official purple color (#632CA6) throughout:
- Typing cursor and correct text highlighting
- Button backgrounds and focus rings
- Timer warning animations
- UI accents and highlights

### Content
- **Easy snippet addition**: Add new Datadog documentation snippets to the `datadogSnippets` array
- **Customizable test duration**: Modify the `testDuration` value in the state object
- **Branding elements**: Update logos and images to match your organization

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### Built With
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Tailwind CSS
- **Vanilla JavaScript** - No frameworks, pure performance
- **Tailwind CSS** - Utility-first CSS framework
- **Datadog RUM** - Real User Monitoring integration

### Key Technologies
- **localStorage API** - Persistent data storage
- **URLSearchParams** - URL parameter handling
- **CSS Animations** - Smooth transitions and effects
- **Web APIs** - Clipboard, History, and more

### Performance Features
- **Lightweight** - No heavy frameworks or dependencies
- **Fast loading** - Optimized images and minimal external resources
- **Responsive** - Works seamlessly across all device sizes
- **Accessible** - Proper focus management and keyboard navigation

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Ideas
- Add different test durations (15s, 60s, custom)
- Implement user accounts and global leaderboards
- Add typing practice modes with specific Datadog topics
- Create mobile-optimized touch typing interface
- Add sound effects and haptic feedback

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Datadog** for providing the amazing monitoring platform and documentation
- **Tailwind CSS** for the beautiful utility-first styling framework
- **Inter font** for the clean, modern typography
- **Bits AI** for the innovative AI integration concept

## 📞 Support

If you have any questions or need help with the typing test:

- **Issues**: Create an issue in this repository
- **Feature Requests**: Submit a feature request with detailed description
- **Bug Reports**: Include browser version and steps to reproduce

---

**Ready to test your typing speed?** 🚀 [Start typing now!](index.html)

*Built with ❤️ and Datadog purple* 