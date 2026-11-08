# sgalella.github.io

Personal academic website of Santiago Galella, built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll) and deployed to GitHub Pages by `.github/workflows/deploy.yml` (builds into the `gh-pages` branch).

## Editing content

| What | Where |
| --- | --- |
| Bio, photo | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| Publications | `_bibliography/papers.bib` (`selected = {true}` shows it on the home page) |
| News | `_news/*.md` |
| Social links | `_data/socials.yml` |
| Blog posts | `_posts/YYYY-MM-DD-title.md`, then set `nav: true` in `_pages/blog.md` and `latest_posts.enabled: true` in `_pages/about.md` |

## Local preview

```bash
export PATH=/opt/homebrew/opt/ruby/bin:$PATH
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
