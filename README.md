# GHUMMAN Group of Companies Website

A modern, responsive website for GHUMMAN Group of Companies - Leading electromechanical solutions provider in UAE since 2005.

## Features

- **Modern Design**: Inspired by Shift5.io with bold typography and industrial aesthetic
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll animations, hover effects, and transitions
- **Complete Content**: All company information from the PDF included
- **Fast Loading**: Pure HTML/CSS/JS - no frameworks needed

## Sections Included

1. **Hero** - Eye-catching landing with company intro and system status panel
2. **About** - Company history, mission, and statistics
3. **Companies** - All 4 subsidiary companies with descriptions
4. **Services** - 8 main services with interactive accordion
5. **Projects** - Ongoing and completed projects with tabs
6. **Clients** - Major clients list with testimonials
7. **Contact** - Full contact form and company details
8. **Footer** - Quick links, services, and newsletter signup

## How to Upload to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right corner
3. Select **New repository**
4. Name your repository (e.g., `ghumman-website`)
5. Make it **Public**
6. Click **Create repository**

### Step 2: Upload Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all files from this folder:
   - `index.html`
   - `style.css`
   - `script.js`
   - `images/` folder (with all images)
3. Click **Commit changes**

#### Option B: Using Git Command Line

```bash
# Navigate to the website folder
cd ghumman-website

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/ghumman-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (or click "Pages" in the left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/(root)** folder
6. Click **Save**

### Step 4: Access Your Website

- Your website will be live at: `https://YOUR_USERNAME.github.io/ghumman-website/`
- It may take 2-3 minutes to deploy

## File Structure

```
ghumman-website/
├── index.html          # Main HTML file
├── style.css           # All styles
├── script.js           # JavaScript functionality
├── images/             # All images
│   ├── hero-welding.jpg
│   ├── about-workers.jpg
│   ├── contact-team.jpg
│   ├── service-*.jpg
│   └── project-*.jpg
└── README.md           # This file
```

## Contact Information

**GHUMMAN Group of Companies**
- Phone: +971 6 574 1516 / +971 52 934 3434
- Email: ghumnuae@eim.ae / ghummanuae@yahoo.com
- Address: P.O. Box: 294594, Dubai, U.A.E
- Website: www.ghummanuae.com

## License

© 2024 GHUMMAN Group of Companies. All rights reserved.
