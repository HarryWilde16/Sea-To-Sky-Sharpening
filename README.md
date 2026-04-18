# Sea to Sky Sharpening Services - Website

A professional, modern website for Sea to Sky Sharpening Services in Pemberton & Whistler, built with clean HTML, CSS, and vanilla JavaScript.

## Project Structure

```
Sea To Sky Sharpening/
├── index.html                  # Home page
├── services.html              # Services & pricing page
├── for-sale.html              # Products for sale page
├── about.html                 # About the business
├── blog.html                  # Blog & tips
├── contact.html               # Contact form
├── thank-you.html             # Form submission confirmation
├── css/
│   └── styles.css             # Main stylesheet
├── js/
│   └── scripts.js             # JavaScript functionality
├── assets/
│   ├── branding/              # Logo files
│   └── images/                # Product images
├── robots.txt                 # SEO robots file
├── sitemap.xml                # XML sitemap
└── README.md                  # This file
```

## Features

### Pages Included
- **Home (index.html)**: Eye-catching hero section with service overview and featured benefits
- **Services (services.html)**: Detailed service offerings with transparent pricing and service process
- **For Sale (for-sale.html)**: Professional product grid showcasing premium sharpened blades and tools
- **About (about.html)**: Company story, values, and commitment
- **Blog (blog.html)**: Blade care tips, maintenance guides, and sharpening advice
- **Contact (contact.html)**: Multi-channel contact form with FAQ and service area details
- **Thank You (thank-you.html)**: Post-submission confirmation page

### Design Features
- **Responsive Design**: Fully mobile-optimized with clean, modern layout
- **Professional Color Scheme**: Dark steel theme with accent red (#e74c3c) for premium feel
- **Smooth Navigation**: Sticky navbar with mobile hamburger menu
- **Fast Load Times**: Lightweight CSS and vanilla JavaScript (no frameworks)
- **Accessibility**: WCAG guidelines, semantic HTML, skip links
- **SEO Optimized**: Meta tags, sitemap, robots.txt included
- **Interactive Elements**: Form validation, smooth scrolling, hover effects

### Service Features
- Kitchen knife sharpening (Western & Japanese)
- Garden tool sharpening (pruners, shears, loppers)
- Specialty blade sharpening (hunting knives, axes, scissors)
- Mobile service options
- Same-day turnaround availability
- For-sale products with professional product grid

## How to Deploy to GitHub Pages

### Step 1: Initialize Git Repository
```bash
cd "C:\Users\harry\OneDrive\Documents\VS Code Projects\Sea To Sky Sharpening"
git init
git add .
git commit -m "Initial commit: Sea to Sky Sharpening website"
```

### Step 2: Create GitHub Repository
1. Go to https://github.com/new
2. Create a new repository: `sea-to-sky-sharpening` (or your preferred name)
3. Choose "Public" for GitHub Pages to work
4. Don't initialize with README (we already have one)

### Step 3: Deploy
```bash
git remote add origin https://github.com/YOUR_USERNAME/sea-to-sky-sharpening.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your GitHub repository Settings
2. Scroll to "GitHub Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch
5. Click Save
6. Your site will be live at `https://YOUR_USERNAME.github.io/sea-to-sky-sharpening/`

### Step 5: Custom Domain (Optional)
1. Register a domain (GoDaddy, Namecheap, etc.)
2. In GitHub Settings > Pages, add your custom domain
3. Add DNS records pointing to GitHub Pages
4. Add a CNAME file to the repository with your domain name

## File Customization Guide

### Update Contact Information
Edit these files to change phone number, email, Instagram handle:
- **All files**: Search and replace `+16049021981` with new phone
- **All files**: Search and replace `seatoskysharpening@gmail.com` with new email
- **All files**: Search and replace `@seatoskysharpening` with new Instagram handle

### Update Colors
Edit `css/styles.css` root variables:
```css
:root {
    --primary: #0d0d0d;          /* Dark background */
    --accent: #e74c3c;           /* Red accent (change here) */
    --silver: #d4af37;           /* Gold highlight */
    /* ... other colors ... */
}
```

### Update Pricing
Edit `services.html` pricing table to reflect current rates.

### Update Products
Edit `for-sale.html` product cards:
- Replace emoji placeholders with actual product images
- Update product names, descriptions, and prices
- Add real product images to `assets/images/`

## Performance Tips

- **Images**: Add actual product images to `assets/images/` folder
- **Meta Tags**: Update all meta descriptions with your specific details
- **Analytics**: Add Google Analytics ID when ready (uncomment in HTML head)
- **Forms**: For production, integrate with Formspree or email service

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Maintenance

### Regular Updates
- Update blog posts in `blog.html`
- Update product listings in `for-sale.html`
- Keep pricing current in `services.html`
- Monitor contact form submissions

### SEO
- Update `sitemap.xml` with new pages
- Maintain `robots.txt` for search engines
- Keep meta descriptions fresh and relevant

## License

© 2024 Sea to Sky Sharpening Services. All rights reserved.

## Support

For questions about the website setup or customization, contact through the site.

---

**Last Updated:** April 15, 2024  
**Version:** 1.0
