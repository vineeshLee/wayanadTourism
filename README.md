# 🌄 Wayanad Tourism Website

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)

A modern, fully responsive tourism website showcasing the breathtaking beauty and attractions of Wayanad, Kerala - "God's Own Country". Built with cutting-edge web technologies and featuring an integrated AI chatbot for enhanced visitor experience.

## 📸 Screenshots

### 🖥️ Desktop View
![Desktop Homepage](screenshots/desktop-homepage.png)
*Main homepage showcasing hero section and navigation*

![Desktop Destinations](screenshots/desktop-destinations.png)
*Destinations section with detailed information*

### 📱 Mobile View
![Mobile Homepage](screenshots/mobile-homepage.png)
*Responsive mobile design with hamburger menu*

![Mobile Gallery](screenshots/mobile-gallery.png)
*Mobile-optimized photo gallery*

### 💬 Chatbot Integration
![Chatbot Interface](screenshots/chatbot-interface.png)
*AI-powered chatbot for visitor assistance*

## ✨ Features

### 🎯 Core Features
- **🏔️ Destination Showcase** - 6 major tourist destinations with detailed descriptions
- **🎢 Attractions Guide** - Must-see attractions and activities
- **🏨 Hotel Directory** - Curated selection of accommodations (budget to luxury)
- **📸 Photo Gallery** - High-quality images of Wayanad's landscapes
- **📞 Contact System** - Interactive contact form and information
- **🤖 AI Chatbot** - Dify-powered conversational assistant

### 🎨 Design & UX
- **📱 Fully Responsive** - Optimized for desktop, tablet, and mobile
- **🎭 Smooth Animations** - CSS transitions and JavaScript animations
- **🎯 Modern UI/UX** - Clean, professional design with intuitive navigation
- **♿ Accessibility** - WCAG compliant with proper semantic HTML
- **⚡ Performance** - Optimized loading with lazy image loading

