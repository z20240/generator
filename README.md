[![Express Logo](https://raw.githubusercontent.com/z20240/pictureRepository/master/uPic/express-typescript.png?token=ACZYRQWCRQLYSFATS76CGHTBK3IDK)](http://expressjs.com/)

[Express'](https://www.npmjs.com/package/express) application generator with typescript.

This tools is forked from express-generator for people whom want to build an express project with typescript.

All args of express-generator are provided, you can use it as express-generator.

[![NPM Version][npm-image]][npm-url]
[![Licensee][licensee-image]][npm-url]
[![Express Version][express-version-image]][express-url]
[![Typescript Version][typescript-version-image]][typescript-url]


## Installation

```sh
$ npm install -g typescript-express-generator
```

## Quick Start

The quickest way to get started with express is to utilize the executable `express(1)` to generate an application as shown below:

Create the app:

```bash
$ ts-express --view=hbs /tmp/foo && cd /tmp/foo
```

Install dependencies:

```bash
$ npm install
```

Start your Express.js app at `http://localhost:3000/`:

```bash
$ npm start
```

## Command Line Options

This generator can also be further configured with the following command line flags.

        --version        output the version number
    -e, --ejs            add ejs engine support
        --pug            add pug engine support
        --hbs            add handlebars engine support
    -H, --hogan          add hogan.js engine support
    -v, --view <engine>  add view <engine> support (dust|ejs|hbs|hjs|jade|pug|twig|vash) (defaults to jade)
        --no-view        use static html instead of view engine
    -c, --css <engine>   add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
        --git            add .gitignore
    -f, --force          force on non-empty directory
    -h, --help           output usage information

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/express-generator.svg
[licensee-image]: https://img.shields.io/badge/licensee-MIT-green
[typescript-version-image]: https://img.shields.io/badge/typescript-4.4-blue
[express-version-image]: https://img.shields.io/badge/express-4.16-green
[npm-url]: https://npmjs.org/package/typescript-express-generator
[downloads-url]: https://npmjs.org/package/typescript-express-generator
[typescript-url]: https://www.typescriptlang.org/
[express-url]: https://expressjs.com/
