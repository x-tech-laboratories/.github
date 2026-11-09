# X-Tech Laboratories brand

Logos, icons and design rules for X-Tech Laboratories and its projects.

## Logo

| File                                                         | Use                                                 |
| ------------------------------------------------------------ | --------------------------------------------------- |
| [`logo/x-tech-laboratories.svg`](logo/x-tech-laboratories.svg) | The full logo: banners, headers, the website.       |
| [`logo/x-tech.svg`](logo/x-tech.svg)                         | The short logo, where space is tight.               |
| [`icon/icon.svg`](icon/icon.svg)                             | The icon alone: avatars, favicons, app icons.       |
| [`icon/icon-inverted.svg`](icon/icon-inverted.svg)           | The icon in white, for use on a blue background.    |

Each SVG has a PNG next to it. The lettering in the logos is already converted to outlines, so they
look the same without the font installed.

The X is cut out of the hexagon. The full logo and the icon carry a white panel behind the X, so it
stays white on a dark background. The short logo has no panel: on a dark background, put a white
shape behind its X, or use the inverted icon.

## Colours, fonts and naming

The colour scheme, fonts and naming scheme are in the
[Design Guidelines](https://x-tech-laboratories.github.io/standards/design/) on the website.

## How the icon and logo are built

The icon is made in Inkscape:

1. Type an "X" in Rajdhani Bold, size 144.
2. Draw a hexagon in `#0088ff` with flat top and bottom sides, the same height as the X.
3. Scale the hexagon to 200% of its width and height.
4. Centre the hexagon and the X on each other, horizontally and vertically.
5. Select both and apply Path → Difference.

The logo adds the name to the icon:

1. Type a hyphen in Rajdhani Bold, size 144, colour `#0088ff`.
2. Place it so its left end touches the hexagon's right corner, centred vertically.
3. Slide it left until the hexagon's sides run smoothly into the top of the hyphen.
4. Continue typing after the hyphen: "Tech" for the short logo, or "Tech Laboratories" for the full one.
5. Convert the text to outlines (Path → Object to Path) before exporting.

## Other artwork

- [`icon-pack/`](icon-pack/) holds hexagon icons for files, folders and media, in sky blue.
- [`x-system.svg`](x-system.svg) is the X-System mark: a hexagon inside a hexagon.
