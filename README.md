# Online CV

A bilingual personal CV generated as static HTML with Jekyll and hosted on GitHub Pages. The site uses Markdown, one shared Liquid layout, one stylesheet, and static files. It has no JavaScript framework, CSS build step, or runtime service.

## Pages and content

- `/en/` and `/es/` contain the English and Spanish CVs.
- The root page uses the browser language when JavaScript is available and always provides direct language links as a fallback.
- Experience and profile text are Markdown. Education and certifications are kept in `_data/education.json` and rendered by a shared include.
- `assets/` contains the stylesheet, profile image, icons, and downloadable documents.

## Preview locally

Install Ruby and Jekyll, then run this from the repository directory:

```sh
gem install jekyll
jekyll serve
```

Open <http://localhost:4000>. GitHub Pages builds the site when changes are published.
