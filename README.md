# &lt;x-instagram&gt;

A [Polymer](http://polymer-project.org) element for querying results from the [Instagram API](http://instagram.com/developer/)

> Maintained by [Addy Osmani](https://github.com/addyosmani).

## Demo

> [Check it live](http://addyosmani.github.io/x-instagram).

## Install

Using [Bower](http://bower.io), run:

```bash
$ bower install --save x-instagram
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="src/x-instagram.html">
```

3. Start using it!

```html
<x-instagram><x-instagram>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [Node.js](http://nodejs.org/download/)
2. Install [Grunt](http://gruntjs.com/):

```sh
$ npm install -g grunt-cli
```

3. Install local dependencies:

```sh
$ npm install
```

4. Run a local server and open `http://localhost:8000`.

```sh
$ grunt connect
```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`tag`      | *string*                  | ``               | The tag to query for (e.g 'selfie')
`count`      | *integer*       | `30`               | The max number of results to return
`photosPerRow`      | *integer*       | `10`               | The number of photos that will show up on a row
`clientId`   | *string*                     | See source               | An Instagram API developer client Id

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
