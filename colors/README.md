<h1 align="center">
  noicss.colors
</h1>
<p align="center">
  Color palette as custom CSS properties, that you can customize in vanilla CSS.
</p>

## Installation:

```Shell
npm install noicss.colors
```

## Usage:

import it into your CSS file:

```CSS
@layer colors, main;

@import url("noicss.colors") layer(colors);

/* YOUR OWN CSS: */
@layer main {
  body {
    background-color: var(--bgColor-5);
  }
  .card {
    background-color: var(--accentColor-1);
  }
  .cardText {
    color: var(--textColor-4);
  }
}
```

## Customization:

all values are optional, so you can set only the hue or all of them

```CSS
@layer colors, main;

@import url("noicss.colors") layer(colors);

/* YOUR OWN CSS: */
@layer main {
  :root {
    --noicssHue: 0; /* <number> from 0 - 360 | starting with 0 at red | default: 0 */
    --noicssSaturation: 1; /* <number> from 0 - 1 | default: 1 */
    --noicssBrightness: 65%; /* <percentage> from 0% - 100% | default: 65% */

    /* brightness change from one color to another: */
    --noicssBrightnessSpread: 20%; /* <percentage> from 0% - 100% | default: 0% */

    /* saturation decrement from one color to another: */
    --noicssSaturationSpread: 0.2; /* <number> from 0 - 1 | default: 0 */
  }
}
```

## Available colors:

there are 3 categories of colors, each with 5 variations to choose from:

| Accent:         | Text:         | Background: |
| --------------- | ------------- | ----------- |
| --accentColor-1 | --textColor-1 | --bgColor-1 |
| --accentColor-2 | --textColor-1 | --bgColor-2 |
| --accentColor-3 | --textColor-1 | --bgColor-3 |
| --accentColor-4 | --textColor-1 | --bgColor-4 |
| --accentColor-5 | --textColor-1 | --bgColor-5 |
|                 |               |             |

---
