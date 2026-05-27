# GreenValley Academy

> A modern, responsive educational institution website built with Tailwind CSS

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Pages](#-pages)
- [Customization](#-customization)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

GreenValley Academy is a static frontend website for an educational institution located in Manjeri, Kerala, India. The website showcases the academy's programs, activities, and provides information for prospective students and parents.

The site features a modern design with smooth animations, responsive layouts, and an intuitive navigation experience.

---

## ✨ Features

- **Responsive Design** — Fully optimized for mobile, tablet, and desktop devices
- **Hero Carousel** — Dynamic hero section with smooth transitions
- **Animated Elements** — Engaging animations using CSS and JavaScript
- **Image Zoom Effects** — Interactive image hover effects
- **Smooth Scrolling** — Enhanced navigation experience
- **Accessibility** — ARIA labels and semantic HTML
- **Custom Typography** — Google Fonts integration (Roboto & Poppins)
- **Dark Theme** — Elegant dark-themed design with green accents

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic markup |
| Tailwind CSS | Utility-first CSS framework |
| JavaScript | Interactive functionality |
| Google Fonts | Typography |
| Vercel/Netlify | Deployment |

---

## 📂 Project Structure

```
greenvalley_academy_frondend/
├── index.html              # Home page
├── about.html              # About page
├── programmes.html         # Academic programmes
├── activities.html         # Activities page
├── application.html        # Admission application
├── contact.html            # Contact page
├── womens_academy.html     # Women's academy page
├── README.md               # Project documentation
├── assets/
│   ├── css/
│   │   ├── index.css       # Home page styles
│   │   ├── about.css       # About page styles
│   │   ├── programmes.css # Programmes styles
│   │   ├── activities.css  # Activities styles
│   │   ├── application.css # Application styles
│   │   ├── contact.css     # Contact page styles
│   │   └── womens_academy.css # Women's academy styles
│   ├── image/
│   │   ├── home/           # Home page images
│   │   ├── about/          # About page images
│   │   ├── programs/       # Programme images
│   │   ├── activity/       # Activity images
│   │   ├── womens/         # Women's academy images
│   │   ├── ico/            # Icons & favicon
│   │   └── logo/           # Logo assets
│   └── js/
│       └── index.js        # JavaScript functionality
```

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/greenvalley_academy_frondend.git
   cd greenvalley_academy_frondend
   ```

2. **Open in browser**
   Simply open `index.html` in your preferred browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. **View the website**
   Navigate to `http://localhost:8000`

---

## 📄 Pages

| Page | Description |
|------|-------------|
| [index.html](index.html) | Home page with hero carousel and academy overview |
| [about.html](about.html) | About the academy, mission, vision, and gallery |
| [programmes.html](programmes.html) | Academic programmes and courses offered |
| [activities.html](activities.html) | Student activities and events |
| [application.html](application.html) | Online admission application form |
| [contact.html](contact.html) | Contact information and form |
| [womens_academy.html](womens_academy.html) | Women's academy specific programmes |

---

## 🎨 Customization

### Colors

The project uses a custom color palette defined in Tailwind config:

```javascript
// Primary color - Deep green
primary: "#00301C"

// Secondary color - Lime green
secondary: "#D1FB5F"
```

### Fonts

- **Headings**: Roboto (400, 700, 900)
- **Body**: Poppins (300, 400, 500, 600)

### Adding New Pages

1. Create a new HTML file in the root directory
2. Copy the header/footer structure from an existing page
3. Add corresponding CSS in `assets/css/`
4. Update navigation links in all pages

---

## 📦 Deployment

### Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Deploy to Netlify

```bash
# Install Netlify CLI
npm i -g netlify-cli

# Deploy
netlify deploy --prod
```

### GitHub Pages

1. Go to repository Settings
2. Select "Pages" from the sidebar
3. Choose the main branch as source
4. Save and wait for deployment

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

- **Website**: [GreenValley Academy](https://greenvalleyacademy.edu.in)
- **Location**: Manjeri, Kerala, India

---

<p align="center">Built with ❤️ for education</p>