# OVGrid textures — 512 px

The colour and relief at 512 px of [OVGrid](https://world.ovgrid.com)'s texture bank, at
`https://estebanrfp.github.io/ovgrid-textures-512/`. The materials, their manifest and their 256 px
maps are in [ovgrid-assets](https://github.com/estebanrfp/ovgrid-assets).

Served by GitHub Pages, with CORS open to every origin. The bank is split by resolution so that
each repository stays under GitHub's 1 GB:

| Repository | What | Size |
|---|---|---|
| [ovgrid-assets](https://github.com/estebanrfp/ovgrid-assets) | every material at 256 px — colour, relief (normal) and ORM — its preview, and the bank's `manifest.json` and `index.json` | ~340 MB |
| [ovgrid-textures-512](https://github.com/estebanrfp/ovgrid-textures-512) | colour and relief at 512 px, for the few materials within 10 m of the camera | ~780 MB |
| [ovgrid-textures-1024](https://github.com/estebanrfp/ovgrid-textures-1024) | colour at 1024 px, within 4 m | ~570 MB |

A material's maps are `<category>/<subcategory>/<name>/<map>-<size>.ktx2`, under `textures/` in
ovgrid-assets and at the root of the two others: colour in
ETC1S, relief and ORM in UASTC with zstd, each with its full mip chain. Peers also share them by
their hash, so this origin stays light.

## Licence

The materials are dedicated to the public domain under [CC0 1.0](LICENSE), as their sources
publish them: 1,894 from [ambientCG](https://ambientcg.com), 867 from
[Poly Haven](https://polyhaven.com), and 11 made by OVGrid itself (water, end grain, glass).
Attribution is not required, but every material's authors and source page are in
[ovgrid-assets' manifest](https://github.com/estebanrfp/ovgrid-assets/blob/main/textures/manifest.json) — thank you to all of them.

## Author

Esteban Fuster Pozzi (@estebanrfp) - Full Stack JavaScript Developer
