# Flag

The `flag` object module is an object similar in appearance to
[the media object](https://github.com/treeframework/object.media), but which
provides slightly more advanced functionality.

## Dependencies

The `flag` object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `flag` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Instalation

You can install the `flag` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-flag --save
```

### Install using npm:

```sh
$ npm install tree-flag --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.flag.scss` into your project and `@import` it into your project in
its Objects layer.

## Usage

Basic usage of the `flag` object uses the required classes:

```html
<div class="o-flag">
    <div class="o-flag__img">
        <img class="o-flag__img src="/path/to/image.png" alt="" />
    </div>
    <div class="o-flag__body">
        <p>Text-like content goes here.<p>
    </div>
</div>
```

The only valid children of the `.o-flag` node are `.o-flag__img` and
`.o-flag__body`.

## Options

## Options

Other, optional classes can supplement the required base classes:

* `.o-flag--[tiny|small|large|huge]`: alter the spacing between the image- and
  text-content.
* `.o-flag--rev`: reversed flag objects have their image-content to the right,
  and text-content to the left.
* `.o-flag--flush`: no space between image- and text-content.
* `.o-flag--[top|bottom]`: align object to top or bottom.
* `.o-flag--responsive`: a very basic responsive implementation of the flag object.

For example:

```html
<div class="o-flag  o-flag--flush">
    <div class="o-flag__img">
        <img class="o-flag__img src="/path/to/image.png" alt="" />
    </div>
    <div class="o-flag__body">
        <p>Text-like content goes here.<p>
    </div>
</div>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
