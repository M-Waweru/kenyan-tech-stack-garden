# Book — Quartz / manuscript content

This folder is the **editorial source of truth** for *The Kenya Tech Stack* when working in Cursor. It is structured for **Quartz** deployment (folders become site sections).

## Layout

| Path | Contents |
|------|----------|
| **`index.md`** | Site landing: overview, links into the tree |
| **`manuscript/`** | Prologue and Parts I–XX (`part-01-…` through `part-20-…`) |
| **`appendices/`** | Cast, rail map, research methodology, source catalog |
| **`meta/`** | Full chapter outline (`structure.md`), [factual rigor audit](meta/factual-rigor-audit.md) |

## Deploying to Quartz

Copy or sync this **`book/`** directory into your Quartz repo’s content root (e.g. `kenyan-tech-stack-garden/content/`), replacing the previous flat layout. Update any CI paths if they assumed all `.md` files lived in one folder.
