
# 🎨 Modern Art Gallery Website

A sleek, responsive website built for a modern art gallery to showcase stunning artwork collections and provide detailed location information.

## 📌 Overview

This is a fully responsive multi-page website tailored for an art gallery. It includes:
- A responsive **HomePage(index.html)** with highlighted artworks
- A dedicated **Location Page(location.html)** with address and map details

- Desktop, tablet, and mobile-optimized layouts

## 🛠 Technologies Used

- **HTML5**
- **SCSS**
- **CSS3 Grid** & **Flexbox**
- **SCSS Custom Properties (Variables)**
- **Desktop-first Workflow**

## ✨ Key Features

- **Responsive Design**: Adapts beautifully across all devices
- **Interactive Elements**: Smooth hover effects and transitions
- **Modern Grid Layout**: Utilizing advanced CSS grid systems
- **Optimized Images**: Responsive image handling via `<picture>` tag
- **Accessibility**: Semantic HTML structure with high contrast design

🔗 **Live Demo**: [Visit Site](https://art-gallery-website-ui-9gp7.vercel.app/)

## 📁 Folder Structure

```
Modern-Art-Gallery/
├── index.html              # Home page
├── location.html           # Location page
├── scss/
│   ├── styles.scss         # Main SCSS stylesheet
│   └── LocationStyles.scss  # SCSS for the Location page
├── css/
│   └── styles.css          # Compiled CSS from SCSS
└── images/                 # Image assets for the project
    ├── desktop/            # Desktop-sized images
    ├── tablet/             # Tablet-sized images
    └── mobile/             # Mobile-sized images
```

## 🔧 Git Workflow

A structured Git workflow was used for seamless development:

1. **Initialize Repository**
   ```bash
   git init
   ```

2. **Initial Commit**
   ```bash
   git add .
   git commit -m "commit message"
   ```

3. **Branching for Features**
   ```bash
   git branch development
   git checkout -b Hero-section
   git checkout -b Gallery-section
   git checkout -b footer-section
   git checkout -b map-section
   git checkout -b contact-section
   git checkout -b location-footer-section
   git checkout -b Readme
   ```

4. **Development & Merging**
   ```bash
   # Development in respective branches
   # Merge all branches back into development
   git checkout development
   git merge Hero-section Gallery-section footer-section map-section contact-section location-footer-section Readme
   ```

5. **Check Status**
   ```bash
   git status
   ```

6. **Push to Remote**
   ```bash
   git push origin main
   ```


1. **I created a new working directory on my local machine, named starter-code in artGalleryProjectFolder**
   ```bash
   mkdir starter-code
   cd Modern-Art-Gallery && cd starter-code
   ```

2. **Open the Project**
   Simply open `index.html` in your browser via vs code live server extension
   ```

## 📝 License

Licensed under the [MIT License](LICENSE).

## 🙌 Credits

Developed by **SULE MALIK**
