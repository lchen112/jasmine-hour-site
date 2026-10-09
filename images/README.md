# Image slots

Drop a file in this folder using the slot name. The site picks it up on the next build. No component edits.

| Slot | Used for | Current file |
| --- | --- | --- |
| `hero.webp` (and `hero.jpg`) | Home hero, wide crop | Pearls tin on a cream backdrop |
| `pearls-100g.webp` | 100g card and product page | Square product photo |
| `pearls-200g.webp` | 200g card | Same tea, separate file so it can change later |
| `pearls-closeup.webp` | Texture figure on the product page | Tight crop of the dry pearls |
| `gift-set.webp` | Gift set card | Missing on purpose — the gift illustration is used |
| `about.webp` | About page | Missing on purpose — the leaves-and-blossoms illustration is used |
| `label.svg` or `label.png` | Header wordmark and the product-label plate | Missing — Ma Shan Zheng draws 茉莉 and Jasmine Hour |

Accepted extensions, in order: `.webp`, `.jpg`, `.jpeg`, `.png`, `.svg` for photos. For `label`, SVG is preferred, then PNG, WebP, JPEG.

Keep photos about 1600px on the long edge. The gift-set and about slots fall back to the SVGs in `public/illustrations/` until a file with that name exists.

`tin.jpg` from the owner is **not** in this folder. Its label is another brand. Do not crop it into a product photo.
