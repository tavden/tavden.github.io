# Tavden Website — Deployment

This site is deliberately static: HTML + CSS + SVG/PNG assets, with no framework, package manager, tracking script or external font dependency.

## Recommended deployment pattern
1. Create a public or private website repository under the Tavden GitHub organisation.
2. Commit the contents of this `website/` directory at repository root.
3. Deploy with any static host (Cloudflare Pages, GitHub Pages, Netlify, etc.).
4. Set the custom domain to `tavden.com` and redirect `www` to the apex domain.
5. Keep HTTPS forced.
6. Verify `/robots.txt`, `/sitemap.xml`, social preview image and favicon after DNS propagation.

## Before going live
Change no brand copy unless you have a reason. The site is intentionally restrained: no stock imagery, no fake customer logos, no unsupported claims, no trendy animation layer and no dependency that can quietly disappear.
