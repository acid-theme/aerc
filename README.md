# Acid for aerc

Three flavours: **Acetic** (`#000000`), pure black with vibrant accents; **Citric** (`#1c1b19`), warm dark grey with muted accents; and **Lactic** (`#ffffff`), white with accents darkened to match.

Part of [Acid](https://github.com/acid-theme/acid), a very dark colourscheme in two
flavours. The main README lists the other ports.

## Install

```sh
mkdir -p ~/.config/aerc/stylesets
curl -fsSLo ~/.config/aerc/stylesets/acid-acetic \
  https://raw.githubusercontent.com/acid-theme/aerc/main/acid-acetic
```

Then select it in `aerc.conf`:

```ini
[ui]
styleset-name=acid-acetic
```

Every style object this aerc accepts is set. Selection raises a row rather than
inverting it, so the colour that marks a message unread, flagged or deleted
survives being selected.

aerc 0.22 documents style objects for quoted text, inline diffs, code, urls and
signatures, and ships stylesets that use them, but its parser rejects them — and
one rejected object stops aerc starting. They are left out until the binary
accepts them.

## Files

- `acid-acetic`
- `acid-citric`
- `acid-lactic`

## Generated

Acid 0.1.0, rendered by acidify from
[`ports/aerc/acid.styleset.tera`](https://github.com/acid-theme/acid/blob/main/ports/aerc/acid.styleset.tera).
Edits to these files are overwritten on the next release. Report issues on
[acid-theme/acid](https://github.com/acid-theme/acid/issues).

## Licence

MIT.