### 🛠️ Technical Features
- **🔧 Modern Build System** - Vite for fast development and optimized builds
- **📦 Modular Architecture** - Well-organized, maintainable code structure
- **🎪 Interactive Elements** - Hover effects, scroll animations, form validation
- **🔍 SEO Optimized** - Meta tags, semantic HTML, and performance best practices
- **🌐 Cross-browser** - Compatible with all modern browsers

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager
- Git (for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/wayanad-tourism.git
   cd wayanad-tourism
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production

```bash
# Create optimized production build
npm run build

# Preview production build locally
npm run preview
```

## 📁 Project Structure

```
wayanad-tourism/
├── 📄 index.html              # Main HTML file with all sections
├── 🎨 style.css               # Complete CSS styling and responsive design
├── ⚙️ main.js                 # JavaScript functionality and interactions
├── 📦 package.json            # Project dependencies and scripts
├── ⚡ vite.config.js           # Vite build configuration
├── 🚫 .gitignore             # Git ignore rules
├── 📖 README.md               # Project documentation
├── 📸 screenshots/            # Screenshots for documentation
│   ├── desktop-homepage.png
│   ├── desktop-destinations.png
│   ├── mobile-homepage.png
│   ├── mobile-gallery.png
│   └── chatbot-interface.png
└── 🏗️ dist/                   # Production build output (after npm run build)
```

## 🏗️ Architecture

### Frontend Stack
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript (ES6+)** - No frameworks, pure JavaScript
- **Vite** - Fast build tool and development server

### Key Components

#### Navigation System
```javascript
// Mobile hamburger menu toggle
const hamburger = document.getElementById('hamburger');
hamburger.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});
```

#### Scroll Animations
```javascript
// Intersection Observer for lazy loading
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
});
```

#### Chatbot Integration
```javascript
// Dify Chatbot Configuration
window.difyChatbotConfig = {
  token: 'YNcd253GopRs5KBs',
  // Additional configuration options
};
```

## 🎯 Sections Overview

### 1. 🏠 Hero Section
- Eye-catching banner with background image
- Call-to-action button for smooth scroll
- Responsive typography and layout

### 2. 🏔️ Destinations (6 Featured)
- **Chembra Peak** - Highest mountain trek (2,100m)
- **Pookot Lake** - Natural freshwater lake
- **Banasura Dam** - Asia's second-largest earth dam
- **Soochipara Falls** - 200-meter waterfall
- **Wildlife Sanctuary** - Tiger reserve and bird watching
- **Jatayu Rock** - Monolithic rock formation

### 3. 🎢 Attractions (6 Experiences)
- **Spy Garden Museum** - Espionage artifacts
- **Spice Plantations** - Cardamom, pepper, cinnamon tours
- **Tea Gardens** - Tea picking and processing
- **Ancient Temples** - Historical religious sites
- **Photography Points** - Scenic viewpoints
- **Adventure Sports** - Paragliding, trekking, camping

### 4. 🏨 Hotels & Resorts (6 Options)
- **Grand Wayanad Palace** (★★★★★) - ₹15,000-25,000/night
- **Green Valley Resort** (★★★★) - ₹8,000-12,000/night
- **Wayanad Valley Inn** (★★★) - ₹3,000-6,000/night
- **Eco-Retreat Wayanad** (★★★★) - ₹7,000-11,000/night
- **Treehouse Paradise** (★★★★★) - ₹12,000-18,000/night
- **Wayanad Homestay** (★★★) - ₹2,500-5,000/night

### 5. 📸 Photo Gallery
- 6 high-quality landscape images
- Hover zoom effects
- Responsive grid layout

### 6. 📞 Contact Section
- Contact information display
- Interactive contact form
- Form validation and submission

### 7. 🔗 Footer
- Social media links
- Copyright information
- Additional navigation

## 🤖 AI Chatbot Integration

### Features
- **Conversational AI** - Powered by Dify platform
- **Tourism Assistance** - Answers visitor queries
- **24/7 Availability** - Always accessible chat support
- **Customizable** - Configurable through Dify dashboard

### Configuration
```javascript
window.difyChatbotConfig = {
  token: 'YNcd253GopRs5KBs',
  inputs: {
    // Define input variables from Start node
  },
  systemVariables: {
    // System-level variables
  },
  userVariables: {
    // User-specific variables
  },
}
```

### Styling
```css
#dify-chatbot-bubble-button {
  background-color: #1C64F2 !important;
}
#dify-chatbot-bubble-window {
  width: 24rem !important;
  height: 40rem !important;
}
```

## 🎨 Design System

### Color Palette
- **Primary**: `#2c5f2d` (Forest Green)
- **Secondary**: `#d4af37` (Gold)
- **Text**: `#333333` (Dark Gray)
- **Background**: `#f5f5f5` (Light Gray)
- **White**: `#ffffff`

### Typography
- **Primary Font**: Segoe UI, system fonts
- **Headings**: 700 weight for impact
- **Body**: 400 weight for readability

### Responsive Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🧪 Testing

### Browser Testing
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

### Device Testing
- ✅ iPhone (various sizes)
- ✅ Android phones
- ✅ iPad and tablets
- ✅ Desktop computers

### Performance Testing
- ✅ Lighthouse scores > 90
- ✅ Page load time < 3 seconds
- ✅ Mobile performance optimized

## 🚀 Deployment

### Netlify (Recommended)
1. Connect GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy automatically on push

### Vercel
1. Import project from GitHub
2. Configure build settings
3. Deploy with zero configuration

### Manual Deployment
```bash
# Build the project
npm run build

# Deploy dist/ folder to your hosting provider
# Examples: AWS S3, Firebase Hosting, GitHub Pages
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow HTML5 semantic markup
- Use CSS custom properties for theming
- Write clean, readable JavaScript
- Test on multiple devices and browsers
- Follow commit message conventions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Wayanad Tourism

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

### Images
- **Unsplash** - High-quality stock photography
- **Pexels** - Additional image resources

### Technologies
- **Vite** - Fast build tool and dev server
- **Dify** - AI chatbot platform
- **Google Fonts** - Typography

### Inspiration
- Wayanad Tourism Board
- Kerala Tourism Department
- Local tourism operators

## 📞 Contact & Support

### Project Support
- **GitHub Issues**: [Report bugs and request features](https://github.com/your-username/wayanad-tourism/issues)
- **Discussions**: [Community discussions](https://github.com/your-username/wayanad-tourism/discussions)

### Tourism Information
- **Official Website**: [www.wayanadtourism.in](https://www.wayanadtourism.in)
- **Phone**: +91-496-2203366
- **Email**: info@wayanadtourism.in
- **Address**: Kalpetta, Wayanad, Kerala 673121

## 🔄 Version History

### v1.0.0 (Current)
- ✅ Complete responsive tourism website
- ✅ 6 destinations with detailed information
- ✅ 6 attractions and activities
- ✅ 6 hotel options with pricing
- ✅ Photo gallery with 6 images
- ✅ Contact form and information
- ✅ Dify chatbot integration
- ✅ Mobile-responsive design
- ✅ Smooth animations and interactions

### Future Releases
- **v1.1.0** - Online booking system
- **v1.2.0** - Weather integration
- **v1.3.0** - Multi-language support
- **v2.0.0** - React.js migration

---

<div align="center">

**Made with ❤️ for Wayanad Tourism**

⭐ Star this repository if you found it helpful!

[🌐 Live Demo](https://wayanad-tourism-demo.netlify.app) •
[📖 Documentation](https://github.com/your-username/wayanad-tourism/wiki) •
[🐛 Report Issues](https://github.com/your-username/wayanad-tourism/issues)

</div>

