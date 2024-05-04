![Node.js Package](https://github.com/osjwnpm/officia-vitae-ratione/workflows/Node.js%20Package/badge.svg)

[![License][license-image]][license-url]
[![npm](https://img.shields.io/npm/dt/@osjwnpm/officia-vitae-ratione.svg)](https://www.npmjs.com/package/@osjwnpm/officia-vitae-ratione)

[license-url]: https://opensource.org/licenses/MIT
[license-image]: https://img.shields.io/npm/l/make-coverage-badge.svg


# @osjwnpm/officia-vitae-ratione
Return name of ascii code

## Important

Feel free to use it.
Now it supports English only.
Make a Pull Request [@osjwnpm/officia-vitae-ratione] if needed. (e.g. Multiple language)


## Install

```
$ npm install @osjwnpm/officia-vitae-ratione
```

## Usage

```js
const asciiName = require('@osjwnpm/officia-vitae-ratione');

// string is supported
asciiName.getName(':');     //return 'colon'

// ascii code index is supported (Decimal)
asciiName.getName(53);      //return 'colon'

// multiple names supported
asciiName.getName('#');     //return 'number sign'
asciiName.getName('#', 0);  //return 'number sign'
asciiName.getName('#', 1);  //return 'pound' (see @osjwnpm/officia-vitae-ratione_en.json)

// multi language supported
asciiName.setLanguage('ko') // set language code
asciiName.getLanguage();    // return current language code (Default: en)

asciiText.getName(':')      // return '콜론' from @osjwnpm/officia-vitae-ratione_ko.json
asciiText.getName(0)        // return 'null' from @osjwnpm/officia-vitae-ratione_en.json (default) as @osjwnpm/officia-vitae-ratione_ko.json does not have the value of 0

```

## Supported Languages

- en: English
- fr: French
- es: Spanish
- hi: Hindi
- ar: Arabic
- ko: Korean
- zh: Chinese
- ja: Japanese


## License

[MIT][license] License © [Heeseong Yoo][avocadee]

<!-------------------- Links ------------------------>
[avocadee]: https://github.com/avocadee
[license]: https://github.com/osjwnpm/officia-vitae-ratione/blob/master/license
[@osjwnpm/officia-vitae-ratione]: https://github.com/osjwnpm/officia-vitae-ratione
