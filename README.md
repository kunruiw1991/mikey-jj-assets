# Mikey & JJ Asset Library

**101 distinct collected assets and references** for Mikey and JJ (Maizen).

[Browse the visual library](https://kunruiw1991.github.io/mikey-jj-assets/) · [Download repository ZIP](https://github.com/kunruiw1991/mikey-jj-assets/archive/refs/heads/main.zip) · [Source index](SOURCES.md) · [JSON catalog](catalog.json)

Search by character, title or format; filter by category and source; open large previews and download original files. The gallery works by opening `index.html` locally too.

## Contents

| Category | Count |
| --- | ---: |
| Character Art | 4 |
| Coloring | 7 |
| Gameplay Reference | 11 |
| Illustration Reference | 23 |
| Merchandise Reference | 22 |
| Model | 2 |
| Model Preview | 2 |
| Pose | 28 |
| Texture | 2 |

The collection includes character artwork and poses, official OBJ models and textures, coloring sheets, illustrations, gameplay screenshots and merchandise reference photos. These categories describe different kinds of material; reference photographs are not transparent game sprites.

## Files

- `assets/`: original source files and companion OBJ material helpers.
- `catalog.json`: titles, characters, categories, source URLs, dimensions, SHA-256 checksums and rights notes.
- `catalog.js`: gallery metadata plus compressed preview images; previews do not count as extra assets.
- `index.html`, `style.css`, `gallery.js`: dependency-free searchable gallery.
- `SOURCES.md`: one source entry for each catalog item.

## Models

Import `assets/jj-model.obj` or `assets/mikey-model.obj` with its companion `.mtl` and texture PNG in the same folder. The OBJ downloads are preserved unchanged. Companion MTL files were added to connect the included textures; they are helpers, not additional collected assets. Rigging or animation is not included.

## Sources and rights

Collected from the [official Maizen website](https://www.maizen.com/downloads/) and the [community Mikey gallery](https://fanmaizen.fandom.com/wiki/Mikey/Gallery). Every entry records its exact file URL and source page. Source publication does not establish an open-content license. Maizen characters and collected images remain the property of their respective rights holders; this repository does not grant a blanket reuse license. Check the original source and obtain any permissions required for your intended use.

## Count and integrity

101 catalog entries, excluding helper files and preview encodings. Exact byte/pixel duplicates and obvious repeated size/language variants were excluded. See [collection checks](docs/validation.md).
