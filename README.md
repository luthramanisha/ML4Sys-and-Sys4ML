# Third Workshop on ML4Sys and Sys4ML (BTW 2027)

Website of the Third Workshop on ML for Systems and Systems for ML, co-located with [BTW 2027](https://btw2027.gi.de/) at LMU Munich on March 16, 2027.

Live site: https://luthramanisha.github.io/ML4Sys-and-Sys4ML/

## Structure

| Path | Page |
|------|------|
| `index.html` | About (home) |
| `call-for-abstracts/index.html` | Call for Abstracts |
| `program/index.html` | Program |
| `participation/index.html` | Participation |
| `2023/index.html` | Placeholder for the 2023 tutorial workshop (original site no longer online) |
| `2025/` | Frozen copy of the 2025 edition in its original theme (static HTML, not processed by Jekyll) |
| `_layouts/default.html` | Shared navbar and footer |
| `assets/css/main.css` | Styles |

The contact email is set once in `_config.yml` (`contact_email`).

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/ML4Sys-and-Sys4ML/.

## Credits and licenses

- The code in this repository is licensed under the Apache License 2.0 (see `LICENSE`).
- The 2027 design is written from scratch and inspired by the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT License).
- Fonts on the 2027 site (Roboto, Roboto Slab) are loaded from Google Fonts.
- The archived 2025 edition in `2025/` uses the [Minimal theme](https://github.com/pages-themes/minimal) by orderedlist (CC0 1.0, see `2025/assets/LICENSE-theme-minimal.txt`) and the Noto Sans font (SIL Open Font License 1.1, see `2025/assets/fonts/OFL.txt`).
- Speaker photos and the BTW 2025 logo belong to their respective owners.
