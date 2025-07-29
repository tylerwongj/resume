# Tyler Wong Portfolio Website

A modern, responsive portfolio website showcasing Unity game development expertise and professional experience.

## 🎯 Features

- **Full-screen hero section** with professional photo background
- **Two-column portfolio layout** showcasing games with metrics
- **Eye-friendly dark color scheme** optimized for extended viewing
- **Responsive design** that works on all devices
- **Smooth animations** and scroll interactions
- **Optimized performance** with lazy loading and efficient CSS
- **Accessibility features** including keyboard navigation

## 🎨 Design Philosophy

Based on the Squarespace Tepito template but customized with:
- Tyler's eye-friendly dark color palette
- Real project data and metrics
- Professional presentation for Unity developer roles
- Focus on quantifiable results (1,000+ downloads, ratings, etc.)

## 📁 File Structure

```
plan-website/
├── index.html              # Main HTML file
├── styles.css              # CSS with Tyler's color scheme
├── script.js               # JavaScript for interactions
├── README.md               # This file
├── design-concept.md       # Detailed design documentation
├── visual-mockup.md        # ASCII mockups and layout plans
├── reference-screenshots/  # Squarespace template references
│   └── tepito-template-reference.png
└── mockup-designs/         # Visual mockup files
    ├── hero-section-mockup.html
    ├── hero-section-mockup.png
    ├── portfolio-section-mockup.html
    └── portfolio-section-mockup.png
```

## 🚀 Setup Instructions

### Option 1: Simple Local Development
1. **Open the website**: Double-click `index.html` to open in your browser
2. **View locally**: The website will work immediately for viewing and testing

### Option 2: Local Server (Recommended)
```bash
# If you have Python installed
python -m http.server 8000

# If you have Node.js installed
npx serve .

# Then visit: http://localhost:8000
```

### Option 3: Deploy to Production
The website is ready to deploy to any hosting service:
- **Netlify**: Drag and drop the entire folder
- **Vercel**: Connect to a GitHub repository
- **GitHub Pages**: Upload to a repository and enable Pages
- **Your hosting provider**: Upload all files to your web directory

## 📝 Customization Guide

### Adding Your Professional Photo
1. **Replace background image** in `styles.css` at line ~170:
```css
.hero-background {
  background-image: url('your-professional-photo.jpg');
  /* Uncomment and add your photo */
}
```

### Updating Project Information
1. **Edit content** in `index.html`
2. **Update project descriptions**, metrics, and links
3. **Replace screenshot paths** to point to your actual images

### Color Scheme Customization
The entire color scheme is defined in CSS custom properties at the top of `styles.css`:
```css
:root {
  --bg-primary: #1e1e1e;    /* Main background */
  --acc-blue: #4a9eff;      /* Primary accent */
  /* Modify these values to change the entire color scheme */
}
```

## 🎯 Key Sections

### Hero Section
- **Full-screen professional photo** background
- **Name and title** with professional tagline
- **Key statistics** (6 published games, 1,000+ downloads, 5+ years)
- **Smooth scroll indicator** to portfolio section

### Portfolio Section
- **Car Fall 3D**: 1,000+ downloads, 3.3/5 stars, with YouTube trailer
- **Puzzle Split**: Strategic puzzle game with multi-character control
- **Burn Destructible Art**: Creative art tool demonstration
- **TruPlay Games**: Current professional role with skill visualization

### About Section
- **Professional timeline** with key positions
- **Skills breakdown** by category
- **Experience highlights** and achievements

## 📱 Mobile Responsiveness

The website is fully responsive with:
- **Mobile navigation** menu with hamburger toggle
- **Stacked layouts** on smaller screens
- **Touch-optimized** interactions
- **Readable typography** at all screen sizes

## ⚡ Performance Features

- **Lazy loading** for images
- **Optimized animations** using CSS transforms
- **Throttled scroll events** for smooth performance
- **Minimal JavaScript** footprint
- **Efficient CSS** with custom properties

## 🔧 Browser Support

Works on all modern browsers:
- Chrome/Edge 88+
- Firefox 87+
- Safari 14+
- Mobile browsers

## 🎨 Color Scheme Reference

Tyler's eye-friendly dark mode palette:
- **Background Primary**: #1e1e1e (main background)
- **Background Secondary**: #2d2d2d (sections)
- **Text Primary**: #e8e8e8 (main text)
- **Accent Blue**: #4a9eff (links, CTAs)
- **Accent Green**: #5cb85c (success, downloads)

## 📞 Contact Integration

The website includes:
- **Email**: tylerwong.j@gmail.com
- **Location**: Walnut, CA
- **LinkedIn**: https://www.linkedin.com/in/tylerwongj/
- **GitHub**: https://github.com/tylerwongj

## 🔄 Future Enhancements

Consider adding:
- **Contact form** with email integration
- **Blog section** for technical posts
- **Live project demos** with embedded games
- **Testimonials** section once you have recommendations
- **Case study pages** with detailed project breakdowns

---

**Built with**: HTML5, CSS3, JavaScript, and attention to accessibility and performance.
**Optimized for**: Unity developer job applications and professional networking.