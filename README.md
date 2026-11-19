# Warhammer Archives

A public, mobile-friendly Warhammer 40,000 **fan wiki**—with **owner-controlled editing**. Live site: **https://rednecko.github.io/warhammer-archives/**

## Explore

- **Sons of Sigismund** — founding, officers, ten Sword Brethren, doctrines, heraldry, rites, relic register, *The Righteous Crusader*, and live campaign chronicle.
- **Future volumes** — Thousand Sons, Death Guard, Imperial Guard, Chaos Knights, Raptors and Blood Angels.

The wiki is intentionally a **living record**. Approved decisions are distinguished from provisional ship layouts and names still undecided. Game results aren't written until games happen.

## How it works

- Markdown lives in `docs/`. Add pages as `docs/path/page.md`.
- The navigation menu lives in `mkdocs.yml`.
- Styles live in `docs/assets/stylesheets/extra.css`.
- The header emblem lives in `docs/assets/images/templar-sigil.svg`.
- The site is automatically published by `.github/workflows/deploy.yml` whenever `main` changes.

### Editing

Only repository collaborators with GitHub write permissions can change the original files. Everyone else can **view the website**. You can edit Markdown through GitHub in a browser; no local Git or VS Code installation is required.

### Publishing

In **Settings → Pages**, set the deployment source to **GitHub Actions**. The workflow builds via `mkdocs build --strict` and deploys to GitHub Pages. Check **Actions → Publish Warhammer Wiki** after commits.

## Lore and continuity

- New decisions override contradictory older drafts.
- Earlier 60 permanent + 100 rotating strength was a **future planning idea**, not the founding roster.
- The founding order has **ten Sword Brethren** and two initially attached Crusader Squads.
- The Marshal's regional Ork victory was **pre-commission**.
- The Sons of Sigismund have **zero recorded post-founding battles** until one is played.

Source and editorial notes are in `docs/sons-of-sigismund/archive/`.

*Unofficial fan project; not endorsed by Games Workshop.*
