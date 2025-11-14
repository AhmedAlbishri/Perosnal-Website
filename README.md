# Dr. Ahmed Albishri - Academic Portfolio Website

A modern, responsive personal academic portfolio website showcasing research, projects, education, and professional experience.

## 🌐 Live Website

Visit the live website: [https://ahmedalbishri.github.io/](https://ahmedalbishri.github.io/)

## ✨ Features

- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern Minimalist UI** - Clean, professional design with smooth animations
- **SEO Optimized** - Complete meta tags, Open Graph, and Twitter Card support
- **Accessibility** - ARIA labels, semantic HTML, and keyboard navigation support
- **Performance** - Optimized images with lazy loading and efficient CSS
- **Typed.js Animation** - Dynamic typing animation for hero section (CDN with local fallback)
- **Smooth Scrolling** - Enhanced navigation experience
- **Mobile Menu** - Responsive sidebar navigation for mobile devices

## 🛠️ Technologies Used (Simple):

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS with custom properties (variables), flexbox, and animations
- **JavaScript (Vanilla)** - No frameworks, pure JavaScript for interactivity
- **Typed.js** - JavaScript typing animation library (CDN with local fallback)
- **Font Awesome 4.3.0** - Icon library (via CDN)

## 📦 Installation & Deployment

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/AhmedAlbishri/ahmedalbishri.github.io.git
   cd ahmedalbishri.github.io
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

### GitHub Pages Deployment

1. Create a repository named `<your-username>.github.io` (or use an existing repository)
2. Push the code to the `main` or `master` branch
3. Go to repository Settings → Pages
4. Select the branch and folder (usually `/root`)
5. Your site will be live at `https://<your-username>.github.io`

**Note:** If using a custom repository name, update the base URL in:
- Open Graph meta tags (`og:url`)
- Canonical URL (`<link rel="canonical">`)
- All absolute URLs in the HTML

## 📁 Project Structure

```
.
├── assets/
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── img/
│   │   ├── favicon/           # Favicon files
│   │   ├── Ahmed.png          # Profile image
│   │   ├── KAU_logo.png       # University logos
│   │   ├── UMKC_logo.png
│   │   └── ...
│   ├── resume/
│   │   └── Dr. Ahmed_Albishri_Resume.pdf
│   └── vendor/
│       └── typed.js/          # Typed.js library (fallback)
├── index.html                 # Main HTML file
└── README.md                  # This file
```

## 🎨 Customization

### Updating Content

1. **Personal Information**: Edit the content in `index.html`
2. **Styling**: Modify CSS variables in `assets/css/style.css`:
   ```css
   :root {
     --color-primary: #000000;
     --color-bg: #ffffff;
     /* ... */
   }
   ```
3. **Images**: Replace images in `assets/img/` directory
4. **Resume**: Update PDF in `assets/resume/`

### Adding New Sections

1. Add a new `<section>` in `index.html`
2. Add corresponding navigation link in the sidebar
3. Style the section in `style.css`