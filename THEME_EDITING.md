# Theme Editing

This site uses `themes/chicago7` as the upstream Chicago 7 theme.

For local customization, edit the project-root override folders instead of
editing files inside `themes/chicago7`:

- `layouts/` overrides `themes/chicago7/layouts/`
- `assets/scss/` overrides `themes/chicago7/assets/scss/`
- `static/icons/` overrides `themes/chicago7/static/icons/`
- `static/fonts/` overrides `themes/chicago7/static/fonts/`

Hugo loads project-root files before theme files, so changes here are easier to
track in this blog repository and will survive theme updates.
