# 10-718: Machine Learning in Practice — course site

Source for the course website at <https://dssg.github.io/MLinPractice/>, built
with [Jekyll](https://jekyllrb.com/) and the
[just-the-docs](https://just-the-docs.com/) theme (used as a remote theme, so
the theme is not vendored into this repo).

## Structure

| File | Page |
| --- | --- |
| `index.md` | Home (logistics, quick links, people) |
| `syllabus.md` | Syllabus overview (parent of the module pages) |
| `module-1-building.md` | Module 1 · Building ML Systems |
| `module-2-beyond-accuracy.md` | Module 2 · Beyond Accuracy |
| `schedule.md` | Schedule |
| `project.md` / `data.md` | Project + data description |
| `grading.md` | Assignments & grading |
| `policies.md` | Policies & resources |

Navigation order and nesting are controlled by the `nav_order`, `parent`, and
`has_children` fields in each page's front matter — not by folder location.

## Deploy (GitHub Pages)

1. Put these files at the root of the `main` branch (or a `docs/` folder).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from
   a branch**, and pick `main` (root or `/docs`).
3. Push. GitHub Pages rebuilds automatically; the site appears at the `url` +
   `baseurl` set in `_config.yml`.

## Preview locally (optional)

```sh
bundle install
bundle exec jekyll serve
# open http://localhost:4000/MLinPractice/
```

