# FlangeCrossRef

Breast-pump flange (breast shield) size & parts compatibility directory.
Plain HTML + CSS. No build step, no trackers.

**Live (GitHub Pages):** https://mussman7.github.io/flangecrossref/

**Brand scope:** every pump brand we can source (Motif, Lansinoh, Elvie, Willow, Zomee, Philips Avent, Baby Buddha, Freemie, Eufy, Ameda, Evenflo, Momcozy, and others) — not only Medela and Spectra. Never invent a millimeter list.

## Layout

- `index.html` — hub
- `assets/style.css`
- `guides/measure-and-brand-sizes/` — measure guide + brand ladders
- `brands/` — brand / model parts pages
- `sizes/`, `adapters/`, `parts/` — upcoming IA folders

## Local preview

```bash
python3 -m http.server 8081
```

Links are relative (`…/index.html`), so pages also open from disk.
