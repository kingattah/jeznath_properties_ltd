# Jeznath Properties Ltd - Real Estate Website

A professional real estate website for Jeznath Properties Ltd, a Nigerian real estate company specializing in quality properties, secure lands, and modern homes.

## Features

- **Responsive Design**: Fully responsive website that works on all devices (mobile, tablet, desktop)
- **Modern UI**: Professional design with black, red, and white color scheme matching the company logo
- **Multiple Pages**:
  - Home Page
  - About Us
  - Services
  - Contact Us

## Technologies Used

- HTML5
- CSS3 (with modern animations and effects)
- JavaScript (for interactivity and form handling)
- Font Awesome Icons

## File Structure

```
Jeznath Properties Ltd/
├── index.html          # Home page
├── about.html          # About Us page
├── services.html       # Services page
├── contact.html        # Contact Us page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── logo.jpeg       # Company logo
│   ├── img1.jpeg       # Hero image
│   ├── img2.jpeg       # About section image
│   ├── img3.jpeg       # Services section image
│   ├── img4.jpg        # CTA section background
│   ├── img5.jpg        # Contact section image
│   └── img6.jpg        # About preview image
└── README.md           # This file
```

## GitHub Pages

- **Repo URL**: https://kingattah.github.io/jeznath_properties_ltd/
- **Custom domain**: https://jeznathproperties.ng/ (see below if it doesn’t load)

Deployment is done via GitHub Actions on every push to `master`. To use it:

1. In the repo: **Settings → Pages**
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. Push to `master`; the workflow will deploy the site

**If the custom domain (jeznathproperties.ng) doesn’t work:**

1. **Settings → Pages → Custom domain**: enter `jeznathproperties.ng` and Save
2. **DNS** (at your domain registrar): add a **CNAME** record:  
   `jeznathproperties.ng` → `kingattah.github.io`  
   (or use GitHub’s A records if your host supports them)
3. Wait for DNS to propagate (up to 48 hours), then enable **Enforce HTTPS**

## Setup

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process required - it's a static website

## Contact Information

- **Company**: Jeznath Properties Ltd
- **Phone/WhatsApp**: +234 7019955999
- **Email**: info@jeznathproperties.com
- **Address**: 17 Toyin Street, Ikeja, Lagos, Nigeria

## License

© 2026 Jeznath Properties Ltd. All rights reserved.
