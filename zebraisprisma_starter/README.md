# Starter static portfolio - Zebra Is Prisma (example)

Quick starter to try Netlify + GitHub deploy without connecting your custom domain yet.

## What is included
- index.html, about.html, portfolio.html, video.html, contact.html
- style.css
- assets/ (empty) - put your images here (photo1.jpg, photo2.jpg, ...)
- _redirects (example file for Netlify)

## Quick local preview
1. Put the folder on your computer (or edit directly on GitHub).
2. To preview locally, in the folder run:
   ```
   python -m http.server 8000
   ```
   Then open http://localhost:8000 in your browser.

## Deploy with GitHub -> Netlify (recommended)
1. Create a new GitHub repository (public) named `zebraisprisma` or similar.
2. Upload these files (use "Add file" -> "Upload files" in the GitHub web UI).
3. In Netlify, choose **New site from Git**, connect GitHub, select the repository.
   - Build command: leave blank
   - Publish directory: leave blank (Netlify will publish the repo root)
4. Deploy — Netlify will give you a `sitename.netlify.app` URL.
5. To update site: edit files on GitHub and push; Netlify will auto-deploy.

## Using your own domain later
- When ready, add your domain in Netlify's Domain settings and follow its DNS instructions.
- For now you can test the live netlify.app URL and iterate.

## Notes
- For images: optimize for web (compress / use .webp if possible).
- For video: prefer embedding YouTube/Vimeo for performance.
