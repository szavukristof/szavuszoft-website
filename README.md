# szavuszoft.hu

A **Szavuszoft** marketing weboldala — egyetlen static HTML page.

🔗 **Élesben:** [szavuszoft.hu](https://szavuszoft.hu)

## Mi ez?

A Szavuszoft egy moduláris karbantartás-irányítási és eszközkezelő rendszer
ipari KKV-knak. Ez a repo a marketing weboldal forráskódját tartalmazza
(`szavuszoft.hu`).

Az **alkalmazás** forráskódja külön privát repo-ban van.

## Tech

- Pure HTML + CSS (no build step)
- Inter font (Google Fonts CDN)
- Cloudflare Pages auto-deploy a `main` branch push-ra

## Lokális preview

```
git clone https://github.com/szavukristof/szavuszoft-website.git
cd szavuszoft-website
# Dupla-kattintás az index.html-re vagy:
start index.html  # Windows
```

## Deploy

Minden `main` branch push automatikusan deployolódik a Cloudflare Pages-en
a `szavuszoft.hu` URL-re.

## Kapcsolat

[info@szavuszoft.hu](mailto:info@szavuszoft.hu)

---

© 2026 Szávu Kristóf
