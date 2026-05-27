# Ganjoor — Mirror

An authorized read-only mirror of selected sections of [ganjoor.net](https://ganjoor.net).
Whenever the main server is unavailable, you can still read the poems, prose, and
related content here.

This mirror is a **backup**, not a replacement: please use ganjoor.net for the
canonical, up-to-date content, audio recordings, and community features.

## What's included

This snapshot currently covers **Saadi (سعدی)**:

| Section | Description |
|---|---|
| `saadi/boostan/` | بوستان — Bustan |
| `saadi/golestan/` | گلستان — Golestan |
| `saadi/divan/` | دیوان (غزلیات، قصاید، رباعیات، …) — Divan |
| `saadi/mavaez/` | مواعظ — Mavaez |
| `saadi/hazl/` | هزلیات |
| `saadi/nasr/` | نثرها |
| `saadi/majales5/` | مجالس پنجگانه |

Additional poets will be added over time using the same mirror process.

## How to browse

### Online (GitHub Pages)

Start at [`Saadi`](https://dshahmirzad.github.io/Ganjoor/) 

### Locally — via a tiny HTTP server (recommended)

From the repository root:

```bash
python3 -m http.server 8080
```

Then visit <http://localhost:8080/saadi/>.

### Locally — by opening files directly

Open `saadi/divan.html` (or any other page) in your browser. All asset and
page links are relative and `.html`-suffixed, so file:// browsing works for
poems and navigation; some live features that depend on ganjoor.net's API
(search box, similar-poet recommendations) will be inert.

## What's NOT mirrored

- Audio recordings of poems (hosted on ganjoor's audio servers)
- Live search and recommendation APIs
- User comments and contributions
- Images embedded by community contributors

## Credits

All poetry, prose, and editorial content is sourced from
[ganjoor.net](https://ganjoor.net), the Persian poetry corpus maintained by
Hamid Reza Mohammadi and a large community of volunteer contributors. Please
support and contribute to the original project.

This mirror exists purely to keep the content reachable during outages.
