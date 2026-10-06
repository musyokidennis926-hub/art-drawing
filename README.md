# Artistry Studio – Art Drawing Business Website

A modern, elegant, fully responsive website for an art drawing / fine art business. Perfect for showcasing portfolio, offering commissions, and collecting client inquiries.

## Features

- **Hero section** with call-to-action
- **About** the artist with stats
- **Portfolio gallery** with category filters (Portraits, Pets, Landscapes, Other)
- **Services** (Commissions, Originals, Prints)
- **Commission process** steps
- **Contact form** (demo – easy to connect to Formspree / Netlify Forms / EmailJS)
- Fully responsive (mobile, tablet, desktop)
- Smooth scrolling navigation
- Mobile hamburger menu
- Dark elegant artistic theme

## Folder Structure

```
art-drawing-website/
├── index.html          # Main page
├── css/
│   └── styles.css      # All styles
├── js/
│   └── script.js       # Interactivity
├── assets/
│   └── images/         # Put your artwork images here
└── README.md
```

## How to Customize

1. **Replace placeholder images**  
   Open `index.html` and replace the `.image-placeholder` divs with real `<img>` tags pointing to your files in `assets/images/`.

2. **Update text**  
   Change the artist name, descriptions, email, social links, stats, etc. directly in `index.html`.

3. **Contact form**  
   The form currently shows an alert. To make it real:
   - **Formspree**: Change `<form>` action to `https://formspree.io/f/your-id` and method="POST"
   - **Netlify Forms**: Add `netlify` attribute to the form tag
   - **EmailJS**: Integrate via their JS SDK

4. **Colors**  
   Edit CSS variables at the top of `css/styles.css` (`--color-accent`, etc.).

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `art-drawing-website` or `yourusername.github.io`).
2. Upload all files from this folder (or push via Git).
3. Go to **Settings → Pages**.
4. Under "Source", select the branch (usually `main`) and folder `/ (root)`.
5. Save. Your site will be live at `https://yourusername.github.io/repository-name/`.

### Quick Git commands

```bash
git init
git add .
git commit -m "Initial commit – Artistry Studio website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Local Preview

Simply open `index.html` in any modern browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node (if you have npx)
npx serve
```

Then visit `http://localhost:8000`.

## License

Free to use and modify for your personal or commercial art business. Attribution appreciated but not required.

---

Made with care for artists who draw.
