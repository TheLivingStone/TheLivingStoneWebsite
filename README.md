# The Living Stone Foundation Website

A modern, responsive website for The Living Stone Foundation - an AI solutions company specializing in intelligent automation, custom LLMs, and AI agent development.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Form Integration**: Contact and career application forms powered by Formspree
- **SEO Optimized**: Proper meta tags, semantic HTML structure
- **Fast Loading**: Optimized images and efficient CSS/JS
- **Accessibility**: WCAG compliant with proper ARIA labels

## 📁 Project Structure

living-stone-website/
├── index.html                          # Homepage
├── about.html                          # About Us page
├── services.html                       # Services page
├── blog.html                          # Blog page
├── careers.html                       # Careers page
├── contact-formspree.html             # Contact form (Formspree)
├── careers-application-formspree.html # Career application form
├── thank-you.html                     # Thank you page
├── styles.css                         # Main stylesheet
├── script.js                          # JavaScript functionality
├── CNAME                              # Custom domain configuration
├── README.md                          # This file
└── assets/
└── images/                        # All website images
├── Living_Stone_LOGO_with_Name-removebg-preview.png
├── LivingStoneFoundationLOGONoBackground.png
├── Zapier.png
├── sendgrid.jpg
├── chainlink-logo-png_seeklogo-396866.png
├── AlchemyLogo.jpg
├── TwilioLogo.png
├── InfuraLogo.png
├── n8nLogo.png
└── [other company logos...]

## 🛠️ Setup Instructions

### 1. Create Project Structure
1. Create a new folder for your website project
2. Create the `assets/images/` subfolder
3. Add all the HTML, CSS, and JS files to the root directory
4. Place all logo images in the `assets/images/` folder

### 2. Configure Forms (Formspree)
The website uses Formspree for form handling:

- **Contact Form**: `https://formspree.io/f/xgvydwbb`
- **Career Application**: `https://formspree.io/f/xrbkjzwb`

After deployment, configure redirect URLs in your Formspree dashboard:
- Redirect URL: `https://thelivingstonefoundation.com/thank-you.html`

### 3. Deploy to GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose your main branch
5. The CNAME file will automatically configure your custom domain

### 4. Configure Custom Domain DNS
Add these DNS records at your domain registrar:

**A Records (for thelivingstonefoundation.com ):**
- Host: @ or thelivingstonefoundation.com
- Points to: 
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

**CNAME Record (for www.thelivingstonefoundation.com):**
- Host: www
- Points to: yourusername.github.io

### 5. Enable HTTPS
After DNS propagation, go to your GitHub repository Settings > Pages and check "Enforce HTTPS".

## 📝 Content Management

### Adding New Blog Posts
Edit `blog.html` and add new blog cards following the existing structure.

### Updating Job Listings
Edit `careers.html` to add, remove, or modify job postings.

### Modifying Services
Update `services.html` to add new services or modify existing ones.

## 🎨 Customization

### Colors
The main brand colors are defined in CSS:
- Primary: #667eea
- Secondary: #764ba2
- Text: #1f2937, #4b5563

### Fonts
The website uses the Inter font family from Google Fonts.

### Images
All images should be optimized for web (WebP format recommended) and placed in `assets/images/`.

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📞 Support

For technical support or questions about the website, contact:
- Email: info@thelivingstonefoundation.com
- Phone: +1 (540) 998-9766

## 📄 License

© 2025 The Living Stone Foundation. All rights reserved.
