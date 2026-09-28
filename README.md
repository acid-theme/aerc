# Acid for aerc

Two flavours: **Acetic** (`#000000`), vibrant, and **Citric** (`#1c1b19`), muted.

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

Every style object aerc documents is set. Selection raises a row rather than
inverting it, so the colour that marks a message unread, flagged or deleted
survives being selected.

## Files

- `acid-acetic`
- `acid-citric`

## Generated

Acid 0.1.0, rendered by acidify from
[`ports/aerc/acid.styleset.tera`](https://github.com/acid-theme/acid/blob/main/ports/aerc/acid.styleset.tera).
Edits to these files are overwritten on the next release. Report issues on
[acid-theme/acid](https://github.com/acid-theme/acid/issues).

## Licence

MIT.
