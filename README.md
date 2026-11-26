# Q-Pulse

A single-page interactive website about macroscopic quantum tunnelling and a structural health sensor concept.

Everything is in `index.html`: no build step and no other files. It loads fonts from Google Fonts, so it needs an internet connection.

## Put it on GitHub Pages (free hosting)

1. Create a new public repository on github.com, for example `q-pulse`.
2. Upload `index.html` (and this README) to the repository root.
3. Go to Settings > Pages. Under "Build and deployment", choose Source: Deploy from a branch, Branch: main, folder: / (root), then Save.
4. After about a minute the site is live at `https://<your-username>.github.io/q-pulse/`.

## Get your own domain

1. Buy a domain from a registrar such as Namecheap, Cloudflare or Google Domains (now Squarespace Domains).
2. In the repository, go to Settings > Pages > Custom domain, enter your domain (for example `qpulse.com`), and Save.
3. At your registrar, add DNS records pointing the domain to GitHub Pages:
   - Four `A` records for the apex domain: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - Optionally a `CNAME` record for `www` pointing to `<your-username>.github.io`
4. Wait for DNS to update (usually under an hour), then tick "Enforce HTTPS" in the Pages settings.

GitHub's documentation has the current IP addresses if they change.
