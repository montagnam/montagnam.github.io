# Marco Montagna, MD - Personal Website

This repository powers the GitHub Pages site at:

- https://montagnam.github.io

## How this website works

This is a Jekyll site hosted by GitHub Pages.

1. You edit files in this repository.
2. You commit and push to the `main` branch.
3. GitHub Pages automatically rebuilds and publishes the website.

For a user site (`username.github.io`), the published URL is based on the repository name.

## Main files

- `_config.yml`: site metadata (title, description, author, theme).
- `index.md`: single-page homepage content with all sections.
- `assets/main.scss`: custom styling (menu, layout, colors, responsive behavior).

## Edit content quickly

Most updates happen in `index.md`:

- Edit biography text in `About`.
- Add and update items in `Publications`, `Teaching`, and `Talks`.
- Keep links in `Contact` up to date.

The top menu uses section anchors (for example `#about`, `#publications`) to jump within the page.

## Publish changes

From the repository folder:

```bash
git add .
git commit -m "Update website content"
git push origin main
```

Then check:

1. Repository `Settings` -> `Pages` to confirm source is `main`.
2. Repository `Actions` (or Pages deployment status) for build success.
3. Live site behavior at https://montagnam.github.io.

## Next personalization steps

1. Replace placeholder publication entries with real citations.
2. Add a profile photo under `assets` and reference it in `index.md`.
3. Add a downloadable CV PDF under `assets` and link it in the hero/contact section.
4. Update the `Last updated` date at the end of `index.md`.
