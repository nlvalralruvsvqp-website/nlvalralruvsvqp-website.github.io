# GitHub Pages Deployment Guide

## Deployment Steps

### 1. Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click "New repository"
3. Name it `geotek-website` (or your preferred name)
4. Make it public
5. Don't initialize with README (we already have files)

### 2. Upload Files

1. Clone the repository locally:

   ```bash
   git clone https://github.com/YOUR_USERNAME/geotek-website.git
   cd geotek-website
   ```

2. Copy all the files from this directory to the repository folder

3. Add and commit files:
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

### 4. Access Your Website

- Your website will be available at: `https://YOUR_USERNAME.github.io/geotek-website`
- It may take a few minutes to deploy

## File Structure

```
├── index.html              # Main homepage
├── biz-kimiz.html          # About Us page
├── amacimiz.html           # Our Mission page
├── presiyometre.html       # Product page
├── galeri.html             # Gallery page
├── politikalar.html        # Policies page
├── iletisime-gecin.html    # Contact page
├── javascript-demo.html    # JavaScript examples
├── README.md              # Project documentation
├── _config.yml            # GitHub Pages config
├── assets/                # Static assets
│   ├── css/               # Stylesheets
│   ├── js/                # JavaScript files
│   ├── images/            # Images and gallery
│   └── webfonts/          # Font files
└── vendor/                # Third-party libraries
    ├── bootstrap/         # Bootstrap CSS/JS
    └── jquery/           # jQuery library
```

## Features

### ✅ Static Website Ready

- All PHP dependencies removed
- Contact form uses Formspree.io for static hosting
- All images and assets properly linked

### ✅ Responsive Design

- Mobile-friendly layout
- Bootstrap framework
- Modern UI components

### ✅ SEO Optimized

- Proper meta tags
- Semantic HTML structure
- Fast loading times

### ✅ Contact Form

- Uses Formspree.io service
- No server-side processing needed
- Form submissions sent to email

## Customization

### Contact Form

To change the contact form destination:

1. Go to [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace `https://formspree.io/f/xpwgkqyz` in the form action with your form URL

### Content Updates

- Edit HTML files directly
- Images are in `assets/images/`
- CSS styles are in `assets/css/`

### Domain Setup (Optional)

1. Buy a custom domain
2. Add CNAME file with your domain name
3. Configure DNS settings to point to GitHub Pages

## Maintenance

- Update content by editing HTML files
- Add new images to `assets/images/galeri/`
- Update contact information in footer sections
- Regular backups recommended

## Support

For technical support or questions about the website setup, contact the development team.

