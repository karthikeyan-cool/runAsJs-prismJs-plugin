[![](https://data.jsdelivr.com/v1/package/npm/runasjs-prismjs-plugin/badge)](https://www.jsdelivr.com/package/npm/runasjs-prismjs-plugin)

# runAsJs-PrismJS-Plugin
This is a [prismjs](https://github.com/PrismJS/prism) plugin that runs the javascript inside the code block and displays the output.

# Demo

## Video:

https://user-images.githubusercontent.com/70737008/187843491-a848e22c-b5b2-41bb-8776-942750bac16d.mp4

## Working Example:

https://karthikeyan-cool.github.io/runAsJs-prismJs-plugin/demo/

# How To Use

- The build files are present in [dist](./dist) folder.
- There will be two folders one is prismjs build and runAsJs build files.
- For runAsJs plugin to work, you need have the following:
  - [Prism js](https://github.com/PrismJS/prism)
  - [Prism js toolbar plugin](https://github.com/PrismJS/prism/tree/master/plugins/toolbar)
  - [Prims js show language (optional) ](https://github.com/PrismJS/prism/tree/master/plugins/show-language)

# Styling

- **customTheme.css** file controls the hover state color of toolbar and left and right margin of the toolbar buttons.
- **runAsJs.css** file controls the output section theme.

# How to build

- To build from source, use the following commands

```shell
npm install
npm run build
```

# How to install

[NPM:](https://www.npmjs.com/package/runasjs-prismjs-plugin)

```shell

npm i runasjs-prismjs-plugin

```

[YARN:](https://yarn.pm/runasjs-prismjs-plugin)

```shell
yarn add runasjs-prismjs-plugin
```

## CDN:

- [jsdelivr](https://www.jsdelivr.com/package/npm/runasjs-prismjs-plugin/) (Format: https://cdn.jsdelivr.net/npm/runasjs-prismjs-plugin@VERSION)

```
https://cdn.jsdelivr.net/npm/runasjs-prismjs-plugin@1.0.0
```

- [unpkg](https://unpkg.com/browse/runasjs-prismjs-plugin/) (Format: https://unpkg.com/browse/runasjs-prismjs-plugin@VERSION/)

```shell
https://unpkg.com/runasjs-prismjs-plugin@1.0.0/dist/runAsJs/js/runAsJs.min.js
```

for issues see [issues section](https://github.com/karthikeyan-cool/PrismJs-plugin-runJavascript/issues);
