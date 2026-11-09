# Colemak-36
 
Each half has 3 rows of 5 keys plus 3 thumb keys. The right half is shown mirror-image, so it reads left to right as you see it on the keyboard.
 
**Legend:** `▽` = transparent (falls through to Base) · `·` = unassigned · **L1 / L2 / L3** = hold for that layer · two-line keys show the Shift character on top, like a keycap
 
---
 
## Layer 0 · Base
 
Always active.
 
| | | | | | ‖ | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Q | W | F | P | Bksp | ‖ | Del | L | U | Y | O |
| A | S | R | T | Enter | ‖ | Tab | N | E | I | Space |
| Z | X | C | K | AltGr | ‖ | **L3** | M | V | J | H |
| | | Alt | Super | Shift | ‖ | **L1** | **L2** | Ctrl | | |
 
---
 
## Layer 1 · Symbols & Numbers
 
Hold the right inner thumb key (**L1**).
 
| | | | | | ‖ | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| `~`<br>`` ` `` | `"`<br>`'` | `:`<br>`;` | B | ▽ | ‖ | Copy | `!`<br>1 | `@`<br>2 | `#`<br>3 | `+`<br>`=` |
| `<`<br>`,` | `>`<br>`.` | `?`<br>`/` | D | ▽ | ‖ | Paste | `$`<br>4 | `%`<br>5 | `^`<br>6 | `_`<br>`-` |
| `{`<br>`[` | `}`<br>`]` | `\|`<br>`\` | G | ▽ | ‖ | Cut | `&`<br>7 | `*`<br>8 | `(`<br>9 | `)`<br>0 |
| | | ▽ | ▽ | ▽ | ‖ | ▽ | ▽ | ▽ | | |
 
Copy / Paste / Cut = `Ctrl+C` / `Ctrl+V` / `Ctrl+X`.
 
---
 
## Layer 2 · Navigation & F-keys
 
Hold the right middle thumb key (**L2**).
 
| | | | | | ‖ | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| PgUp | Home | ↑ | End | ▽ | ‖ | Undo | F1 | F2 | F3 | F4 |
| PgDn | ← | ↓ | → | ▽ | ‖ | Redo | F5 | F6 | F7 | F8 |
| Ins | Word ← | · | Word → | ▽ | ‖ | Esc | F9 | F10 | F11 | F12 |
| | | ▽ | ▽ | ▽ | ‖ | ▽ | ▽ | ▽ | | |
 
Word ← / → = `Ctrl+←` / `Ctrl+→`. Undo / Redo = `Ctrl+Z` / `Ctrl+Y`.
 
---
 
## Layer 3 · International
 
Hold the bottom inner key of the right hand (**L3**).
 
| | | | | | ‖ | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| „ | “ | ” | · | ▽ | ‖ | Vol + | · | Ü<br>ü | · | Ö<br>ö |
| Ä<br>ä | §<br>ß | · | · | ▽ | ‖ | Vol − | · | É<br>é | · | – |
| ‚ | ‘ | ’ | · | ▽ | ‖ | ▽ | « | » | ‹ | › |
| | | ▽ | ▽ | ▽ | ‖ | ▽ | ▽ | ▽ | | |
 
---
 
## Unicode macros (Layer 3)
 
Typed via `Ctrl+Shift+U` + hex code + Enter (Linux / GTK input).
 
| Macro | Char | Code |
|---|:-:|---|
| M0 | „ | U+201E |
| M1 | “ | U+201C |
| M2 | ” | U+201D |
| M3 | ‚ | U+201A |
| M4 | ‘ | U+2018 |
| M5 | ’ | U+2019 |
| M6 | « | U+00AB |
| M7 | » | U+00BB |
| M8 | ‹ | U+2039 |
| M9 | › | U+203A |
| M10 | – | U+2013 |
 
## AltGr keys (Layer 3)
 
These assume the **US International (AltGr)** layout in your OS.
 
| Key | Sends | Char | With Shift |
|:-:|---|:-:|:-:|
| ä | `AltGr+Q` | ä | Ä |
| ß | `AltGr+S` | ß | § |
| ö | `AltGr+P` | ö | Ö |
| ü | `AltGr+Y` | ü | Ü |
| é | `AltGr+E` | é | É |
 
## Good to know
 
- Macro **M6** («) sends its key-up before the key-down, the reverse of the other macros. If « doesn't type, swap those two steps in Vial.
- Macro **M11** (`Super+Shift+N`, then types "mail") is defined but not placed on any key.
- Five tap dances are configured but unused: `!` / Alt, `%` / Ctrl, `^` / RCtrl, `)` / Alt, AltGr / Alt.
- No combos or key overrides are set. Layers 4–9 and the encoders are empty.
 
