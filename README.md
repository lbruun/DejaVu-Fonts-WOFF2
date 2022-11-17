# DejaVu fonts in WOFF2 format

Re-publishes [DejaVu Fonts](https://github.com/dejavu-fonts/dejavu-fonts) in WOFF2 format. 

WOFF2 format is the format used on the web. All major browsers support WOFF2 format, with the exception
of IE11 which can understand WOFF1, but not WOFF2. See [Can-I-Use](https://caniuse.com/woff2) for more information.

The project uses Google's [WOFF2 tool](https://github.com/google/woff2) to convert from TrueType format to WOFF2 format.
(technically, the fonts are still in TrueType format, as the WOFF2 format is solely about compression)

The main purpose of the project is to act as an upstream channel for other - more targeted - distributions.

## Bundles

The project publishes two packages:

- All DejaVu fonts.
- LGC DejaVu fonts. These are a subset of the full set, only containing Latin, Greek and Cyrillic characters. 
This reduces the total download size from around 3.7 MB to 3.0 MB which may matter if you want your website to display quickly.

Versioning follows that of releases from the [DejaVu Fonts project](https://github.com/dejavu-fonts/dejavu-fonts).


## License

The font files have their own LICENSE file included in the Released package. This is simply the original
LICENSE file from the [DejaVu Fonts project](https://github.com/dejavu-fonts/dejavu-fonts).

This project, its documentation and source code, is licensed under Apache License v2.

