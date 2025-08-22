# Frontend Mentor - Social links profile solution

This is my solution to the [Social links profile challenge](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). A compact profile card with avatar, location, short bio, and a vertical list of social links featuring hover/focus states and accessible markup.

![Preview](./preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Deployment](#deployment)

## Overview

### The challenge

Users should be able to:

- See hover and keyboard focus states on all interactive links
- View the component comfortably on mobile and desktop viewports

### Links

- Solution URL: <!-- Add Frontend Mentor solution URL -->
- Live Site URL: <!-- Add GitHub Pages URL once deployed -->

## My process

### Built with

- Semantic HTML5
- Modern CSS (flexbox, custom font, hover/focus states)
- Mobile-first thinking (single-column layout)
- Minimal footprint: no frameworks

### What I learned

- Using a single flex column container with centered alignment keeps the card layout simple while allowing an independently positioned footer.
- Replacing large top margins with layout techniques (flex centering or fixed positioning for attribution) creates true vertical centering.
- Explicit `:focus-visible` states greatly improve keyboard accessibility for link groups.

### Continued development

- Add prefers-reduced-motion handling for any future animations.
- Introduce CSS variables for color tokens and spacing scale.
- Add a dark/light toggle or theme expansion.

### Useful resources

- MDN: [Flexbox guide](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)
- MDN: [:focus-visible](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible)
- GitHub Docs: [GitHub Pages deployment](https://docs.github.com/en/pages)

## Author

- GitHub: [@Ankankun](https://github.com/Ankankun)
- Frontend Mentor: [@Ankankun](https://www.frontendmentor.io/profile/Ankankun)

## Deployment

Deploy to GitHub Pages in the existing repository `Social-Links-Profile`.

From the project root (contains `index.html`):

```powershell
cd "c:\Users\User\VS Workspace\projects\social-links-profile-main"

# If not already a git repo (skip if .git exists)
git init
git branch -M main
git add .
git commit -m "Initial commit"

# Add remote (skip if already added)
git remote add origin https://github.com/Ankankun/Social-Links-Profile.git

# Push code
git push -u origin main
```

Enable Pages:

1. GitHub repo → Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / Folder: `/ (root)` → Save
4. Wait 1–3 minutes, then visit: `https://ankankun.github.io/Social-Links-Profile/`

Updating after changes:

```powershell
git add .
git commit -m "Update styles/content"
git push
```

If push is rejected because remote has an initial commit you didn’t pull:

```powershell
git fetch origin
git pull --allow-unrelated-histories origin main
git add .
git commit -m "Merge remote"
git push
```
