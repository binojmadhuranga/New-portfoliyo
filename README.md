# Personal Portfolio Website..

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, mobile-friendly design, and interactive elements.

## Features

- 📱 **Responsive Design** - Works perfectly on all devices
- 🎨 **Modern UI/UX** - Clean and professional design
- ⚡ **Fast Loading** - Optimized performance
- 🌟 **Smooth Animations** - Engaging user experience
- 📧 **Contact Form** - Functional contact form with validation
- 🚀 **Easy Customization** - Simple to modify and personalize

## Sections

1. **Hero/Home** - Introduction with call-to-action buttons
2. **About** - Personal information and statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Portfolio of work with project details
5. **Contact** - Contact form and social media links

## Getting Started

1. **Download/Clone** the files to your computer
2. **Open** `index.html` in your web browser
3. **Customize** the content with your information

## Customization Guide

### Personal Information

**Update the following in `index.html`:**

- Replace "Your Name" with your actual name
- Update the hero title and description
- Modify the about section text
- Add your contact information
- Update social media links

### Skills Section

Edit the skills in the HTML file under the `#skills` section:

```html
<div class="skill-item">
    <i class="fab fa-your-icon"></i>
    <span>Your Skill</span>
</div>
```

### Projects Section

Update project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project image or keep the icon -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="btn btn-small">Live Demo</a>
            <a href="your-github-link" class="btn btn-small btn-outline">GitHub</a>
        </div>
    </div>
</div>
```

### Colors and Styling

**Main color scheme (in `styles.css`):**

- Primary gradient: `#667eea` to `#764ba2`
- Text color: `#2c3e50`
- Background: `#f8f9fa`

To change colors, search and replace these hex codes in the CSS file.

### Adding Your Photos

Replace the placeholder elements with your actual photos:

1. Add your images to the project folder
2. Replace the `.image-placeholder` divs with `<img>` tags
3. Update the CSS to style your images

Example:
```html
<!-- Replace this: -->
<div class="image-placeholder">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With this: -->
<img src="your-photo.jpg" alt="Your Name" class="profile-image">
```

### Font Icons

This template uses Font Awesome icons. You can:

- Browse icons at [fontawesome.com](https://fontawesome.com/icons)
- Replace icon classes in the HTML
- Add new icons for skills, social media, etc.

### Contact Form

The contact form includes:

- Client-side validation
- Success/error notifications
- Responsive design

**To make it functional:**

1. Add a backend service (PHP, Node.js, etc.)
2. Update the form action in JavaScript
3. Or integrate with services like Formspree, Netlify Forms, etc.

## File Structure

```
portfoliyo/
├── index.html      # Main HTML file
├── styles.css      # CSS styles
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize images** - Compress images before adding them
2. **Minimize HTTP requests** - Combine CSS/JS files if needed
3. **Use CDN** - Font Awesome is loaded from CDN
4. **Enable caching** - Configure server caching for better performance

## Deployment

### GitHub Pages

1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch
5. Your site will be available at `username.github.io/repository-name`

### Netlify

1. Drag and drop your folder to [netlify.com](https://netlify.com)
2. Your site is live instantly with a custom URL

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project folder
3. Follow the prompts

## Customization Examples

### Adding a New Section

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <div class="new-content">
            <!-- Your content here -->
        </div>
    </div>
</section>
```

### Adding Navigation Link

```html
<a href="#new-section" class="nav-link">New Section</a>
```

### Custom Animation

```css
@keyframes yourAnimation {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

.your-element {
    animation: yourAnimation 0.6s ease-out;
}
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox/Grid
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icon library

## Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, pull requests are welcome!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:

1. Check this README for common tasks
2. Search for HTML/CSS/JavaScript tutorials online
3. Ask questions in developer communities

---

**Happy coding! 🚀**

*Remember to update this README with your own information and remove any sections that don't apply to your use case.*
