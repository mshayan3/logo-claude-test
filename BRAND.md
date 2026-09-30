# The Marauders — brand guidelines

The full guideline is an eight-page document on the canvas. This file is the
same rules in text, for anyone working from a terminal or a pull request.

## Colour

| Name | Hex | RGB |
|------|-----|-----|
| Bone | `#EAE3DA` | 234 227 218 |
| Ink | `#17171A` | 23 23 26 |
| Oxblood | `#7F1B28` | 127 27 40 |

Four sanctioned pairings, all approved:

| Mark | Ground | Use |
|------|--------|-----|
| Ink | Bone | Primary. Documents, decks, contracts, print. |
| Bone | Ink | Reversed. Avatars, merch, stream, dark UI. |
| Oxblood | Bone | Accent, light surfaces. |
| Oxblood | Ink | Accent, dark surfaces. |

The mark is never two colours at once, and never sits on a mid-tone —
the channels close up against a middling value and the form stops reading.

Oxblood on ink is the tightest pairing in the set. It holds at size but loses
definition small; below 40 px use bone on ink instead.

CMYK: Bone 0·3·7·8 · Ink 12·12·0·90 · Oxblood 0·79·69·50. These are unmanaged
conversions for uncoated stock — have the printer pull a physical match before
any long run, and do not guess a Pantone from them.

## Type — Saira

One superfamily, three voices. Free, open licence, on Google Fonts.

| Role | Face | Spec |
|------|------|------|
| Marque | Saira 600 | Caps, tracked 0.22em. Locked — never retyped or re-tracked. |
| Headline | Saira Condensed 700 | Decks, slides, merch, stream. |
| Text | Saira 400 | 1.6 line-height. Contracts, proposals, site, email. |
| Data | Saira 500 | Stats, tables, match figures. |

**Confirmed.** Saira ships Condensed, Semi-Condensed and Normal at weights
100–900, upright and italic. One family covers the marque lockup, the athletic
headline voice and clean body text without a second licence or a fallback.

Its squarish skeleton and flat terminals rhyme with the mark's cut planes.

    <link href="https://fonts.googleapis.com/css2?family=Saira:wght@300;400;500;600;700&family=Saira+Condensed:wght@500;600;700&display=swap" rel="stylesheet">

### Considered and passed over (for the record)

- **Archivo** — neutral grotesque, reads firm rather than gaming, sets long text
  better than anything else tested. Weaker formal rhyme with the mark. The safe
  alternative if Saira reads too technical.
- **Chakra Petch** — clipped corners echo the mark's chamfers exactly, but it
  reads loudly as gaming and only spans 300–700 with no widths. Wordmark only,
  if at all.
- **Space Grotesk** — contemporary with character; the quirks in the R and G
  fight a mark this geometric, and it has a single width.

## Clearspace and size

**Clearspace** is X on all sides, where X is half the height of the mark. No
type, image, rule, edge or other logo enters it. On a crowded surface, scale the
mark down rather than tightening its clearspace.

**Minimum size** is 24 px tall on screen, 8 mm tall in print. Below that the
channels close up and the helmet turns to a blob. There is no small-size
variant. The only exception is a 16 px favicon.

**Proportion** is locked at 766 × 1004 — 1 : 1.31. Scale both axes together.

**Alignment**: centre the mark optically, not mathematically. Its visual weight
sits low, so in a square frame it is set slightly above centre.

## Lockups

    [mark]  THE MARAUDERS          ← primary, horizontal
            ————————————————
            ESPORTS ADVISORY

Mark height drives every measure. Gap between mark and wordmark is one quarter
of mark height; wordmark cap-height is one sixth of mark height; the hairline
rule spans the wordmark exactly; the descriptor sits below, tracked 0.4em.

A **stacked** lockup exists for narrow and square surfaces — same parts, centred
on one axis, gap one fifth of mark height. The **mark alone** is for avatars,
favicons, patches and stamps; in a square or circle it occupies half the frame.

"Esports Advisory" is the only element stating what the business is, and the
name will not do that job alone. It stays in every external lockup. It may be
dropped only where the mark appears alone as an avatar or icon.

Never rebuild a lockup by eye.

## Misuse

Never stretch, condense or scale one axis. Never rotate or tilt. Never recolour
outside the three brand colours. Never add shadow, glow, bevel, gradient or
outline. Never place the mark on a mid-tone. Never crowd it. Never use two
colours at once. Never crop it, fill it with a pattern or photo, or animate it
in a way that deforms the form.

The mark is made of cut channels. Almost anything done to it after export closes
those channels and the helmet stops reading. Scale the master artwork and change
nothing else.

## Files

`assets/mark-ink.png`, `mark-bone.png`, `mark-oxblood.png` — 766 x 1004, the
supplied artwork cut from its background and recoloured, alpha preserved on the
antialiased edges. Drop them on any approved ground.

Master artwork is held by the client. These are working exports; if a vector
master exists, use it for anything printed, cut or embroidered.
