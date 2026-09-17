# Landing-page assets

The landing page keeps its replaceable imagery in this directory so production
screenshots or revised illustrations can be swapped without restructuring the
page.

| File | Dimensions | Purpose and crop | Figma source |
| --- | --- | --- | --- |
| `dabbli-wordmark.png` | 127 × 56 | Header wordmark; uncropped | `29:5` |
| `kid-set-overview.png` | 289 × 625 | Hero product screen; uncropped authentic iOS frame | `431:241` |
| `child-making.png` | 500 × 720 | How-it-works image; portrait crop keeps the child and making materials visible | `434:286` |
| `parent-child.png` | 528 × 640 | Parent review image; portrait crop keeps the shared work and both people visible | `436:291` |
| `chevron-down.svg` | Vector | Research disclosure indicator | `435:299` |

When replacing a raster image, keep the filename and intrinsic aspect ratio if
possible. Update the corresponding `width`, `height`, and alternative text in
`index.html` and `index-nl.html` if the replacement changes them.

The current parent-and-child image is an acceptable launch placeholder. A
future replacement should preserve the quieter review-together moment defined
in the Figma brief rather than introducing a celebratory or reward-focused
scene.

Alternative text is maintained next to each use in the English and Dutch HTML.
The assets were exported from the founder-provided Dabbli Figma file. Retain the
available project provenance and reconfirm publication rights before replacing
them with any unrelated third-party image.
