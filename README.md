# Thuna Font

[![Build](https://img.shields.io/badge/build-GitHub%20Actions-blue?logo=githubactions&logoColor=white)](https://github.com/mooniak/thuna-font/actions)
[![License: Mooniak EULA](https://img.shields.io/badge/license-Mooniak%20EULA-lightgrey)](EULA.txt)
![Repository: private](https://img.shields.io/badge/repo-private-lightgrey)

Thuna is a Sinhala typeface by Aravinda Illangangedara, maintained by [Mooniak](https://mooniak.com/). It is a premium font, distributed under the Mooniak Fonts EULA. It is in an early (alpha) stage.

![Thuna specimen](documentation/image1.png)
![Thuna character set](documentation/image2.png)

## About

Thuna started from a FontForge drawing (`sources/1-drawing/Thuna.sfd`, kept for reference) and a template of letters in `documentation/`. The source is now a Glyphs package, `sources/Thuna.glyphspackage`, with [LankaGlyphset](https://github.com/mooniak/lanka-glyphsets) glyph names (`ka-sinh`, `aasign-sinh`, …) and OpenType features generated for them.

- 348 glyphs, one master (Regular), 1000 units per em.
- Sinhala letters, vowel signs, hal forms, the drawn conjuncts, Sinhala Lith digits and a basic Latin set.
- Alternates for the i / ii / u / uu signs and virama (`ss01`, `ss02`).

What is still to do for this font is tracked centrally with `mnik check thuna`.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

- `make build` will produce font files.
- `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
- `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions.

## Changelog

- 0.001 — Ported to the Mooniak font setup: Glyphs package source, LankaGlyphset glyph names, generated OpenType features, Mooniak metadata and vertical metrics.

## License

Mooniak Fonts EULA — proprietary, all rights reserved. This font is **not** open source and is not licensed under the SIL Open Font License. See [EULA.txt](EULA.txt).
For licensing, contact hello@mooniak.com.

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
