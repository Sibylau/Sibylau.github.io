# Jie Liu — Personal Website

Source for my personal academic website, live at **[sibylau.github.io](https://sibylau.github.io)**.

I'm a Ph.D. candidate in the [Computer Systems Laboratory (CSL)](https://www.csl.cornell.edu/) at
[Cornell University](https://www.cornell.edu/), advised by Prof.
[Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/). My research is on **domain-specific languages
and compilers**, with a focus on efficient **sparse data processing** on heterogeneous hardware such
as GPUs and FPGAs.

## Built with

This website is built on [**al-folio**](https://github.com/alshedivat/al-folio) — a clean, responsive
[Jekyll](https://jekyllrb.com/) theme for academics, created by
[Maruan Al-Shedivat](https://github.com/alshedivat) and its
[contributors](https://github.com/alshedivat/al-folio/graphs/contributors), and released under the
MIT License. All theme documentation (customization, FAQ, deployment options) lives in the
[upstream repository](https://github.com/alshedivat/al-folio).

- **Theme:** [al-folio](https://github.com/alshedivat/al-folio) (MIT)
- **Generator:** [Jekyll](https://jekyllrb.com/)
- **Hosting:** [GitHub Pages](https://pages.github.com/)

## Running locally

### With Docker (recommended)

```bash
docker compose up
```

Then open <http://localhost:8080>. The site live-reloads as you edit.

### Natively (Ruby)

Requires Ruby 3.2.x and [Bundler](https://bundler.io/).

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deployment

Every push to `master` triggers the [`Deploy site`](.github/workflows/deploy.yml) GitHub Actions
workflow, which builds the site and publishes it to the `gh-pages` branch. GitHub Pages serves that
branch (Settings → Pages → *Deploy from a branch* → `gh-pages` / `root`) at
[sibylau.github.io](https://sibylau.github.io).

## Repository layout

| Path | Contents |
| --- | --- |
| `_pages/` | Top-level pages (about, CV, projects, …) |
| `_posts/` | Blog posts |
| `_projects/` | Project entries |
| `_news/` | News / announcements |
| `_bibliography/papers.bib` | Publications |
| `_data/` | Structured data (CV, socials, …) |
| `assets/` | Images, PDFs, styles, scripts |
| `_config.yml` | Site configuration |

## License

The al-folio theme and this site's source are released under the [MIT License](LICENSE)
(© 2022 Maruan Al-Shedivat). Website **content** — text, images, and publications — © Jie Liu.
