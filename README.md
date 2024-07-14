# [hosteze Icons](https://github.com/adimail/hosteze-icons)

[![npm][npm-version-image]][npm-url]
![license](https://img.shields.io/npm/l/hosteze-icons.svg?style=flat-square)
[![npm][npm-downloads-image]][npm-url]

[npm-version-image]: https://img.shields.io/npm/v/hosteze-icons.svg?style=flat-square
[npm-downloads-image]: https://img.shields.io/npm/dw/hosteze-icons.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/hosteze-icons

> Hosteze-icons is under active development with no stable releases.

Collection of icons visible on [Hosteze](https://hosteze.in) site and mobile app.

Include icons from hosteze in your React projects easily with `hosteze-icons`, which uses ES5 imports that allows you to include only the icons that your project is using.

## Installation (for standard modern project)

```bash
yarn add hosteze-icons
# or
pnpm add hosteze-icons
# or
npm install hosteze-icons --save
```

example usage

```jsx
import { Logo } from 'hosteze-icons';

function Question() {
  return (
    <h3>
      welcome to <Logo />!
    </h3>
  );
}
```

## Licence

GPL-3.0 license
