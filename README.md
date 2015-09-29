# &lt;paper-fab-speed-dial&gt;

Polymer This element is designed to be used by wrapping a group of paper-fab to obtain a speed-dial.



## Demo

[Check it live!](http://GNURub.github.io/paper-fab-speed-dial/demo)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install paper-fab-speed-dial --save
```

Or [download as ZIP](https://github.com/GNURub/paper-fab-speed-dial/archive/master.zip).


## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/paper-fab-speed-dial/paper-fab-speed-dial.html">
    ...
    <link rel="import" href="bower_components/paper-fab/paper-fab.html">
    ```

3. Start using it!  
    ```html
    <paper-fab-speed-dial up|left|down|right>
      <paper-fab icon="accessibility" main></paper-fab>
      <paper-fab icon="alarm"         mini></paper-fab>
      <paper-fab icon="shop"          mini></paper-fab>
    </paper-fab-speed-dial>
    ```


## Options

Attribute         | Options     | Default      | Description
---               | ---         | ---          | ---
up                | Boolean     | true         | up position
right             | Boolean     | false        | right position
down              | Boolean     | false        | down position
left              | Boolean     | false        | left position


## License

[MIT License](http://opensource.org/licenses/MIT)
