# Theresa De Gree Portfolio

A static portfolio website built as a simple landing page. It is styled to match the clean, modern structure of the example site.

## Files

- `index.html` — main portfolio page
- `styles.css` — responsive styling

## Open locally

1. Open `index.html` directly in a browser.
2. For a better local development experience, use a local server such as VS Code Live Server or `python3 -m http.server`.

## Deploying live

This site is ready to publish as a static site. You can deploy using one of these options:

### GitHub Pages

1. Create a GitHub repository, for example `theresa-de-gree-portfolio`.
2. Add the GitHub repository as a remote:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. In the GitHub repository settings, enable Pages from the `main` branch and `/` root.
4. GitHub will provide a public URL like `https://<your-username>.github.io/<repo-name>/`.

### Netlify

1. Create a Netlify account.
2. Connect the repository or drag the project folder into the Netlify deploy dashboard.
3. Set the build command to none and the publish directory to `/`.
4. Netlify will provide a public URL once deployed.

## Notes

- This project does not require Node.js or npm.
- Replace placeholder text in `index.html` with your final CV details if needed.
- The project is now initialized as a git repository for easy deployment.
