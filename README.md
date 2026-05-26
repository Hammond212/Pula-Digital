# Pula Digital Website

A modern, professional web solutions website built with HTML, CSS, and vanilla JavaScript. Designed for 2026 with a sleek, contemporary aesthetic.

## Project Structure

```
pula-digital/
├── index.html
├── pula-logo.png
├── README.md
└── .gitignore
```

## Features

- **Responsive Design** – Works seamlessly on mobile, tablet, and desktop
- **Dark Mode Support** – Automatically detects system preference
- **Modern Aesthetics** – 2026-ready design with smooth animations
- **Fast Loading** – Minimal dependencies, optimized performance
- **SEO Friendly** – Proper semantic HTML structure
- **Accessible** – WCAG compliant markup

## Sections

1. **Navigation** – Sticky header with smooth scroll navigation
2. **Hero** – Eye-catching introduction with call-to-action
3. **Services** – 6 core service offerings in grid layout
4. **Why Us** – Benefits and unique value propositions
5. **Contact** – Lead generation contact form
6. **Footer** – Professional footer with copyright

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pula-digital.git
cd pula-digital
```

2. Open in your browser:
```bash
# Option 1: Direct open
open index.html

# Option 2: Using Python HTTP server
python -m http.server 8000
# Visit http://localhost:8000
```

### Installation

No build process required! This is a static website with no dependencies.

## Deployment

### Option 1: GitHub Pages (Free)

1. Push to GitHub
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/pula-digital`

### Option 2: Netlify (Free)

1. Connect your GitHub repository
2. Build command: (leave empty)
3. Publish directory: `/`
4. Deploy!

### Option 3: Vercel (Free)

1. Import your GitHub repository
2. Vercel auto-detects it's a static site
3. Click Deploy
4. Done!

### Option 4: Self-Hosted

Upload files to your web server:
- index.html
- pula-logo.png

## Customization

### Colors

Edit the CSS variables in `index.html` under the `:root` section:

```css
:root {
  --accent-primary: #185FA5;
  --accent-secondary: #6133CE;
  --text-primary: #000000;
  --text-secondary: #666666;
}
```

### Content

Edit text directly in the HTML:
- Hero section heading and description
- Service titles and descriptions
- Feature list items
- Contact form labels

### Logo

Replace `pula-logo.png` with your own logo file and update the HTML reference if needed.

### Contact Form

The contact form currently shows an alert. To make it functional:

1. **Using Formspree:**
   - Go to https://formspree.io
   - Create a new form
   - Replace the form action with your Formspree endpoint

2. **Using EmailJS:**
   - Sign up at https://www.emailjs.com
   - Add the EmailJS script and configure it

3. **Using your backend:**
   - Set up a server endpoint
   - Update the form's action attribute

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **No external dependencies** – Only Font Awesome for icons
- **Optimized images** – Keep logo file size minimal
- **CSS-only animations** – Smooth 60fps performance
- **Lighthouse Score** – Target 95+ on all metrics

## Maintenance

### Regular Updates

1. Keep Font Awesome CDN updated
2. Test on new devices/browsers
3. Monitor analytics
4. Update testimonials and case studies

### SEO

Add meta tags in the `<head>` section:
```html
<meta name="description" content="Your meta description">
<meta property="og:title" content="Pula Digital">
<meta property="og:description" content="Your description">
<meta property="og:image" content="url-to-logo">
```

## File Size

- index.html: ~15 KB
- pula-logo.png: ~80 KB (optimize with compression tools if needed)
- Total: ~95 KB

## License

© 2026 Pula Digital. All rights reserved.

## Contact

For questions or support, visit the website or contact through the form.

---

**Built with ❤️ for modern web solutions**
