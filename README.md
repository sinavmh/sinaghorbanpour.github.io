# Sina Ghorbanpour - Portfolio Website

A stunning, professional portfolio website for Sina Ghorbanpour, a Biomedical Engineering professional. This website showcases expertise, skills, and experience with a luxurious, modern design that leaves a lasting impression on visitors.

## 🌟 Features

### Design & User Experience
- **Luxurious Design**: Premium aesthetic with emerald green accents and elegant typography
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: Elegant fade-ins, hover effects, and parallax scrolling
- **Professional Typography**: Inter for body text, Playfair Display for headings
- **Modern UI/UX**: Clean, spacious layout with intuitive navigation

### Content Sections
1. **Hero Section**: Eye-catching introduction with bilingual tagline
2. **About Me**: Bilingual content (English & Persian) with language toggle
3. **Skills & Services**: 5 key areas of expertise with icons
4. **Experience & Education**: Timeline showcasing academic journey
5. **Portfolio**: Placeholder sections for future projects
6. **Testimonials**: Space for professional recommendations
7. **Contact**: Contact form and direct contact information

### Technical Features
- **SEO Optimized**: Meta tags, semantic HTML, and proper structure
- **Performance Optimized**: Lightweight, fast-loading design
- **Accessibility**: WCAG compliant with proper contrast and navigation
- **Cross-browser Compatible**: Works on all modern browsers
- **Mobile-first Design**: Responsive grid layouts and touch-friendly interactions

## 🎨 Design System

### Color Palette
- **Primary**: Emerald Green (#10b981)
- **Primary Dark**: Darker Emerald (#059669)
- **Primary Light**: Light Emerald (#34d399)
- **Text Dark**: Dark Gray (#1f2937)
- **Text Light**: Light Gray (#6b7280)
- **Background**: White (#ffffff) and Light Gray (#f9fafb)

### Typography
- **Headings**: Playfair Display (serif)
- **Body Text**: Inter (sans-serif)
- **Responsive Sizing**: Clamp functions for fluid typography

### Animations
- Smooth fade-in effects on scroll
- Hover animations on interactive elements
- Parallax scrolling on hero section
- Typing effect on hero title
- Loading animations

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Text editor (VS Code, Sublime Text, etc.)
- Local web server (optional, for development)

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** content in the HTML file
4. **Modify** styles in `styles.css`
5. **Update** functionality in `script.js`

### File Structure
```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 📝 Customization Guide

### Updating Content

#### Personal Information
Edit the following sections in `index.html`:
- Hero section name and taglines
- About section content (English & Persian)
- Contact information (phone, email, LinkedIn)
- Footer information

#### Skills & Services
Update the skills section by modifying:
```html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fas fa-[icon-name]"></i>
    </div>
    <h3>Skill Title</h3>
    <p>Skill description</p>
</div>
```

#### Experience Timeline
Modify the timeline items in the experience section:
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="timeline-date">Year - Year</div>
        <h3>Position/Title</h3>
        <p>Description of role and achievements</p>
    </div>
</div>
```

#### Portfolio Projects
Replace placeholder content with actual projects:
```html
<div class="portfolio-item">
    <div class="portfolio-placeholder">
        <i class="fas fa-[project-icon]"></i>
        <h3>Project Name</h3>
        <p>Project Description</p>
    </div>
</div>
```

### Styling Customization

#### Colors
Update CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #10b981;      /* Main accent color */
    --primary-dark: #059669;       /* Darker shade */
    --primary-light: #34d399;      /* Lighter shade */
    /* ... other colors */
}
```

#### Typography
Change fonts by updating the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
```

#### Animations
Modify animation timing and effects in `styles.css`:
```css
--transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
```

### Adding Functionality

#### Contact Form
The contact form is currently set up for demonstration. To make it functional:
1. Set up a backend service (Formspree, Netlify Forms, etc.)
2. Update the form action and method in `index.html`
3. Modify form handling in `script.js`

#### Analytics
Add Google Analytics or other tracking:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🌐 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on push
3. Custom domain setup available

### Vercel
1. Import project from GitHub
2. Automatic deployment on push
3. Preview deployments for pull requests

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Optimization

The website is optimized for:
- **Fast Loading**: Minimal external dependencies
- **SEO**: Semantic HTML and meta tags
- **Accessibility**: ARIA labels and keyboard navigation
- **Mobile Performance**: Optimized images and responsive design

## 📞 Support

For customization help or questions:
- Review the code comments for guidance
- Check browser console for any errors
- Ensure all files are in the same directory
- Verify internet connection for external resources (fonts, icons)

## 📄 License

This project is created for Sina Ghorbanpour's personal use. Feel free to use as a template for your own portfolio with appropriate modifications.

## 🎯 SEO Keywords

- Sina Ghorbanpour
- Biomedical Engineering
- Medical Technology
- Healthcare Innovation
- Medical Device Analysis
- Medical Imaging
- Healthcare Solutions
- Biomedical Engineering Portfolio

---

**Built with ❤️ for professional excellence and innovation in healthcare technology.**
