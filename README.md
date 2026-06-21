# Aamir Shehzad — Personal Portfolio Website

A clean, minimal, and premium personal portfolio website built with vanilla HTML, CSS, and JavaScript. Designed for GitHub Pages hosting.

## ✨ Features

- **10 Sections**: Navigation, Hero, About, Skills, Projects, Experience, Testimonials, Blog, Contact, Footer
- **Responsive Design**: Fully responsive across desktop, tablet, and mobile
- **Smooth Animations**: Scroll-triggered reveals, counter animations, floating background orbs
- **Testimonials Carousel**: Touch-enabled slider with auto-rotation
- **Contact Form**: Formspree-ready form with validation
- **SEO Optimized**: Meta tags, Open Graph, semantic HTML
- **Accessibility**: ARIA labels, keyboard navigation, focus management

## 🚀 Getting Started

### Local Development

Simply open `index.html` in your browser — no build step required!

### Deploy to GitHub Pages

1. **Create a GitHub repository**:
   - Go to [github.com/new](https://github.com/new)
   - Name it `yourusername.github.io` (for a personal site) or any name (for a project site)

2. **Push your code**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Click **Save**

4. **Your site is live!** 🎉
   - Personal site: `https://yourusername.github.io`
   - Project site: `https://yourusername.github.io/repo-name`

## 🎨 Customization

### Update Your Information

Open `index.html` and search/replace the placeholder content:

- **Name**: Replace "Alex Morgan" with your name
- **Title/Tagline**: Update the hero section text
- **About**: Edit the bio paragraphs
- **Skills**: Add/remove skill tags in each category
- **Projects**: Update project cards with your own work
- **Experience**: Edit the timeline items
- **Contact**: Update email, location, and social links
- **Images**: Replace files in `assets/images/`

### Contact Form Setup

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form and copy your form ID
3. In `index.html`, update the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
4. In `script.js`, update the form handler to actually submit instead of simulating

### Colors & Fonts

Edit the CSS custom properties at the top of `style.css`:

```css
:root {
  --color-accent: #6366F1;     /* Change accent color */
  --color-bg: #FAFAF9;         /* Change background */
  --color-text: #1C1917;       /* Change text color */
}
```

## 📁 File Structure

```
├── index.html          # Main HTML file
├── style.css           # All styles (design system + components)
├── script.js           # Interactivity & animations
├── README.md           # This file
└── assets/
    └── images/
        ├── profile.png     # Your profile photo
        ├── project-1.png   # Project screenshot
        ├── project-2.png   # Project screenshot
        └── project-3.png   # Project screenshot
```

## 📝 License

Feel free to use this template for your personal portfolio. Attribution appreciated but not required.
