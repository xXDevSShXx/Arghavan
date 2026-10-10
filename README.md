# Arghavan
> Named after the Persian word for the Judas tree, whose blossoms are a red-leaning purple.

A dark theme and style guide for the [DSam](https://github.com/xxdevsshxx/dsam) system: near-black surfaces, vanilla-cream text, and a single vibrant warm-purple accent.
## Principles

- **Dark, high contrast, easy on the eyes.** Cream text on near-black; never pure white on pure black.
- **One accent.** Purple marks focus and the current item, and distinguishes elements where spacing and size cannot.
- **Plain but precise.** A middle ground between terse and engineered: sharp corners, thin borders, small gaps.
- **Minimal glyphs.** Text first; Nerd Font icons only where text would be ambiguous.
- **Type.** Monospace in the terminal and bar, sans-serif in browsers and GUI.

## Palette

| Role | Hex | Use |
|---|---|---|
| bg | `#121212` | base background |
| surface | `#1B1B1B` | bars, popups, inactive panels |
| line | `#2B2B2B` | borders, separators, scrollbar |
| muted | `#8C867A` | secondary text, placeholders |
| fg (vanilla) | `#EDE3BA` | primary text |
| accent-base | `#9011BF` | fills, active elements, non-text distinction |
| accent | `#BE55E6` | focus, prompt, links, text-level accent |
| accent-dim | `#3A0F4D` | selection and highlight backgrounds |
| error | `#D9604C` | |
| warning | `#D9A441` | |
| success | `#7FAE6B` | |
| info | `#6E9BC4` | |

`accent-base` is too dark for text on `bg` (about 2.7:1), so text and focus indicators use `accent` (about 5:1). Primary text on `bg` is about 14:1.

### Terminal (ANSI)

| Color | Hex |
|---|---|
| black | `#121212` |
| red | `#D9604C` |
| green | `#7FAE6B` |
| yellow | `#D9A441` |
| blue | `#6E9BC4` |
| magenta | `#BE55E6` |
| cyan | `#6FAFA8` |
| white | `#EDE3BA` |

Bright variants are the same hues at +10% lightness.
