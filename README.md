# Portfolio-website-HTML-and-CSS

Simple static portfolio website built with plain HTML and CSS.

Quick links

- [index.html](index.html) — Home / entry page
- [about.html](about.html) — About page
- [skills.html](skills.html) — Skills page
- [projects.html](projects.html) — Projects page
- [contact.html](contact.html) — Contact page
- [styles.css](styles.css) — Global stylesheet
- [images/](images/) — Image assets folder

Overview

- Static site: each page is a standalone HTML file that loads [styles.css](styles.css).
- Thumbnail + lightbox pattern uses anchor fragment links (example: the certificate thumbnail targets `#img1`).
- The layout is responsive using CSS grid classes: `.grid-2`, `.grid-3`.

Local preview

- Open [index.html](index.html) in your browser, or use a live-server extension (e.g., Live Server for VS Code) to preview changes live.

Editing notes

- Update global styles in [styles.css](styles.css). CSS variables (e.g. [`--accent`](styles.css)) are defined in the `:root` block.
- Page content and navigation are in the HTML files listed above. Keep relative links to the `images/` folder when adding new images.
- Lightbox thumbnails use a pattern:
  - Thumbnail: `<a href="#img1"><img src="images/certificate.png" class="thumb" /></a>`
  - Lightbox: `<div class="lightbox" id="img1">…</div>`

Adding assets

- Place images under the [images/](images/) folder and reference them with relative paths like `images/your-image.png`.

Contact

- Owner email: <gmoges235@gmail.com> (also used in the contact form action in [contact.html](contact.html)).

License

- Content and code are simple static assets — add a license file if you plan to publish.
