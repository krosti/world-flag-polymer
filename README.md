# &lt;world-flag&gt;

Polymer component who aims standarize i18n information.

> Maintined by [Fernando Cea](http://github.com/krosti)
> [@krosti](http://twitter.com/krosti)
> [LinkedIn](http://ar.linkedin.com/in/fernandocea/)

> Contributors: [Karl Groves](https://github.com/karlgroves)

## Demo

[Check it live!](http://krosti.github.io/world-flag-polymer/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install world-flag-polymer --save
```

Or [download as ZIP](https://github.com/webcomponents/world-flag-polymer/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/world-flag-polymer/dist/world-flag.html">
    ```

3. Start using it!

    ```html
    <world-flag></world-flag>
    ```

## Options

Attribute           | Options                           | Default               | Description
---                 | ---                               | ---                   | ---
`language`          | *string*                          | `en`                  | Standard i18n short-name
`icon`              | *boolean*                         | `true`                | Icon visibility
`size`              | *string* 'small, medium, large'   | `''`                  | Icon size
`type`              | *boolean*                         | `''`                  | Icon display style

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Node](http://nodejs.org/)

2. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

4. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

5. To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

6. To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/world-flag-polymer/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) -
