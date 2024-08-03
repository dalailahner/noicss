<h1 align="center">
  noicss
</h1>
<p align="center">
  A modular CSS collection to set you up with all kinds of things you might need.
</p>
<p align="center">
  In modern vanilla CSS.
</p>

## noicss modules:

- [reset](https://github.com/dalailahner/noicss/tree/master/reset)
- [colors](https://github.com/dalailahner/noicss/tree/master/colors)
- more to come...

## Installation:

get the whole library:

```Shell
npm install noicss
```

or you can pick individual modules depending on your needs:

```Shell
npm install noicss.reset
```

## Usage:

import the things you need it into your CSS file:

```CSS
@layer reset, colors, main;

@import url("noicss.reset") layer(reset);
@import url("noicss.colors") layer(colors);

/* YOUR OWN CSS: */
@layer main {

}
```

---
