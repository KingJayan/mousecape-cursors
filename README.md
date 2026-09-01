## cursors

a small library of my own mousecape cursor packs.

requires [mousecape](https://github.com/alexzielenski/Mousecape), or the newer
SwiftUI build [here](https://github.com/sdmj76/Mousecape-swiftUI).

### picking one

`capes/{style}/{style}-{palette}-{mode}-{version}.cape`

| style | |
|---|---|
| `vanilla` | the baseline |
| `soft` | rounder, heavier outline |
| `thin` | lighter weight, smaller |
| `chonk` | vanilla at maximum weight |
| `cartoony` | rubber-hose arrow, gloved hands with cuffs |
| `bubble` | inflated, glossy, very round |
| `macintosh` | 1-bit pixel art, no antialiasing, no shadow, wristwatch for wait |
| `material` | no outline, pastel accent tint, soft elevation shadow |
| `demo` | glossy aqua-era gradient and highlight |

| palette | |
|---|---|
| `mono` | no accent, body color only |
| `mocha` `latte` `nord` | full-saturation accents |
| `ink` | ink on paper, near-monochrome badges |
| `sage` | muted green and clay |

`mode` is `light` or `dark` — the brightness of the desktop you use, not of the
cursor. `light` gives a dark cursor with a light outline; `dark` inverts it.

preview imgs in [previews/{style}/](previews/), same layout as `capes/`.

changes in [CHANGELOG.md](CHANGELOG.md). 108 capes, 20MB — clone with
`--depth 1` if you only want the current set.

built and structurally validated, but not verified in mousecape on macos.

feedback, reports in [issues](https://github.com/KingJayan/mousecape-cursors/issues/new).
feel free to download, test, port, and redistribute (MIT).
