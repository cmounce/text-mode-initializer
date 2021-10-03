# Palettes
## Algorithmic
`cga.pal` is the default text-mode palette for the CGA graphics card and its
successors. It is effectively public domain, and is probably not even eligible
for copyright because it follows a very obvious pattern.

`rgb332.pal` is a non-regular RGB palette that uses 3 levels of red, 3 levels
of green, and 2 levels of blue: this results in 18 possible combinations, so
black and white are omitted to get exactly 16 colors. Designed not from an
artistic standpoint, but to be visually distinct from other 16 color palettes
in common use. Public domain.

`scatter.pal` is generated by using Martin Roberts's quasirandom sequence R3
to sample the RGB color cube (see `procedural-palettes.py` in the `scripts/`
folder). Public domain.

## Converted
These were converted from existing color palettes via `convert-palette.py`.
The colors are not exact matches because VGA's text mode uses 18-bit color
(6 bits per channel) instead of 24-bit color (8 bits per channel).

`solarize.pal` is converted from Ethan Schoonover's well-known Solarized
palette. The [GitHub project](1) is MIT licensed, although that may apply more
to the various config files, as opposed to the colors themselves.

[1]: https://github.com/altercation/solarized

`sweetie.pal` is converted from GrafxKid/Jason Mercado's Sweetie 16, currently
the most-downloaded 16 color palette on [Lospec](2). I haven't been able to
find an explicit license, but he seems okay with the MIT-licensed TIC-80
project [using it as their default palette](3).

[2]: https://lospec.com/palette-list/sweetie-16
[3]: https://github.com/nesbox/TIC-80/issues/873