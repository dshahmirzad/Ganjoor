# Ganjoor — Mirror

An authorized read-only mirror of selected sections of [ganjoor.net](https://ganjoor.net).
Whenever the main server is unavailable, you can still read the poems, prose, and
related content here.

This mirror is a **backup**, not a replacement: please use ganjoor.net for the
canonical, up-to-date content, audio recordings, and community features.

## What's included

### Saadi (سعدی)

| Section | Description |
|---|---|
| `saadi/boostan/` | بوستان — Bustan |
| `saadi/golestan/` | گلستان — Golestan |
| `saadi/divan/` | دیوان (غزلیات، قصاید، رباعیات، …) — Divan |
| `saadi/mavaez/` | مواعظ — Mavaez |
| `saadi/hazl/` | هزلیات |
| `saadi/nasr/` | نثرها |
| `saadi/majales5/` | مجالس پنجگانه |

### Hafez (حافظ)

| Section | Description |
|---|---|
| `hafez/ghazal/` | غزلیات — Ghazals (496) |
| `hafez/montasab/` | منتسبات — Attributed poems (119) |
| `hafez/robaee2/` | رباعیات — Rubaiyat |
| `hafez/ghete/` | قطعات — Qit'as |
| `hafez/ghaside/` | قصاید — Qasidas |

### Other high-traffic poets (سخنوران پرمخاطب)

| Poet | Directory | Notes |
|---|---|---|
| Moulavi / Rumi (مولوی) | `moulavi/` | Masnavi, Divan-e Shams, etc. (~6,400 pages) |
| Saeb Tabrizi (صائب) | `saeb/` | Divan-e Saeb (~9,900 pages — largest in the mirror) |
| Attar (عطار) | `attar/` | Manteq al-Tayr, Elahi-nameh, Asrar-nameh, … (~5,200 pages) |
| Ferdousi (فردوسی) | `ferdousi/` | Shahnameh and shorter works (~840 pages) |
| Nezami (نظامی) | `nezami/` | Khamseh (~385 pages) |
| Khayyam (خیام) | `khayyam/` | Rubaiyat and tarane (~450 pages) |
| Iraj Mirza (ایرج میرزا) | `iraj/` | Divan (~246 pages) |
| Shahriar (شهریار) | `shahriar/` | Divan (~200 pages) |

Additional poets will be added over time using the same mirror process.

## How to browse

### Online (GitHub Pages)

- Poets: [`Saadi`](https://dshahmirzad.github.io/Ganjoor/saadi/) · [`Hafez`](https://dshahmirzad.github.io/Ganjoor/hafez/) · [`Moulavi`](https://dshahmirzad.github.io/Ganjoor/moulavi/) · [`Saeb`](https://dshahmirzad.github.io/Ganjoor/saeb/) · [`Attar`](https://dshahmirzad.github.io/Ganjoor/attar/) · [`Ferdousi`](https://dshahmirzad.github.io/Ganjoor/ferdousi/) · [`Nezami`](https://dshahmirzad.github.io/Ganjoor/nezami/) · [`Khayyam`](https://dshahmirzad.github.io/Ganjoor/khayyam/) · [`Iraj`](https://dshahmirzad.github.io/Ganjoor/iraj/) · [`Shahriar`](https://dshahmirzad.github.io/Ganjoor/shahriar/)
- [`Home`](https://dshahmirzad.github.io/Ganjoor/)

### Locally — via a tiny HTTP server (recommended)

From the repository root:

```bash
python3 -m http.server 8080
```

Then visit any poet, e.g. <http://localhost:8080/saadi/> or <http://localhost:8080/moulavi/>.

### Locally — by opening files directly

Open `saadi/divan.html`, `hafez/hafez.html`, `moulavi/masnavi.html`, or any other page in your browser.
All asset and page links are relative and `.html`-suffixed, so file:// browsing
works for poems and navigation; some live features that depend on ganjoor.net's
API (search box, similar-poet recommendations) will be inert.

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
