# Yazhini Vasanth - Portfolio

A modern, premium, responsive portfolio website built with plain HTML, CSS, and JavaScript. Fully data-driven using `portfolio-data.json`.

## Features

- Dark elegant theme with glassmorphism cards
- Smooth animations (fade-in, hover lift, timeline transitions)
- Fully responsive (desktop, tablet, mobile)
- Dynamic content loaded from JSON
- Lightbox gallery with hover effects
- Video section with local MP4 support
- GitHub Pages compatible

## Structure

```
├── index.html            # Main page (CSS + JS embedded)
├── portfolio-data.json   # All content data
├── images/
│   ├── profile.jpg       # Profile photo
│   ├── timeline/         # Timeline event photos
│   ├── gallery/          # Gallery photos
│   └── video-thumbs/     # Video thumbnails
└── videos/               # MP4 video files
```

## Setup

1. Clone this repository
2. Add your images to the `images/` folders
3. Add your videos to the `videos/` folder
4. Edit `portfolio-data.json` to update content
5. Push to GitHub and enable GitHub Pages

## GitHub Pages

1. Go to **Settings** > **Pages**
2. Set source to `main` branch, root `/`
3. Save — your site will be live at `https://<username>.github.io/yazhiniprofile/`

## Customization

All content is driven by `portfolio-data.json`. Update the JSON file to change:

- Navigation menu items
- Hero section text and profile card
- Timeline events
- Gallery categories and photos
- Video items
- Footer text
