## cursors

a small library of generated mousecape cursor packs. 32 capes, 42 cursors each.

requires [mousecape](https://github.com/alexzielenski/Mousecape), or the newer
SwiftUI build [here](https://github.com/sdmj76/Mousecape-swiftUI).

### picking one

`capes/{style}/{style}-{palette}-{mode}-v2.cape`

| field | values | |
|---|---|---|
| style | `vanilla` `soft` `thin` `chonk` | line weight, corner radius, size |
| palette | `mono` `mocha` `latte` `nord` | accent colour on badges and spinner |
| mode | `light` `dark` | brightness of the desktop you use, not the cursor |

`light` draws a dark cursor with a pale outline; `dark` inverts it. Every
variant has its own identifier, so they all coexist in one Mousecape library.

previews for every variant are in [previews/](previews/).

### v2

- arrowheads no longer punch a notch where the shaft meets them
- magnifiers tint the lens, so zoom in/out differ at a glance
- corner resize cursors read as arrows instead of an X
- cell is a distinct thick plus; IBeamXOR gets a crossbar
- crosshair gains a centre dot; menu badge matches its siblings
- binary plists and quantised PNGs: 32 capes now weigh less than 12 did
- new `chonk` style, new `latte` and `nord` palettes

feel free to download, test, port, and redistribute (MIT).
feedback goes in [issues](https://github.com/KingJayan/mousecape-cursors/issues/new).

not verified on macOS — built and structurally validated, but untested in
Mousecape itself. reports welcome.
