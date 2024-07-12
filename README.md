# [hosteze Icons](https://github.com/adimail/hosteze-icons)

[![npm][npm-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/react-icons.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/react-icons

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
