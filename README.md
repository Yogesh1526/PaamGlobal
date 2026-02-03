# PAAM Global & Services Website

A modern, attractive, and responsive website for PAAM Global & Services - a versatile trading and manufacturing company.

## Features

- ✨ Modern and attractive design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🚀 Fast loading and optimized
- ♿ Accessible navigation
- 📧 Contact form ready for integration

## File Structure

```
PAAM GLOBAL & SERVICES/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## How to Use

1. **Open the website**: Simply open `index.html` in your web browser
2. **For development**: Use a local server (recommended)
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve`
   - VS Code: Use Live Server extension

## Replacing Images with AI-Generated Images

The website currently uses placeholder images from Unsplash. To replace them with AI-generated images:

1. **Hero Section Background**: 
   - Location: `index.html` line ~45 (hero section)
   - Replace the `background-image` URL in CSS or the `::before` pseudo-element

2. **About Section Image**:
   - Location: `index.html` line ~120
   - Replace the `src` attribute with your AI-generated image URL

3. **Service Cards Images**:
   - Location: Multiple service cards in `index.html`
   - Each service card has an image - replace the `src` attribute

### Recommended Image Sizes:
- Hero background: 1920x1080px
- About section: 800x600px
- Service cards: 600x400px

### Image Suggestions:
- **Hero**: Industrial facility, machinery, or professional business setting
- **About**: Team photo, office, or manufacturing facility
- **Services**: 
  - Industrial belting and machinery
  - Abrasives and tools
  - Hardware components
  - Printing equipment
  - Pipes and fittings
  - Balata belts

## Customization

### Colors
Edit the CSS variables in `styles.css` (lines 7-16):
```css
:root {
    --primary-color: #1e3a8a;
    --secondary-color: #3b82f6;
    --accent-color: #f59e0b;
    /* ... */
}
```

### Content
All content can be edited directly in `index.html`. The structure is well-commented and easy to navigate.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Form

The contact form is currently set up with client-side validation. To make it functional:

1. Set up a backend service (PHP, Node.js, etc.)
2. Update the form submission handler in `script.js` (around line 60)
3. Add your server endpoint URL

## Performance Tips

- Optimize images before uploading (use WebP format when possible)
- Consider using a CDN for images
- Minify CSS and JavaScript for production
- Enable GZIP compression on your server

## License

This website is created for PAAM Global & Services.

---

**Need Help?** Contact: contactmepgs@gmail.com

