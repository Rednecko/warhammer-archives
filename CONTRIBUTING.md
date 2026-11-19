# Editing Warhammer Archives

This wiki is publicly readable, but the original repository is editable only by authorized collaborators.

## Publishing process

1. Decide an entry's status: **established, working, open, superseded** or **recorded**.
2. Start from an appropriate file in `templates/` or edit an existing file in `docs/`.
3. Keep narrative lore separate from real tabletop results.
4. Check all links are relative to the Markdown source file, using `../` where needed.
5. Add new public Markdown pages to `mkdocs.yml` navigation.
6. Commit or open a pull request. A commit to `main` automatically rebuilds GitHub Pages.
7. Verify **Actions → Publish Warhammer Wiki** succeeds.

## Lore priority

The latest explicitly confirmed decision beats conflicting older drafts. The private master Google Doc and development archives remain source material; any contradictory older details are editorial context, not automatically active lore.

### What must not happen

- Do not invent a victory, loss, casualty, relic origin or character name simply to fill a page.
- Do not promote working ship capacity estimates into the starting tabletop roster.
- Do not merge the founder's pre-commission Ork campaign with the new household's unplayed campaign.
- Do not confuse a house oath, the Trial of Swords and a relic-specific vow.
- Do not call the Sons of Sigismund an independent successor Chapter.

## Website configuration

`docs/` — page content  
`mkdocs.yml` — navigation and Material theme settings  
`docs/assets/stylesheets/extra.css` — colors, typography and layouts  
`docs/assets/images/` — original site assets  
`.github/workflows/deploy.yml` — automatic GitHub Pages publishing

The site is a fan archive, not official Games Workshop material.
