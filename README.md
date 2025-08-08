# 🚀 Rishabh Sharma | Developer Portfolio

[![GitHub last commit](https://img.shields.io/github/last-commit/rishaabh/rishabh.github.io?style=flat-square)](https://github.com/rishaabh/rishabh.github.io/commits/main)
[![Website Status](https://img.shields.io/website?style=flat-square&url=https%3A%2F%2Frishaabh.github.io)]([https://rishaabh.github.io](https://sharma18b.github.io/rishabh.github.io/#))
[![GitHub repo size](https://img.shields.io/github/repo-size/rishaabh/rishabh.github.io?style=flat-square)](https://github.com/rishaabh/rishabh.github.io)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

## 📌 Overview

A modern, performance-optimized portfolio showcasing my journey as a Software Engineer at Amazon. This digital presence serves as both a comprehensive resume and a technical showcase, highlighting my professional experience, technical capabilities, and project portfolio.

**[✨ Live Site](https://rishaabh.github.io)**

![Portfolio Preview](assets/img/portfolio-preview.png)

## 🎯 Key Features

### 🎨 **Modern Design**
- **Glassmorphism Floating Dock**: Unique macOS-style navigation with blur effects
- **Responsive Architecture**: Fluid design system that adapts seamlessly across all device form factors
- **Intelligent Theming**: Context-aware dark/light mode with manual override
- **Interactive Elements**: Micro-interactions and subtle animations enhancing user engagement

### ⚡ **Performance & Accessibility**
- **Performance Optimized**: Lighthouse score of 90+ across all metrics
- **Accessibility Focused**: WCAG 2.1 AA compliant with semantic HTML and proper ARIA attributes
- **SEO Optimized**: Structured data and meta tags for better search visibility

### 📝 **Content Management**
- **Dynamic Blog System**: JSON-based blog management for easy updates
- **Real Project Showcase**: Authentic GitHub projects with live links
- **Professional Tone**: Humble and approachable content strategy

## 🛠️ Technical Stack

```
Frontend Core:
├── HTML5 (Semantic markup)
├── CSS3 (Custom properties, Flexbox, Grid, Glassmorphism)
└── JavaScript (ES6+, Vanilla)

Framework & Libraries:
├── Bootstrap 5 (Component architecture)
├── AOS (Scroll-based animations)
├── GlightBox (Media galleries)
└── Swiper (Touch carousels)

Performance:
├── Lazy loading
├── Image optimization
├── Minification
└── Critical CSS extraction

Deployment:
└── GitHub Pages (CI/CD via GitHub Actions)
```

## 🏗️ Architecture

The project follows a component-based architecture with clear separation of concerns:

```
rishabh.github.io/
├── assets/                  # Static resources
│   ├── css/                 # Stylesheets
│   │   ├── style.css        # Main stylesheet
│   │   └── variables.css    # CSS custom properties
│   ├── data/                # Dynamic content
│   │   └── blogs.json       # Blog posts data
│   ├── img/                 # Optimized images
│   ├── js/                  # JavaScript modules
│   │   ├── main.js          # Core functionality
│   │   └── theme.js         # Theme switching logic
│   └── vendor/              # Third-party libraries
├── forms/                   # Form handling
│   └── contact.php          # Contact form processor
├── index.html               # Main entry point
├── resume.html              # Resume/CV page
├── projects.html            # Projects showcase
├── blog.html                # Technical blog
├── contact.html             # Contact information
└── README.md                # Project documentation
```

## 🎨 **Unique Features**

### **Glassmorphism Floating Dock Navigation**
- **Desktop**: Vertical dock on the left with hover animations
- **Mobile**: Horizontal dock at bottom for touch-friendly navigation
- **Interactive**: Scale effects, tooltips, and smooth transitions
- **Accessible**: Proper ARIA labels and keyboard navigation

### **Dynamic Blog Management**
- **JSON-based**: Easy content updates via `assets/data/blogs.json`
- **Auto-loading**: JavaScript dynamically generates blog cards
- **Medium Integration**: Direct links to published articles
- **Responsive Cards**: 3-column desktop, 2-column tablet, 1-column mobile

### **Real Project Showcase**
- **GitHub Integration**: Live links to actual repositories
- **Diverse Portfolio**: AI/ML, Web Development, and Robotics projects
- **Interactive Filtering**: Filter projects by category
- **Professional Presentation**: Clean cards with tech stack badges

## 🔄 Development Workflow

This project follows a trunk-based development model:

1. **Feature Development**:
   ```bash
   git checkout -b feature/new-component
   # Make changes
   git commit -am "feat: add new component with responsive design"
   git push origin feature/new-component
   ```

2. **Content Updates**:
   ```bash
   # Update blog content
   vim assets/data/blogs.json
   
   # Add new project
   # Update projects.html with new project card
   ```

3. **Deployment**:
   - Push to `main` triggers automatic GitHub Pages deployment
   - Changes are live within minutes

## 🚀 Local Development

```bash
# Clone the repository
git clone https://github.com/rishaabh/rishabh.github.io.git

# Navigate to project directory
cd rishabh.github.io

# Start local development server (choose one)
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js with live-server
npx live-server --port=8000

# Option 3: PHP (for contact form testing)
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📊 Performance Metrics

| Metric          | Score | Target |
|-----------------|-------|--------|
| Performance     | 94    | 95+    |
| Accessibility   | 98    | 100    |
| Best Practices  | 100   | 100    |
| SEO             | 100   | 100    |
| First Load Time | 1.2s  | <1.5s  |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/rishabh18b/)
- [Twitter](https://x.com/rissshhhhabh)
- [Medium](https://risharma18b.medium.com/)
- [Email](mailto:risharma18b@gmail.com)

---

*Built with ❤️ by Rishabh Sharma*
