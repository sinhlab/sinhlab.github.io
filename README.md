# Sinthavanh Chanthavong GitHub Pages Site

Quarto-based academic profile site for GitHub Pages.

## Edit

Edit the source file:

```text
index.qmd
```

The generated website file is:

```text
index.html
```

## Render Locally

```powershell
quarto render
```

Then open `index.html` in a browser.

## Publish on GitHub Pages

1. Create a GitHub repository, for example `sinhlab.github.io`.
2. Push this folder to GitHub.
3. In GitHub, open `Settings > Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Set branch to `main` and folder to `/root`.
6. Save.

For a user site named `sinhlab.github.io`, the public URL will be:

```text
https://sinhlab.github.io
```

## Main Files

- `_quarto.yml` - Quarto website configuration
- `index.qmd` - editable page content
- `styles.css` - custom visual style
- `index.html` - rendered GitHub Pages output
- `assets/profile-photo.jpg` - profile portrait
- `.nojekyll` - disables Jekyll processing on GitHub Pages
