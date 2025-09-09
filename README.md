# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with dark/light mode toggle, smooth animations, and mobile-friendly layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between themes with persistent preference
- **Smooth Animations**: Intersection Observer animations and hover effects
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Modern UI**: Clean, professional design with gradient accents
- **SEO Friendly**: Semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
PORTFOLIO/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your preferred hosting service

## 🎨 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<!-- Replace "Your Name" with your actual name -->
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">Full-Stack Developer | AI Enthusiast</h2>
<p class="hero-tagline">Passionate about creating innovative solutions and turning ideas into reality through code.</p>
```

#### About Section
```html
<!-- Update the bio text -->
<div class="about-text">
    <p>I'm a passionate Full-Stack Developer with expertise in modern web technologies...</p>
    <!-- Add more paragraphs as needed -->
</div>
```

#### Skills Section
```html
<!-- Update skills in each category -->
<div class="skill-category">
    <h4>Frontend</h4>
    <div class="skill-tags">
        <span class="skill-tag">React</span>
        <span class="skill-tag">Vue.js</span>
        <!-- Add/remove skills as needed -->
    </div>
</div>
```

#### Projects Section
```html
<!-- Update project information -->
<div class="project-card">
    <div class="project-content">
        <h3>E-Commerce Platform</h3>
        <p>A full-stack e-commerce solution with React frontend...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <!-- Add technologies used -->
        </div>
        <div class="project-links">
            <a href="YOUR_GITHUB_LINK" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="YOUR_LIVE_DEMO_LINK" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
        </div>
    </div>
</div>
```

#### Experience Section
```html
<!-- Update work experience -->
<div class="timeline-item">
    <div class="timeline-content">
        <h4>Senior Full-Stack Developer</h4>
        <p class="company">TechCorp Inc.</p>
        <p class="duration">2022 - Present</p>
        <ul>
            <li>Led development of scalable web applications...</li>
            <!-- Add more bullet points -->
        </ul>
    </div>
</div>
```

#### Education Section
```html
<!-- Update education details -->
<div class="education-item">
    <h4>Bachelor of Science in Computer Science</h4>
    <p class="institution">University of Technology</p>
    <p class="year">2016 - 2020</p>
    <p>Graduated with honors. Specialized in software engineering...</p>
</div>
```

#### Contact Section
```html
<!-- Update social links -->
<div class="social-links">
    <a href="YOUR_LINKEDIN_URL" class="social-link"><i class="fab fa-linkedin"></i> LinkedIn</a>
    <a href="YOUR_GITHUB_URL" class="social-link"><i class="fab fa-github"></i> GitHub</a>
    <a href="YOUR_TWITTER_URL" class="social-link"><i class="fab fa-twitter"></i> Twitter</a>
    <a href="mailto:your.email@example.com" class="social-link"><i class="fas fa-envelope"></i> Email</a>
</div>
```

### Color Scheme Customization

To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    /* Light Theme Colors */
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1d4ed8;       /* Darker shade for hover */
    --secondary-color: #64748b;     /* Secondary text color */
    --accent-color: #3b82f6;       /* Accent color for gradients */
    --text-primary: #1e293b;       /* Primary text color */
    --text-secondary: #64748b;     /* Secondary text color */
    --bg-primary: #ffffff;         /* Main background */
    --bg-secondary: #f8fafc;       /* Secondary background */
    --bg-tertiary: #f1f5f9;        /* Tertiary background */
    --border-color: #e2e8f0;       /* Border color */
}

[data-theme="dark"] {
    /* Dark Theme Colors */
    --primary-color: #3b82f6;
    --primary-dark: #2563eb;
    --secondary-color: #94a3b8;
    --accent-color: #60a5fa;
    --text-primary: #f1f5f9;
    --text-secondary: #cbd5e1;
    --bg-primary: #0f172a;
    --bg-secondary: #1e293b;
    --bg-tertiary: #334155;
    --border-color: #334155;
}
```

### Adding Your Photo

Replace the placeholder icon with your photo:

1. Add your photo to the project folder
2. Replace the profile placeholder in `index.html`:

```html
<!-- Replace this -->
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>

<!-- With this -->
<div class="profile-image">
    <img src="your-photo.jpg" alt="Your Name" />
</div>
```

3. Add CSS for the image in `styles.css`:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: var(--shadow-lg);
}

.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Adding Project Screenshots

Replace the placeholder icons with actual project screenshots:

```html
<!-- Replace this -->
<div class="project-placeholder">
    <i class="fas fa-code"></i>
</div>

<!-- With this -->
<div class="project-image">
    <img src="project-screenshot.jpg" alt="Project Name" />
</div>
```

Add CSS for project images:

```css
.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [netlify.com](https://netlify.com)
2. Your site will be deployed instantly
3. You can set up a custom domain later

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Minimize CSS/JS**: Use minified versions for production
3. **Use CDN**: Font Awesome and Google Fonts are already using CDN
4. **Lazy Loading**: Consider adding lazy loading for images

## 🔧 Troubleshooting

### Contact Form Not Working
The contact form is currently set up for demonstration. To make it functional:
1. Use a form service like Formspree or Netlify Forms
2. Or implement a backend solution

### Images Not Loading
1. Check file paths are correct
2. Ensure image files are in the same directory
3. Use relative paths (e.g., `./image.jpg`)

### Dark Mode Not Working
1. Check if JavaScript is enabled
2. Clear browser cache
3. Check browser console for errors

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Happy Coding! 🎉** 