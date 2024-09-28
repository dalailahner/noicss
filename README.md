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
- [toggle](https://github.com/dalailahner/noicss/tree/master/toggle)
- more to come...

## Installation:

get the whole library:

```Shell
npm install noicss
```

or you can pick individual modules depending on your needs:

```Shell
npm install noicss.reset noicss.colors noicss.toggle
```

## Usage:

import the things you need into your CSS file:

```CSS
@layer reset, colors, toggle, main;

@import url("noicss/reset") layer(reset);
@import url("noicss/colors") layer(colors);
@import url("noicss/toggle") layer(colors);

/* YOUR OWN CSS: */
@layer main {

}
```

or when you installed the modules individually:

```CSS
@layer reset, colors, toggle, main;

@import url("noicss.reset") layer(reset);
@import url("noicss.colors") layer(colors);
@import url("noicss.toggle") layer(colors);

/* YOUR OWN CSS: */
@layer main {

}
```

---
