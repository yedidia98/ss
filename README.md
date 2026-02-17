# MoonPac landing page

This repository is now configured to auto-deploy to **GitHub Pages**.

## Live deployment setup (one-time)

1. Push this branch to GitHub.
2. Open **Settings → Pages** in your repository.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Merge to `main` (or push to `work` if you keep that as your live branch).

After the workflow runs, your live URL will appear in:
- Actions run summary (`deploy-pages` job), and
- Settings → Pages.

Typical URL format:
- `https://<your-username>.github.io/<repo-name>/`

## Notes

- The logo link points to `index.html` so it works in subpath deployments (like GitHub Pages project sites).
