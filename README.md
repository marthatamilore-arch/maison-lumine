# Maison Luminé — GitHub Pages

A lightweight, one-page public site for Maison Luminé, featuring the approved 30-second campaign film, Drop II headwear, the Lagos-born brand story, and verified Instagram/WhatsApp links.

## Public destination

`https://marthatamilore-arch.github.io/maison-lumine/`

## Structure

- `public/` — static, crawler-readable website and local campaign assets.
- `public/media/maison-lumine-promo-30s.mp4` — the finished 30-second video with its original score.
- `.github/workflows/pages.yml` — publishes the `public/` directory through GitHub Pages on pushes to `main`.
- `TODO.md` — approved scope and acceptance criteria.

## Local preview

Run a static server from the project root:

```sh
python3 -m http.server 3000 --directory public
```

Then open `http://localhost:3000/`. No external font, video host, framework or runtime service is required.

Instagram: <https://instagram.com/shoplumine.ng>

WhatsApp: <https://wa.me/2347049333131>
