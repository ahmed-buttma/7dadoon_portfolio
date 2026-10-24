# Ahmed Buttma - Personal Portfolio

Multi-CV portfolio website built with **pure HTML & CSS** (no JavaScript, no Bootstrap or any framework).

**Live site:** https://ahmed-buttma.github.io/

## Pages
- `index.html` - Home (choose a CV), About, Skills, Projects, Contact, Footer
- `software.html` - Software Engineer CV
- `dabke.html` - Dabke Trainer CV
- `media.html` - Photographer & Videographer CV (with photo gallery)
- `accounting.html` - Accountant CV
- `style.css` - one stylesheet shared by all pages
- `images/` - project and gallery images

## Tech
- Semantic HTML5 (header, nav, main, section, article, footer)
- CSS variables, Flexbox, Grid, media queries
- CSS-only features: dark/light switch (checkbox + `:has`), rotating text, scroll-reveal and counters (scroll-driven animations), lightbox (`:target`)
- Responsive: phone, tablet, laptop, large screens
- Deployed with GitHub Pages

## Adding videos
Each project page (`project-*.html`, `project-freedom.html`) has a "Video coming soon" box.
- **Video file:** put it in a folder named `videos/` and use
  `<video class="project-video" controls preload="metadata" playsinline><source src="videos/NAME.mp4" type="video/mp4"></video>`.
  It is displayed at its own dimensions (landscape, portrait or square).
- **YouTube:** use `<div class="video-box wide|tall|square"><iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe></div>`.
  Pick `wide` (16:9), `tall` (9:16) or `square` (1:1) to match the video.
