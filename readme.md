
# Template di webpack con partials e un template engine

> Template di webpack con partials e un template engine, per produrre velocemente pagine web che siano riusabili in angular.io

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## Prerequisites

This project requires NodeJS and NPM.
[Node](http://nodejs.org/) and [NPM](https://npmjs.org/)

## Table of contents

- [Template di webpack con partials e un template engine](#template-di-webpack-con-partials-e-un-template-engine)
    - [Prerequisites](#prerequisites)
    - [Table of contents](#table-of-contents)
    - [Getting Started](#getting-started)
        - [Installation](#installation)
    - [Usage](#usage)
        - [Serving the app](#serving-the-app)
        - [Unit teststing](#unit-teststing)
        - [Building a distribution version](#building-a-distribution-version)
        - [Serving the distribution version](#serving-the-distribution-version)
    - [Contributing](#contributing)
    - [Credits](#credits)
    - [Built With](#built-with)
    - [Versioning](#versioning)
    - [Authors](#authors)
    - [License](#license)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation

**BEFORE YOU INSTALL:** please read the [prerequisites](#prerequisites)

Start with cloning this repo on your local machine:

```sh
$ git clone https://github.com/ORG/PROJECT.git
$ cd PROJECT
```

Then install all the Node dependencies usin npm or Yarn

```sh
$ npm install
```

Or using Yarn

```sh
$ yarn
```

## Usage

### Serving the app

```sh
$ npm start
```

### Unit teststing

```sh
$ npm test
```

### Building a distribution version

```sh
$ npm run build
```

This task will create a distribution version of the project
inside your local `dist/` folder

### Serving the distribution version

```sh
$ npm run serve:dist
```

This will use `lite-server` for servign your already
generated distribution version of the project.

*Note* this requires
[Building a distribution version](#building-a-distribution-version) first.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

1.  Fork it!
1.  Create your feature branch: `git checkout -b my-new-feature`
1.  Add your changes: `git add .`
1.  Commit your changes: `git commit -am 'Add some feature'`
1.  Push to the branch: `git push origin my-new-feature`
1.  Submit a pull request :sunglasses:

## Credits

TODO: Write credits

## Built With

* Dropwizard - Bla bla bla
* Maven - Maybe
* Atom - ergaerga
* Love

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **John Doe** - *Initial work* - [JohnDoe](https://github.com/JohnDoe)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

[MIT License](https://andreasonny.mit-license.org/2017-2018) © Andrea SonnY

```