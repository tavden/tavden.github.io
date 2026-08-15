# Deploy Tavden Website

The folder is a dependency-free static site designed for the `tavden.github.io` repository and `tavden.com`.

## Replace current site
From the repository root, replace the old site files with the contents of this `website` directory, then:

```bash
git add -A
git commit -m "Refresh Tavden website to locked 2026 brand standard"
git push
```

GitHub Pages should remain configured to deploy from `main` / root. `CNAME` keeps the custom domain declaration in the repository.

## Verify after deploy
- `https://tavden.com` loads over HTTPS.
- Mobile layout is clean.
- `https://tavden.com/assets/og-tavden-1200x630.png` loads.
- `https://tavden.com/.well-known/security.txt` loads.
- GitHub and social links work.
- Field Suite wording remains **in development / packaging for M5Launcher** until the release is actually live.
