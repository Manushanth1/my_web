# Deployment Guide

Deploy your portfolio for free using any of these methods.

---

## Option 1: GitHub Pages (Recommended)

### Steps:
1. Create a GitHub repository
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to repository **Settings** → **Pages**
4. Under "Source", select **main** branch → **/ (root)**
5. Click **Save**
6. Your site: `https://YOUR_USERNAME.github.io/YOUR_REPO`

---

## Option 2: Netlify

### Steps:
1. Go to [netlify.com](https://netlify.com)
2. Sign up / Log in with GitHub
3. Click "Add new site" → "Import an existing project"
4. Connect your GitHub repository
5. Build settings: Leave blank (static site)
6. Click "Deploy"
7. Custom domain available in settings

**Drag & Drop Alternative:**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag your project folder
3. Instant deployment!

---

## Option 3: Vercel

### Steps:
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Click "New Project"
4. Import your repository
5. Framework: **Other**
6. Deploy

---

## Contact Form Setup (Optional)

For a working contact form, use one of these free services:

### Formspree
1. Go to [formspree.io](https://formspree.io)
2. Create a form, get your endpoint
3. Update `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_ID" method="POST">
   ```

### Netlify Forms
If using Netlify:
```html
<form name="contact" netlify>
```

---

## Custom Domain

All platforms support custom domains:
1. Purchase domain (Namecheap, Google Domains, etc.)
2. Add CNAME/A records pointing to your host
3. Configure in platform settings

---

## Pre-Deployment Checklist

- [ ] Updated all placeholder text (name, email, links)
- [ ] Added real `resume.pdf`
- [ ] Updated project GitHub/demo links
- [ ] Tested on mobile
- [ ] Tested dark/light mode
- [ ] Checked all links work

---

## Explaining This Website in Interviews

> "I built my portfolio from scratch using HTML, CSS, and JavaScript to demonstrate both my technical skills and my understanding of user experience. I focused on making it fast-loading, responsive, and accessible. The dark/light mode toggle was a fun challenge that taught me about CSS custom properties and localStorage. I deployed it on GitHub Pages to understand the deployment pipeline."

**Key Points:**
- Built without frameworks to show fundamentals
- Responsive design for all devices
- SEO-friendly for discoverability
- Performance-focused (no bloat)
- Continuous improvement (I update projects regularly)
# My_web
