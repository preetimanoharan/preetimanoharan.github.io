# Preeti Manoharan Portfolio

A Hugo-based personal website for Preeti Manoharan, built with the `hugo-profile` theme.

This repository contains a static portfolio and resume site with career experience, education, skills, and multilingual support.

## Project structure

- `hugo.yaml` - Hugo configuration, site parameters, and homepage sections
- `themes/hugo-profile` - Hugo theme installed as a Git submodule
- `content/` - page and blog content
- `static/` - static assets such as images and documents
- `i18n/` - translation files for supported languages
- `layouts/` - custom templates and theme overrides

## Requirements

- Hugo 0.87.0 or higher
- Git (to initialize and update the theme submodule)

## Local development

1. Initialize the theme submodule:

   ```bash
   git submodule update --init --recursive
   ```

2. Start the Hugo server:

   ```bash
   hugo server
   ```

3. Open the local preview in your browser at:

   ```text
   http://localhost:1313/
   ```

## Customization

- Edit `hugo.yaml` to update site title, hero content, about section, experience, education, skills, and navigation settings.
- Add or edit site content in `content/`.
- Replace site images under `static/images/`.
- Use `i18n/` for translation support and add new languages if needed.

## Deployment

This site is configured with `baseURL: "https://preetimanoharan.github.io/"` in `hugo.yaml`.

For deployment, build the static site with:

```bash
hugo
```

Then publish the generated `public/` directory to your hosting provider.

## Notes

- The theme is managed as a Git submodule in `themes/hugo-profile`.
- If you change the theme or update the submodule, run the `git submodule update --recursive` command again.
