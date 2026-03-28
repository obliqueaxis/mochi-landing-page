# Mochi Landing Page

## Project Overview
Static marketing landing page for **Mochi**, a cute recipe management iOS app.

## Tech Stack
- Single `index.html` file with embedded `<style>` and `<script>`
- No build tools, no frameworks - just open in browser
- Google Fonts: **Nunito** (400, 600, 700, 800)

## Design System

### Colors (CSS custom properties)
- `--cream`: `#F7EFEA` — primary background
- `--tan`: `#EDE0D7` — alternate section background
- `--warm`: `#DABFAC` — footer/accent background
- `--pink`: `#E8998D` — CTA buttons, accents
- `--pink-hover`: `#D9877A` — button hover state
- `--text`: `#4A3728` — body text (warm dark brown)
- `--text-light`: `#7A6558` — secondary text

### Typography
- Font: Nunito (Google Fonts), fallback sans-serif
- Headings: 700-800 weight
- Body: 400-600 weight

### Spacing / Layout
- Max content width: 1100px
- Mobile breakpoint: 768px
- Mobile-first responsive design

## File Structure
```
landing page/
├── CLAUDE.md
├── index.html
└── MochiImages/
    ├── MochiLogoTitleTransparent.png  (logo with app name)
    ├── MochiCharacter.png             (mascot)
    ├── IMG_2841.png                   (home screen)
    ├── IMG_2845.png                   (recipe detail)
    ├── IMG_2843.png                   (meal plan)
    └── ...other images
```

## Conventions
- All styles are embedded in `<style>` within `<head>`
- Minimal JS at bottom of `<body>` (~20 lines, IntersectionObserver for fade-ins)
- Image paths relative: `MochiImages/filename.png`
- Sections alternate between `--cream` and `--tan` backgrounds
- Feature sections use two-column layout on desktop (text + phone screenshot)
