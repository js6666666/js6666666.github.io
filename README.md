# Jiang Shu — academic website

Personal academic website for Jiang Shu, a biostatistics PhD student at Duke
University.

The site uses plain HTML, CSS, and SVG, with no build dependencies, runtime
JavaScript, external fonts, or analytics.

## Local preview

Open `index.html` directly in a browser, or serve the repository locally:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Visit <http://127.0.0.1:8765>. Stop the server with Ctrl+C.

## Structure

- `index.html`: biography, research interests, selected publications, and news.
- `publications.html`: selected publications with links to published records.
- `projects.html`: research descriptions and links to public materials.
- `cv.html`: academic background and selected publications.
- `contact.html`: academic email and public profiles.
- `assets/site.css`: shared responsive and print styles.
- `assets/research-illustration.svg`: conceptual illustration; no patient data.
- `assets/favicon.svg`: site icon.

Navigation and the footer are shared across the five static pages. Update each
page when changing either, keeping one `aria-current="page"` navigation link on
each page. Publication entries also appear on the home page and CV.
