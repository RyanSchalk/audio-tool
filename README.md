### :construction_worker: In Progress :construction_worker:

# audio-tool

## A lightweight audio custom web component

<p align="center">
 <a>
   [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
 </a>
 <a href="https://www.npmjs.com/package/prettier">
    <img alt="npm version" src="https://img.shields.io/npm/v/prettier.svg?style=flat-square">
 </a>
 <a>
   [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)
 </a>
</p>

## Live Demo

Check out a live demo [here.](http://www.kevinmlogan.com/audio-tool/)

## Install

```
npm install audio-tool
```

## How to use

1. Inject in the script through a script tag in the HEAD of your index.html.

```
<script src="node_modules/audio-tool.js"></script>
```

2. Start using it in an html file.

```
<audio-tool src="content/ff7-prelude.m4a" title="FF7 Prelude" auto-play="false"></audio-tool>
```

## PollyFill

Using a browser that doesn't natively support custom web components?

Add the following to the HEAD of your index.html.

```
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

## Responsiveness

Add the following meta tag for responsiveness across all devices.

> This tag is not specific to this component. This is required for any app to understand the screen size in mobile browsers.

```
<meta name="viewport" content="width=device-width,initial-scale=1.0" />
```

## Customizations

| Attribute | Options |                 Description                  |           Default           |
| :-------: | :-----: | :------------------------------------------: | :-------------------------: |
|    src    | string  |         the path to your audio file          |            none             |
|   title   | string  |           Define the track title.            | The path to your audio file |
| auto-play | boolean | Automatically start playing the track onload |

## Specs

|:--:|:--:|
|CSS Grid||
|No Shadow DOM||
|es5+ transpiled down to es5||
|customElement.define() native function|
|[Material UI SVG Icons](https://www.materialui.co/icons)|

## License

[MIT License](https://github.com/kevinlogan94/audio-tool/blob/master/README.md)
https://icons8.com/icons/set/pause
css-grid

Helpful links
https://stackoverflow.com/questions/47960743/html-audio-object-reporting-wrong-file-duration?rq=1
https://stackoverflow.com/questions/6312993/javascript-seconds-to-time-string-with-format-hhmmss
http://jonraasch.com/blog/javascript-style-node

TODO:
Add polyfill recommendation for browsers that don't support customElements.define().
https://stackoverflow.com/questions/40677265/how-to-get-custom-elements-working-in-firefox
