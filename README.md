# ELF Conference

One-page static website for the European Life &amp; Family (ELF) conference — a gathering of European promoters and advocates of Life and Family, built on three pillars: **European**, **Life**, and **Family**.

No build step: `index.html` is a self-contained static page (plain HTML/CSS/JS). The logo lives in `assets/elf-logo.png`.

## Deploying to european-life-family.eu (GitHub Pages)

This repo already includes a `CNAME` file pointing at `european-life-family.eu`.

1. On GitHub: Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
2. At your domain registrar, add DNS records for `european-life-family.eu`:
   - Four `A` records (apex/root) pointing to:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - One `CNAME` record for `www` pointing to `tassilopilar.github.io`
3. Wait for DNS to propagate, then confirm the custom domain in Settings → Pages and enable "Enforce HTTPS".
