# Gurleen Kaur — Portfolio Website

Personal portfolio site for Gurleen Kaur, MS CS student at NYU Tandon and Software Engineer.

**Live site:** <!-- Add your GitHub Pages / Vercel URL here -->

## Tech Stack
- Pure HTML, CSS, JavaScript — no frameworks, no build step
- Google Fonts (DM Serif Display, DM Mono, DM Sans)
- Scroll-triggered animations via IntersectionObserver

## Structure
```
portfolio/
├── index.html        # Main page
├── css/
│   └── style.css     # All styles
├── js/
│   └── main.js       # Animations, nav, interactions
├── assets/
│   └── gurleen_resume.pdf   # Place your resume PDF here
└── README.md
```

## Setup & Deployment

### Run locally
Just open `index.html` in your browser — no build step needed.

### Deploy on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Deploy on Vercel (recommended — faster)
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **New Project** → import this repo
3. Leave all settings default → click **Deploy**
4. Done — you get a free `yourname.vercel.app` URL instantly

## Customization

### Add your photo
Replace the initials block in `index.html`:
```html
<!-- Find this comment in index.html and replace the div below it -->
<img src="assets/photo.jpg" alt="Gurleen Kaur" class="avatar-img" />
```
Then add to `css/style.css`:
```css
.avatar-img { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }
```

### Add your resume PDF
Place your resume PDF at `assets/gurleen_resume.pdf` — the download button will work automatically.

### Update the "Looking for" tagline
In `index.html`, find the contact section and update:
```html
I'm actively looking for Summer 2026 SDE internships in the US.
```
