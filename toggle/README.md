<h1 align="center">
  noicss.toggle
</h1>
<p align="center">
  Customizable & accessible toggle switch by noicss. In modern vanilla CSS.
</p>

## Installation:

```Shell
npm install noicss.toggle
```

## Usage:

import it into your CSS file:

```CSS
@layer toggle, main;

@import url("noicss.toggle") layer(toggle);

/* YOUR OWN CSS: */
@layer main {
  :root {
    /* CUSTOMIZATION: */
    --noicssToggleWidth: 64px;
    --noicssToggleHeight: 32px;

    --noicssToggleRed: oklch(58% 0.22 27);
    --noicssToggleGreen: oklch(70% 0.2 135);

    --noicssToggleBorder: oklch(95% 0 0);

    --noicssToggleButton: oklch(95% 0 0);
    --noicssToggleButtonBorder: oklch(80% 0 0);

    --noicssToggleOutline: currentcolor;
  }
}
```

and use it in your html like this:

```HTML
<label class="noicssToggle">
  <input type="checkbox" />
</label>
```
