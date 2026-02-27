# Jubilant Designs - Dynamic & Responsive Website

A modern, dynamic, and fully responsive website for Jubilant Designs, a creative branding and design solutions company based in Accra, Ghana.

## Features

### 🎨 Design & UI
- **Modern Aesthetic**: Clean, professional design with gradient accents
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging animations and transitions
- **Accessibility**: WCAG compliant with keyboard navigation support

### 📱 Mobile-First Approach
- Mobile menu toggle with smooth transitions
- Responsive grid layouts that adapt to all screen sizes
- Touch-friendly buttons and interactive elements
- Optimized font sizes for readability

### ✨ Interactive Features
- Fixed navigation bar with smooth scrolling
- Animated scroll-to-top button
- Form validation and email integration
- Counter animations for statistics
- Intersection Observer for lazy loading animations
- Parallax effects in hero section
- Service card hover effects
- Portfolio item animations

### 📑 Page Sections
1. **Navigation Bar** - Fixed header with smooth scroll navigation
2. **Hero Section** - Eye-catching banner with call-to-action
3. **Services** - 4 main service offerings with icons
4. **Portfolio** - Featured works showcasing past projects
5. **About** - Company information with statistics
6. **Contact** - Contact form and information
7. **Footer** - Links and social media integration

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS variables and Grid/Flexbox
- **JavaScript (ES6+)** - Interactive features and animations
- **Font Awesome** - Icon library (via CDN)
- **Google Fonts** - Typography optimization

## Color Scheme

- **Primary**: #667eea (Purple-Blue)
- **Secondary**: #764ba2 (Deep Purple)
- **Accent**: #f5576c (Red)
- **Dark Background**: #0f1419
- **Light Background**: #f8f9fa

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3 or Node.js (for local server)

### Installation & Setup

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/joshua-danquah-website/-Jubilant-Homeschooler.git
   cd -Jubilant-Homeschooler
   ```

2. **Using Python HTTP Server**
   ```bash
   python -m http.server 8000
   # Then open http://localhost:8000 in your browser
   ```

3. **Using Node.js HTTP Server**
   ```bash
   npm install -g http-server
   http-server -p 8000
   # Then open http://localhost:8000 in your browser
   ```

4. **Using npm scripts**
   ```bash
   npm install
   npm start
   # Website opens at http://localhost:8000
   ```

5. **Using Live Server (VS Code)**
   - Install the "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

## Project Structure

```
-Jubilant-Homeschooler/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript interactions
├── package.json        # Project metadata
└── README.md           # This file
```

## Customization Guide

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f5576c;
    /* ... more variables ... */
}
```

### Updating Contact Information
In `index.html`, update the contact section:
```html
<a href="mailto:jubilanthomeschooler@gmail.com">jubilanthomeschooler@gmail.com</a>
<a href="tel:+233303934948">+233 (0) 303-934948</a>
```

### Modifying Services
Edit the services section in `index.html` to add/remove services and update icons from Font Awesome.

### Adding Portfolio Items
Duplicate a `.portfolio-item` div in the Portfolio section and update the content.

### Customizing Text
All text content is in `index.html` - simply find and replace the content you want to change.

## Features in Detail

### Navigation
- Sticky navigation bar that stays at top while scrolling
- Smooth scroll to sections with offset for fixed navbar
- Mobile hamburger menu with animation
- Auto-close menu when a link is clicked

### Contact Form
- Email validation
- Smooth form submission
- Opens user's default email client (mailto)
- Visual feedback on submission
- Form state management

### Animations
- Hero section fade-in animation
- Service cards slide up on view
- Portfolio items scale on hover
- Smooth scroll transitions
- Parallax background in hero
- Floating shapes in background

### Performance
- Lightweight and optimized
- Minimal external dependencies (only Font Awesome icons via CDN)
- Efficient CSS animations (GPU-accelerated)
- Organized and readable code

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Optimization

- Semantic HTML5 structure
- Proper heading hierarchy
- Meta tags for social sharing
- Accessibility attributes
- Mobile-friendly responsive design

## Accessibility Features

- Keyboard navigation support
- Focus indicators for interactive elements
- ARIA labels where applicable
- Color contrast compliance
- Readable font sizes
- Semantic HTML

## Future Enhancements

Potential features to add:
- Blog section with articles
- Multi-language support
- Dark mode toggle
- Advanced portfolio filtering
- Client testimonials carousel
- Chat/live support widget
- Analytics integration
- CMS integration

## Contact Information

**Jubilant Designs**
- Email: [jubilanthomeschooler@gmail.com](mailto:jubilanthomeschooler@gmail.com)
- Phone: +233 (0) 303-934948
- Location: Accra, Ghana

## License

MIT License - feel free to use this template for your projects.

## Support

For issues, suggestions, or questions, please contact:
- Email: jubilanthomeschooler@gmail.com
- GitHub Issues: [Project Issues](https://github.com/joshua-danquah-website/-Jubilant-Homeschooler/issues)

---

**Version**: 1.0.0  
**Last Updated**: February 2026  
**Developed by**: Joshua Danquah