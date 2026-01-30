# World2Bold Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Project Structure

```
world2bold-portfolio/
├── index.html                # Home page
├── about.html                # About page
├── services.html             # Services page
├── projects.html             # Portfolio / Projects
├── contact.html              # Contact page
├── privacy-policy.html       # Privacy Policy (AdSense ready)
├── 404.html                  # Custom 404 page
├── favicon.ico               # Website favicon
├── netlify.toml              # Netlify configuration
│
├── assets/
│   ├── css/
│   │   └── styles.css        # Main stylesheet
│   │
│   ├── js/
│   │   └── main.js           # JavaScript functionality
│   │
│   └── images/
│       ├── hero.svg          # Hero illustration
│       ├── about.svg         # About illustration
│       ├── project-1.png     # Project placeholder
│       ├── project-2.png     # Project placeholder
│       └── project-3.png     # Project placeholder
│
└── README.md                 # This file
```

## Features

- **Responsive Design**: Mobile-first approach, works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Contact Form**: Functional contact form for user inquiries
- **Mobile Menu**: Hamburger menu for mobile navigation
- **SEO Ready**: Proper meta tags and semantic HTML
- **AdSense Compatible**: Privacy policy page ready for Google AdSense
- **404 Page**: Custom error page for missing pages
- **Netlify Ready**: Includes netlify.toml configuration

## Getting Started

### Option 1: Local Development

1. Download or clone the project files
2. Open `index.html` in your browser
3. Customize the content with your information

### Option 2: Deploy to Netlify

1. Create a Netlify account at [netlify.com](https://netlify.com)
2. Drag and drop the project folder to deploy
3. Update your domain and configure DNS

## Customization

### Add Your Content

- Replace placeholder text in all HTML files
- Update image files in `assets/images/`
- Modify colors in `assets/css/styles.css`

### Google AdSense

1. Add your AdSense publisher ID in the script tag in `index.html`
2. Update the privacy policy with your AdSense information
3. Follow Google AdSense guidelines for ad placement

### Contact Form

The contact form currently logs data to the browser console. To make it functional:

1. Set up a backend server or use a service like Formspree or EmailJS
2. Update the form submission handler in `assets/js/main.js`

### Images

Replace the placeholder SVG and PNG files with your own:

- `hero.svg` - Hero section illustration
- `about.svg` - About page illustration
- `project-1.png`, `project-2.png`, `project-3.png` - Project images

## Color Scheme

The default color scheme uses:

- **Primary Color**: `#2563eb` (Blue)
- **Secondary Color**: `#1e40af` (Dark Blue)
- **Text Color**: `#333` (Dark Gray)
- **Light Background**: `#f9fafb` (Off-White)

Customize these in `assets/css/styles.css` using the CSS variables in the `:root` selector.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Lightweight and fast-loading
- Optimized CSS and JavaScript
- Minimal dependencies
- Static site (excellent performance)

## Deployment

### Deploy to Netlify (Recommended)

```bash
1. Push your code to GitHub
2. Connect your GitHub repo to Netlify
3. Automatic deployments on push
```

### Deploy to Vercel

```bash
1. Push your code to GitHub
2. Import project on vercel.com
3. Automatic deployments
```

### Deploy to GitHub Pages

```bash
1. Create a GitHub repository
2. Push files to main branch
3. Enable GitHub Pages in settings
```

## SEO Tips

1. Update all meta descriptions
2. Use descriptive image alt text
3. Ensure fast page load times
4. Submit sitemap to Google Search Console
5. Add structured data/schema markup

## Maintenance

- Update contact information regularly
- Keep portfolio projects current
- Monitor and fix broken links
- Update privacy policy as needed
- Test on multiple devices and browsers

## License

This project is open source and available for personal and commercial use.

## Support

For questions or issues, please contact: hello@world2bold.com

---

**Last Updated**: January 30, 2026
