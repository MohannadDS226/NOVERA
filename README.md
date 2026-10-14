# NOVERA

A cinematic, editorial portfolio experience for Project 208 — NOVERA.

## Image quality

The visible page uses full-resolution, 10-bit AVIF images encoded at a high-quality setting for sharp architectural detail without excessive initial load time. Full-resolution WebP files remain as compatibility and social-preview assets.

## Future scroll-film integration

The site automatically checks for these files:

- `assets/film/novera-experience-desktop.mp4`
- `assets/film/novera-experience-mobile.mp4`

When present, they replace the current scroll-controlled still sequence automatically. No layout rebuild is required.

## Local preview

Serve the repository root with any static server, for example `python3 -m http.server 8080`.

## Deployment

Pushes to `main` deploy through the included GitHub Pages workflow.
