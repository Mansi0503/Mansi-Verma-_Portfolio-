# 🚀 Mansi Verma - AI/ML & Data Analytics Portfolio

> A modern, interactive portfolio showcasing AI/ML expertise, data analytics projects, and professional achievements.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📋 Table of Contents

- [✨ Features](#features)
- [🎯 Live Demo](#live-demo)
- [🛠️ Technologies Used](#technologies-used)
- [📂 Project Structure](#project-structure)
- [🚀 Quick Start](#quick-start)
- [💻 Usage](#usage)
- [📱 Responsive Design](#responsive-design)
- [📊 Sections Overview](#sections-overview)
- [🔧 Customization](#customization)
- [📦 Deployment](#deployment)
- [🤝 Contributing](#contributing)
- [📝 License](#license)
- [📞 Contact](#contact)

---

## ✨ Features

### 🎨 Modern UI/UX
- **Glassmorphism Design** - Beautiful frosted glass effect with blur backdrop
- **Smooth Animations** - GSAP-powered transitions and micro-interactions
- **Gradient Accents** - Modern color palette (Indigo, Cyan, Pink)
- **Responsive Layout** - Perfect on desktop, tablet, and mobile devices

### 🎯 Interactive Elements
- **Animated Counter** - Stats auto-count on page load (DSA problems, CGPA, projects)
- **Floating Badges** - Continuously animated profile badges
- **Hover Effects** - Smooth transitions on cards and buttons
- **Animated Charts** - Interactive data visualizations (Radar & Line charts)
- **Progress Bars** - Animated skill proficiency indicators

### 📊 Data Visualizations
- **Skills Radar Chart** - 6-dimension skill analysis
- **Career Growth Chart** - AI/ML & Data Analytics progress tracking
- Both charts fully interactive with hover details

### 💼 Professional Sections
- **Hero Section** - Eye-catching introduction with CTA buttons
- **Skills** - Organized skill categories with proficiency levels
- **Projects** - Featured projects with tech stacks and live demos
- **Experience** - Timeline-based experience presentation
- **Education** - Degree and certifications showcase
- **Contact** - Multiple contact options with link styling

---

## 🎯 Live Demo

🌐 **Live Portfolio**: [View Live](https://claude.ai/artifact/DSSwVsKwCNf3y44keJMy1k)


---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients, animations, glassmorphism
- **JavaScript (Vanilla)** - Interactive elements and animations

### Libraries & Tools
| Tool | Purpose |
|------|---------|
| **Chart.js** | Data visualization (charts) |
| **GSAP** | Advanced animations |
| **ScrollMagic** | Scroll-triggered animations |
| **Font Awesome** | Icon library |

### Deployment
- **Netlify** - Fast, reliable hosting with auto-deployment
- **Vercel** - Alternative modern deployment platform
- **GitHub Pages** - Free GitHub-based hosting

---

## 📂 Project Structure

```
portfolio/
├── index.html              # Main portfolio file
├── README.md              # This file
├── assets/
│   ├── images/            # Profile photo and project images
│   ├── icons/             # SVG icons
│   └── favicon.ico        # Website favicon
└── docs/
    ├── DEPLOYMENT.md      # Deployment guide
    └── CUSTOMIZATION.md   # How to customize
```

---

## 🚀 Quick Start

### Option 1: View Live (No Installation)
Simply click the [Live Demo](#live-demo) link above to see the portfolio in action.

### Option 2: Download & Open Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mansi0503/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   ```bash
   # On macOS
   open index.html
   
   # On Windows (PowerShell)
   start index.html
   
   # Or right-click → Open with → Browser
   ```

3. **For development (with live reload)**
   ```bash
   # Using Python (if installed)
   python3 -m http.server 8000
   
   # Using Node.js http-server
   npx http-server
   ```
   Then visit `http://localhost:8000`

---

## 💻 Usage

### Viewing the Portfolio
1. Open `index.html` in any modern web browser
2. Navigate using the sticky navbar (smooth scroll)
3. Interact with animated elements and charts
4. Click contact links to reach out

### Key Features to Try
- ✨ Hover over skill cards to see animations
- 📊 Interact with charts (zoom, hover for details)
- 🎯 Click section links in navbar for smooth scrolling
- 📱 Resize window to see responsive design
- 🔗 Click project links to view live demos

---

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:

| Device | Breakpoint | Optimization |
|--------|-----------|--------------|
| **Desktop** | 1200px+ | Full layout, all features |
| **Tablet** | 768px - 1199px | Adapted grid, touch-friendly |
| **Mobile** | < 768px | Single column, optimized touch |

**Browser Support:**
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

---

## 📊 Sections Overview

### 1. **Hero Section**
- Animated introduction
- Professional headline and description
- Call-to-action buttons
- Floating profile badges

### 2. **Skills**
- 6 organized skill categories
- Color-coded tags
- Animated progress bars
- Interactive radar chart

### 3. **Projects**
- 3 featured projects:
  - AI Placement Copilot (Streamlit + Gemini API)
  - Blood Sugar Analytics (Power BI + DAX)
  - Heart Disease Prediction (ML + Scikit-Learn)
- Tech stack badges
- Links to live demos

### 4. **Experience**
- Animated timeline
- AI/ML Internship details
- Key achievements and learnings

### 5. **Education**
- B.Tech CSE (AI & ML) at VIT Bhopal
- CGPA: 8.28
- Professional certifications
  - Applied Machine Learning in Python (Coursera)
  - Cloud Computing (NPTEL)
  - Internet of Things (NPTEL)
  - Data Analysis (NASSCOM)

### 6. **Contact**
- Phone, Email, LinkedIn, GitHub
- Glassmorphic design
- Hover animations

---

## 🔧 Customization

### Update Personal Information
Edit the HTML file to customize:

```html
<!-- Update name and headline -->
<h1>Your Name</h1>
<div class="hero-subtitle">Your Title</div>

<!-- Update description -->
<p class="hero-desc">Your professional summary...</p>

<!-- Update contact links -->
<a href="tel:+919999999999">Your Phone</a>
<a href="mailto:your.email@gmail.com">Email</a>
```

### Change Colors
Update CSS variables in the `<style>` section:

```css
:root {
    --primary: #6366f1;        /* Your primary color */
    --secondary: #06b6d4;      /* Your secondary color */
    --accent: #ec4899;         /* Your accent color */
}
```

### Add/Remove Projects
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <div class="project-tech">
            <span class="tech-badge">Technology</span>
        </div>
    </div>
    <div class="project-content">
        <p>Project description...</p>
        <a href="link" class="project-link">View Project</a>
    </div>
</div>
```

### Modify Skills
Update skill categories and tags:

```html
<div class="skill-card">
    <h3>Category Name</h3>
    <div class="skill-tags">
        <span class="tag">Skill 1</span>
        <span class="tag">Skill 2</span>
    </div>
</div>
```

See [CUSTOMIZATION.md](docs/CUSTOMIZATION.md) for detailed guide.

---

## 📦 Deployment

### Deploy to Netlify (Recommended ⭐)

1. **Download** `index.html`
2. Go to **netlify.com**
3. **Drag & drop** your file
4. Your portfolio is live! 🎉

**Get Custom Domain:**
- In Netlify dashboard → Site settings → Domain management
- Connect your custom domain (mansiverma.com, etc.)

### Deploy to Vercel

```bash
npm install -g vercel
vercel
```

### Deploy to GitHub Pages

1. Create repository: `yourusername.github.io`
2. Upload `index.html`
3. Enable GitHub Pages in settings
4. Access at: `https://yourusername.github.io`

See [DEPLOYMENT.md](docs/DEPLOYMENT.md) for detailed deployment guide.

---

## 🤝 Contributing

This is a personal portfolio, but you're welcome to:
- Report issues or bugs
- Suggest design improvements
- Fork and customize for yourself
- Share feedback

### To Contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit (`git commit -m 'Add improvement'`)
5. Push to branch (`git push origin feature/improvement`)
6. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

**What you can do:**
- ✅ Use for personal portfolio
- ✅ Modify and customize
- ✅ Fork and redistribute
- ✅ Use commercially

**What you must do:**
- ✅ Include license and copyright notice

---

## 📞 Contact & Connect

I'm always interested in discussing AI/ML projects, data analytics opportunities, and collaborations.

| Platform | Handle/Link |
|----------|------------|
| **Phone** | +91-6394352131 |
| **Email** | mv699205@gmail.com |
| **LinkedIn** | [linkedin.com/in/mansi-verma-94328b2a7](https://linkedin.com/in/mansi-verma-94328b2a7) |
| **GitHub** | [github.com/Mansi0503](https://github.com/Mansi0503) |
| **Portfolio** | [Your Portfolio Link] |

---

## 📚 Additional Resources

- [HTML Semantic Markup](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [CSS Grid & Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [GSAP Animations](https://greensock.com/gsap/)
- [Chart.js Documentation](https://www.chartjs.org/)

---

## 🎓 About Me

**Mansi Verma**
- 🎓 B.Tech CSE (AI & ML) @ VIT Bhopal (2023-2027)
- 🤖 Specializing in Machine Learning & Data Analytics
- 💼 AI/ML Intern @ YoungMinds Technology Solutions
- 🏆 150+ DSA Problems solved on LeetCode
- 🎯 Passionate about building practical AI solutions

---

## ⭐ If you like this portfolio, please give it a star! ⭐

```
✨ Built with passion for AI/ML Excellence ✨
```

---

## 📋 Checklist Before Sharing

- [ ] Update all personal information
- [ ] Add your actual profile photo
- [ ] Update contact links
- [ ] Test all links and animations
- [ ] Deploy to live hosting
- [ ] Share on LinkedIn, GitHub, email
- [ ] Monitor portfolio visits (if using analytics)

---

## 🐛 Troubleshooting

### Portfolio looks broken?
- Check browser compatibility (use Chrome/Firefox)
- Clear browser cache (Ctrl+Shift+Del)
- Disable browser extensions (if issues persist)

### Images not showing?
- Ensure image paths are correct
- Use relative paths or base64 encoding
- Check CORS settings if hosted online

### Charts not displaying?
- Verify Chart.js CDN is accessible
- Check browser console for errors (F12)
- Update Chart.js to latest version

### Animations not smooth?
- Use modern browser (Chrome 90+)
- Disable other extensions
- Check system performance

---

**Last Updated:** October 2026  
**Version:** 1.0.0

---

<div align="center">

### Made with ❤️ for AI & Data Excellence

[⬆ Back to Top](#-mansi-verma---aiml--data-analytics-portfolio)

</div>
