# derpystudios.com

Static site for Derpy Studios (Derpy Solutions LLC), served by GitHub Pages.

## Publish

1. On GitHub, create the organization (e.g. `derpystudios`) and a public repo
   named `<org>.github.io` (e.g. `derpystudios.github.io`).
2. Push this folder to its `main` branch.
3. Repo **Settings → Pages**: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
   The `CNAME` file sets the custom domain to `derpystudios.com`.
4. At your DNS provider for derpystudios.com:
   - Four `A` records on `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - (optional IPv6) `AAAA` on `@`: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
   - `CNAME` on `www` → `<org>.github.io`
5. Once the DNS check passes in Settings → Pages, tick **Enforce HTTPS**.
6. Recommended: verify the domain under the org's **Settings → Pages** so nobody else can claim it.

## Files

- `index.html`, `assets/site.css`: the page.
- `assets/img/derpy-mark*.png`: the logo (photo cutout with colour grade, outline and glow).
- `assets/img/derpy-plant-original.png`: the plain cutout, no filters.
- `assets/img/derpy-badge*.png`: round badge for avatars and favicons.
- `assets/media/`: Die Fighter screenshots and clips, copied from the Steam refresh kit.
