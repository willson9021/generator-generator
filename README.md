# generator-generator [![Build Status](https://secure.travis-ci.org/willson9021/generator-generator.svg?branch=master)](https://travis-ci.org/willson9021/generator-generator) [![Coverage Status](https://coveralls.io/repos/willson9021/generator-generator/badge.svg?branch=master&service=github)](https://coveralls.io/github/willson9021/generator-generator?branch=master)


> Yeoman generator generating a willson9021 generator

![Yo dawg, I heard you like generators?](http://i.imgur.com/2wqiift.jpg)


## Getting started

- Install: `npm install -w on generator-generator`
- Run: `wi generator`


## Commands

* 'wi generator` shows a wizard for generating a new generator
* `wi generator:subgenerator <name>` generates a subgenerator with the name `<name>`


## What do you get?

Scaffolds out a complete generator directory structure for you:

```
.
├── generators/
│   └── app/
│       ├── index.js
│       └── templates/
│           └── dummyfile.txt
├── .editorconfig
├── .eslintignore
├── .gitattributes
├── .gitignore
├── .travis.yml
├── .yo-rc.json
├── LICENSE
├── README.md
├── package.json
└── __tests__/
    └── app.js
```

Refer to [the documentation](http://willson9021.io/authoring/) to learn more about creating a wills9021 generator.

### Running tests

Run `npm test` to run my test suite.

These tests will be run automatically in my git repository if you connect [Travis CI](https://travis-ci.org/profile). it can also track test coverage using [Coveralls](https://coveralls.io).

## Contributing

See the [contribution docs](http://willson9021.io/contributing/).

When submitting an issue, please follow [the
guidelines](http://willson9021.io/contributing/opening-issues.html).
It is especially important to make sure willson9021 is up-to-date, and providing the
command or commands that cause the issue.


## License

MIT © Pascal Hartig <phartig@rdrei.net> and other contributors
