# olivier-nourry

Personal academic website of Olivier Nourry, served by GitHub Pages at
<https://onourry.github.io/olivier-nourry/>.

It is a small, theme-free Jekyll site. All content lives in YAML files under `_data/`,
so updating the site normally means editing one of these and pushing to `main`:

| File | What it holds |
| --- | --- |
| `_data/profile.yml` | Name, affiliation, profile links (hero icons), research interests |
| `_data/news.yml` | News items on the home page (newest first) |
| `_data/publications.yml` | Publications (field reference at the top of the file) |
| `_data/pubtypes.yml` | Order and headings of the publication groups |
| `_data/teaching.yml` | Courses |
| `_data/service.yml` | Program committees and reviewing |
| `_data/cv.yml` | Positions, education, grants |
| `_data/talks.yml` | Talks |

The About text is in `index.html`; styles are in `assets/style.css`.
Put PDFs or slides under `files/` and reference them from a publication with
`pdf: /files/your-paper.pdf`.

## Local preview

```sh
bundle install
bundle exec jekyll serve
# open http://localhost:4000/olivier-nourry/
```
