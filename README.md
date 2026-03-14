# Duojiang Research Site

This Quarto project is set up for GitHub Pages deployment.

## Local editing

- Edit the `.qmd` files in the project root.
- Update `styles.css` if you want to change the look and feel.
- Run `quarto render` to build the site locally.

## GitHub Pages deployment

1. Put this project in its own GitHub repository.
2. Push the default branch as `main`.
3. In GitHub, open `Settings -> Pages`.
4. Set the source to `GitHub Actions`.
5. Push again or run the `Deploy Research Site` workflow manually.

The workflow in `.github/workflows/deploy.yml` renders the Quarto site and deploys `_site` to GitHub Pages.

## Before publishing publicly

- Replace the placeholder email and profile links in `contact.qmd`.
- Replace the starter text on the research, publications, and projects pages with your actual work.
