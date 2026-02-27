<!-- 
    Jubilant Designs - Deployment Configuration
    This file contains configuration information for deployment
-->

# Deployment Guide

## Local Development

To run the website locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server -p 8000

# Using npm
npm install
npm start
```

Then open `http://localhost:8000` in your browser.

## Deployment Options

### 1. GitHub Pages
- Push to GitHub repository
- Go to Settings > Pages
- Select main branch as source
- Website will be live at `https://username.github.io/-Jubilant-Homeschooler`

### 2. Netlify
- Connect Git repository
- Build Command: `npm run build` (if applicable)
- Publish Directory: `.` (current directory)
- Deploy

### 3. Vercel
- Connect Git repository
- Framework: Other (static site)
- Deploy

### 4. Traditional Hosting
- Upload files via FTP/SFTP to web server
- Ensure index.html is in root directory
- Access via your domain

## File Structure for Deployment

```
public/
├── index.html
├── styles.css
├── script.js
└── package.json
```

## Environment Variables

Currently, no environment variables are required. All configuration is hardcoded in HTML files.

## SEO Configuration

Update these meta tags in `index.html`:
- `<title>` - Page title (appears in browser tab)
- `<meta name="description">` - Meta description
- `<meta name="keywords">` - Keywords for SEO
- `<meta property="og:...">` - Open Graph tags for social sharing

## Performance Optimization

Already implemented:
- CSS minification ready
- JavaScript optimization
- Image optimization (if adding images)
- Lazy loading
- Smooth animations (GPU-accelerated)

### Further Optimization:
- Use CSS/JS minifiers
- Implement image compression
- Add service worker for offline capability
- Set up CDN for static assets
