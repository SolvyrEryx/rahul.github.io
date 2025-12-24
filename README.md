# 🎯 Anish Vyapari - Personal Portfolio

> A cosmic, AI-powered portfolio website showcasing AI/ML projects, Discord bot development, and full-stack engineering expertise.

**Live Demo:** [solvyreryx.github.io](https://solvyreryx.github.io)

## 🚀 About

I'm a 2nd-year Computer Science student at RAIT/DYPatil College (AI & ML specialization) based in Mumbai, passionate about AI/ML, full-stack development, and strategic problem-solving. This interactive portfolio demonstrates my technical skills through an immersive, desktop-like interface.

**Current Focus:**
- 🤖 AI/ML Model Integration (Mistral, Google Gemini APIs)
- 🔗 Discord.py Bot Development
- 💻 Full-Stack Web Development
- ☁️ Cloud Deployment (Railway, GitHub Pages)
- ♟️ Chess Strategy (Elo: 1826)
- 📋 AICCONS 2026 Research Paper Reviewer

## ✨ Features

- **Glassmorphism Design** - Modern glass-effect cards with backdrop blur effects
- **Dark Space Theme** - Sleek dark interface with cosmic aesthetic
- **Interactive Apps** - Multiple desktop-style applications:
  - 💬 **NeuralBot (AI Chat)** - Powered by Mistral API with image generation
  - 🔧 **VS Code IDE** - Interactive code editor with Python syntax highlighting
  - 💻 **Terminal** - Functional command-line interface
  - 📊 **System Monitor** - Real-time performance graphs
  - 📁 **File Explorer** - Browse local file system
  - 🌐 **Browser** - Integrated web browser with GitHub & Discord integration
- **Smooth Animations** - Fade-in effects, drift animations, hover interactions
- **Responsive Design** - Fully responsive on mobile, tablet, and desktop
- **Single HTML File** - No build process needed - just pure HTML, CSS, and JavaScript
- **Performance Optimized** - Lightweight and fast loading
- **Chess.com Integration** - Live stats display
- **GitHub Integration** - Dynamic repository showcase
- **Discord Presence** - Live status via Lanyard API

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Styling:** TailwindCSS, Custom CSS Animations
- **APIs & Integration:**
  - Mistral AI API (Neural Chat)
  - Chess.com API (Rating Stats)
  - GitHub API (Repository Showcase)
  - Discord Lanyard API (Status)
  - Pollinations.ai (Image Generation)
  - Unsplash API (Background Images)
- **Fonts:** JetBrains Mono, Inter, FontAwesome Icons

## 🎯 Key Features Deep Dive

### Desktop-Style Interface
- Draggable windows with minimize/maximize/close controls
- Taskbar with app shortcuts
- Start menu for quick access
- Notification system

### AI Chat (NeuralBot)
- Conversational AI powered by Mistral API
- Text-to-image generation using `generate image <prompt>` command
- Context-aware responses about portfolio and projects

### Code Editor (VS Code)
- Syntax highlighting for Python
- File switching (forex_algo.py, neural_net.py, bio.md, etc.)
- Line numbers and status bar
- Editable content with real-time updates

### Browser Hub
- Tools Hub with curated links
- Chess.com profile integration
- GitHub profile showcase
- Discord status display

## 📖 Getting Started

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SolvyrEryx/solvyreryx.github.io.git
   cd solvyreryx.github.io
   ```

2. **Open in browser:**
   - Double-click `index.html` or
   - Use a local server:
     ```bash
     python -m http.server 8000
     # or
     npx serve
     ```
   - Visit `http://localhost:8000`

### Customization

Edit the `index.html` file to customize:

- **Name & Title:** Update the name and professional title in the hero section
- **Links:** Replace GitHub, LinkedIn, and email links with your own
- **Projects:** Modify the project cards in the file system
- **Colors:** Adjust CSS variables in the `:root` selector
- **Background:** Change the Unsplash image URL
- **API Keys:** Add your own Mistral API key (currently requires setup)

## 🔧 Configuration

To enable the AI Chat feature:

1. Get a Mistral API key from [mistral.ai](https://mistral.ai)
2. Add it to the JavaScript configuration in `index.html`
3. For image generation, no API key is needed (uses Pollinations.ai)

## 📁 File Structure

```
solvyreryx.github.io/
├── index.html          # Main portfolio file (1042 lines)
├── README.md          # Project documentation
└── LICENSE            # MIT License
```

## 🚀 Deployment

This project is hosted on **GitHub Pages**. Any changes pushed to the `main` branch will automatically deploy.

### Steps to Deploy Your Fork:

1. Fork this repository
2. Rename it to `yourusername.github.io`
3. Go to **Settings → Pages**
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at `https://yourusername.github.io`

## 🌐 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile Browsers

## 🎨 Design Credits

- **Glassmorphism Design** - Modern UI trend
- **Dark Theme** - GitHub Dark Mode inspired
- **Color Palette** - GitHub's native colors + custom accents
- **Icons** - FontAwesome 6.4.0
- **Fonts** - JetBrains Mono & Inter from Google Fonts

## 💫 Contributing

Found a bug or want to improve the design? Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋 Author

**Anish Vyapari**

- **GitHub:** [@solvyreryx](https://github.com/solvyreryx)
- **LinkedIn:** [@anish-vyapari](https://linkedin.com/in/anish-vyapari/)
- **Email:** [contact@example.com](mailto:contact@example.com)

## 🙊 Acknowledgments

- **TailwindCSS** - For the amazing utility-first CSS framework
- **FontAwesome** - For beautiful icons
- **Mistral AI** - For the powerful API
- **Chess.com & Lanyard** - For the integration APIs
- **GitHub Pages** - For free hosting
- Design inspiration from modern glassmorphism trends

---

**Last Updated:** December 24, 2025

**Status:** ✅ Live and Operational

**Made with ❤️ by Anish Vyapari**
