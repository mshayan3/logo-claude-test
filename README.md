# The Marauders

The mark is locked. This repo holds it in every sanctioned colourway.

`assets/mark-*.svg` are the mark alone on transparency — drop them on any ground.
`assets/tile-*.svg` are the mark pre-composed on its ground, for places that
need a flat square (avatars, favicons, app icons).

## Colourways

### Core

| Name | Mark | Ground | Use |
|------|------|--------|-----|
| **Ink on Bone** | `#0B0B0B` | `#EBE7E1` | Primary. Documents, decks, contracts, anything printed. |
| **Bone on Ink** | `#EBE7E1` | `#17171A` | Reversed. Avatars, merch, stream, dark UI. |
| **Tonal** | `#2B2B33` | `#17171A` | Watermark, deboss, blind emboss, large background use. |

### Oxblood — recommended accent

| Name | Mark | Ground |
|------|------|--------|
| Oxblood on Bone | `#7E1C28` | `#EBE7E1` |
| Bone on Oxblood | `#EBE7E1` | `#7E1C28` |
| Oxblood on Ink | `#A8283A` | `#17171A` |

Deep, heraldic, closer to dried blood than to a team colour. It carries the
martial edge the name asks for without landing anywhere near the hot reds every
other org already owns. Lightened to `#A8283A` on ink, where the deep value
would otherwise disappear.

### Alternates

| Name | Mark | Ground | Reads as |
|------|------|--------|----------|
| Brass on Ink | `#B4893C` | `#17171A` | Medal, trophy, badge on a uniform. Pedigree. |
| Gunmetal on Bone | `#4E555E` | `#EBE7E1` | Industrial, cool, understated. |
| Signal on Ink | `#E2572E` | `#17171A` | Heat. Loudest option here. |

## Rules

- One colourway per surface. The mark is never two colours at once.
- Never place the mark on a mid-tone. It needs either Bone or Ink beneath it —
  the channels are what make it read, and they close up against a middling value.
- Never add a stroke, shadow, bevel or gradient. The channels do that work.
- Never re-space the channels to fit a layout. Scale the whole mark.

## Type

**Jost** 500, all caps, tracked at 0.3em for the name and 0.44em for the
descriptor, split by a hairline rule.

## Construction

Traced from the supplied artwork onto a 200 x 262 grid.

The two diagonals descend **inward** — high at the outer edges, plunging toward
the centre, where they meet the chevron. Diagonal and chevron read as one
continuous stroke. Getting this direction backwards inverts the whole mark: the
upper wedges taper the wrong way and the form stops reading.

Channels are 11 units measured perpendicular, held constant across the verticals,
the diagonals and the chevron, so the slopes carry different vertical offsets.

The side panels run out to points at the bottom. Only the centre column meets the
base, so the flat bottom edge is the width of that column alone.

If a source file turns up, replace the mask geometry in `assets/mark-ink.svg` and
regenerate — every other file is that same geometry with a different fill.
