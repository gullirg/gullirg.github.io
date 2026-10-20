# gullirg.github.io

Personal academic website of Guglielmo Reggio, served by GitHub Pages at <https://gullirg.github.io>.

The site is built with Jekyll from the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template, a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (© Michael Rose, MIT License; see `LICENSE`).

## Where things live

| What | File |
|---|---|
| Name, bio, profile links (Scholar, ORCID, …) | `_config.yml` → `author` |
| Top navigation | `_data/navigation.yml` |
| Publications and conference contributions | `_data/publications.yml` |
| News on the home page | `_data/news.yml` |
| Pages (Home, Research, Publications, Projects, CV) | `_pages/` |
| Earlier projects | `_portfolio/` |
| PDFs (CV, posters, papers) | `files/` |
| Styles | `_sass/_custom.scss` (loaded last, on top of the theme) |

## Common updates

- **Preprint goes live:** in `_data/publications.yml`, set `doi` on the `reggio2026hexmod` entry, change `venue` to `bioRxiv`, and remove `note`. Add `code` once the GitHub repository is public.
- **New paper or poster:** add an entry at the top of `_data/publications.yml`; `selected: true` also shows it on the home page.
- **New CV:** the CV source is the [gullirg/cv](https://github.com/gullirg/cv) repository. Copy the compiled PDF to `files/Guglielmo_Reggio_CV.pdf`.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
