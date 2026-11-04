# FGO NPC V4

131 retained appearance groups covering the reviewed 1.5–2.7 roster.

Each group publishes two lossless WebP sprite strips: `avatars.webp` (768×128) and `portraits.webp` (3072×384). The six frames are **happy, angry, sad, laugh, neutral, confused**. Single-image groups repeat the same original image across all six frames. All selected expressions are included in these strips; individual emotion PNGs are in the local delivery package.

86 groups use six emotion mappings; 45 use a single image. Missing emotions may reuse or approximate an original face; the manifest records the selection and reason for every slot. Full exact aliases, at most six per new group, are in `V4_触发键清单.txt`. ASCII letter case is ignored by CSS. Seven redundant groups reuse the existing V3 catalogue resources.

Sources: original game sprite sheets and scene assets recorded per character in `manifest.json`.
