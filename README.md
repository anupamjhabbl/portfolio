# Modern Portfolio Website

A beautiful, responsive, and animated single-page portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, modern design, and mobile-first responsive layout.

## ✨ Features

- **Modern Design**: Clean, professional design with gradient accents
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Responsive Layout**: Mobile-first design that works on all devices
- **Interactive Elements**: Animated skill bars, timeline, and project cards
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation
- **Loading Screen**: Beautiful loading animation
- **Performance Optimized**: Throttled scroll events and efficient animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. That's it! The website should work immediately

### Local Development
If you want to run it locally with a server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

#### Hero Section
```html
<span class="title-name">Your Name</span>
<span class="title-role">Your Role</span>
<p class="hero-description">Your description here</p>
```

#### About Section
```html
<p>Your personal story and background</p>
<div class="about-stats">
    <div class="stat-item">
        <span class="stat-number">5+</span>
        <span class="stat-label">Years Experience</span>
    </div>
    <!-- Add more stats as needed -->
</div>
```

#### Skills Section
Update the skill percentages in the HTML:
```html
<div class="skill-progress" data-width="90"></div>
```

#### Projects Section
Replace the placeholder projects with your own:
```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project image here -->
        <img src="path/to/your/image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">Live Demo</a>
            <a href="your-github-link" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

#### Experience Section
Update the timeline with your work experience:
```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="timeline-company">Company Name</span>
            <span class="timeline-date">2020 - Present</span>
        </div>
        <p>Job description and achievements</p>
        <div class="timeline-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

#### Contact Section
Update your contact information:
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>Your Phone Number</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your Location</span>
</div>
```

### Styling Customization

#### Colors
Update the color scheme in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #ffd700;
    --text-color: #333;
    --light-bg: #f8f9fa;
}
```

#### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

Don't forget to import your chosen font in the HTML head section.

### Adding New Sections
To add a new section:

1. Add the HTML structure in `index.html`
2. Add the corresponding CSS in `styles.css`
3. Add any JavaScript functionality in `script.js`

Example new section:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">New Section</h2>
            <div class="section-line"></div>
        </div>
        <!-- Your content here -->
    </div>
</section>
```

## 📱 Responsive Design

The website is built with a mobile-first approach and includes:
- Responsive navigation with hamburger menu
- Flexible grid layouts
- Optimized typography for all screen sizes
- Touch-friendly interactive elements

## 🎭 Animation Features

- **Scroll Animations**: Elements animate as they come into view
- **Hover Effects**: Interactive hover states for cards and buttons
- **Parallax Effects**: Floating elements move at different speeds
- **Typing Effect**: Hero title types out on page load
- **Counter Animations**: Statistics count up when visible
- **Ripple Effects**: Button click animations
- **Smooth Transitions**: All interactive elements have smooth transitions

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain or use the provided Netlify subdomain

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this portfolio template.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Modern CSS techniques and animations
- Inspiration from award-winning portfolio websites

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to:
- Open an issue on GitHub
- Check the code comments for guidance
- Refer to the customization guide above

---

**Happy coding! 🎉**
