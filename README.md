# Layer personal site

This is a personal site that can be deployed directly with GitHub Pages.

## Local Preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish To GitHub Pages

1. Push the code to the `llllayer.github.io` GitHub repository.
2. Open `Settings > Pages` in the repository.
3. Choose `Deploy from a branch`, select `main`, and use the `/root` folder.
4. Save the settings, wait for deployment, then visit the GitHub Pages URL for the repository.

## Customization

- `index.html`: update the name, intro, projects, articles, and contact links.
- `styles.css`: adjust colors, layout, and responsive behavior.
- `script.js`: add small interactions.
