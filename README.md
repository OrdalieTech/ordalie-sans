# Ordalie Sans

A neo-grotesque sans serif for interfaces and text. Variable from Thin to Black, in roman and italic.

[Specimen](https://ordalietech.github.io/ordalie-sans/) · [Download the latest release](https://github.com/OrdalieTech/ordalie-sans/releases/latest)

## Characteristics

| | |
|---|---|
| Weights | Variable, 100 to 900 |
| Named instances | Thin, ExtraLight, Light, Regular, Book (450), Medium, SemiBold, Bold, ExtraBold, Black |
| Styles | Roman and italic (9° slant, single-storey a) |
| Glyphs | 574 |
| Languages | 281 Latin-script languages |
| Metrics | 1000 units per em, x-height 520, cap height 720 |
| Kerning | Class-based, across the full weight range |
| OpenType features | `kern` `tnum` `zero` `sups` `numr` `dnom` `ordn` `case` `ss01` to `ss14` |

## Additions

Ordalie Sans is derived from [Aspekta](https://github.com/ivodolenc/aspekta) by Ivo Dolenc. It keeps the original drawing and adds:

- Guillemets `« » ‹ ›` with thin no-break spaces (U+202F, U+2009), figure and punctuation spaces
- Section and pilcrow signs `§ ¶`, ligatures `Œ œ`, bullet, tilde
- Superior figures and letters, ordinals `ª º`, numero `№`
- Fractions `½ ¼ ¾ ⅓ ⅔ ⅛` and a fraction slash
- Tabular figures (`tnum`) and a slashed zero (`zero`)
- Signs `± ≠ ≈ ~ ′ ″` on the math axis
- Round dots on `i`, `j` and all punctuation
- Case forms for dashes, brackets, guillemets and signs
- Kerning, an italic, and the full weight axis for every added glyph

## Files

```
fonts/variable/   OrdalieSans[wght].ttf, OrdalieSans-Italic[wght].ttf
fonts/static/     one TTF per named instance, roman and italic
fonts/webfonts/   WOFF2: variable fonts, and static/ for each instance
```

## Use

**Desktop**: install the two files in `fonts/variable/`. For software without variable font support, install the files in `fonts/static/`.

**Web**:

```css
@font-face {
  font-family: 'Ordalie Sans';
  src: url('OrdalieSans%5Bwght%5D.woff2') format('woff2');
  font-weight: 100 900;
  font-style: normal;
}
@font-face {
  font-family: 'Ordalie Sans';
  src: url('OrdalieSans-Italic%5Bwght%5D.woff2') format('woff2');
  font-weight: 100 900;
  font-style: italic;
}
```

## License

Ordalie Sans is licensed under the [SIL Open Font License 1.1](OFL.txt), with Reserved Font Name "Ordalie Sans". It is derived from Aspekta © 2025 Ivo Dolenc, under the same license.
