# pizza-background

> fill the background of an element with pizza

## Install

Available via npm:

```
npm i --save pizza-background
```

## Usage 

Include in your css with an `@import` statement:

```css
@import "pizza-background";
```

Bundle your css dependencies with a tool like sheetify:

```
npm i --save-dev sheetify
```

Create a bundle-css script in your package.json file:

```json
"scripts": {
  "bundle-css":  "sheetify style.css > bundle.css"
}
```

Add your bundled css to your html:

```html
<link href="bundle.css" rel="stylesheet">
```

Use the `pizza` class:

```
<body class="pizza"></body>
```

Sidenote: make sure the element & its parent elements have a width and height.

## License
MIT