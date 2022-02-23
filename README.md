# css-reset

Based on [Josh's Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) with input from [Chris Coyier](https://css-tricks.com/notes-on-josh-comeaus-custom-css-reset/), [Andy Bell](https://piccalil.li/blog/a-modern-css-reset/) and [Elad Shechter](https://css-tricks.com/an-interview-with-elad-shechter-on-the-new-css-reset/). (Via articles... not personally)

## What does it do?

It is a minimal, unopinionated, CSS reset that irons out some of the CSS qurirks before you start. Both the raw file and a version minified using PostCSS cssnano are available.

## How to use it?

The package name on NPM is '@jeclark/css-reset'.

### Using UNPKG

You can import the file into any HTML file using UNPKG with:

```html
<link rel="stylesheet" href="https://unpkg.com/@jeclark/css-reset/reset.css" />
```

Or for the minified version:

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/@jeclark/css-reset/reset.min.css"
/>
```

### Installing with NPM

Install the package and import before the regular styles of the project.

```html
<link rel="stylesheet" href="./node_modules/@jeclark/css-reset/reset.css" />
```

```html
<link rel="stylesheet" href="./node_modules/@jeclark/css-reset/reset.min.css" />
```

### In a React project

Install the package and insert it into the main entry file.

```js
import '@jeclark/css-reset/reset.css';
```

### Using SCSS

Import inside a file like index.scss or main.scss that imports all other css / scss files.

```css
@import './node_modules/@jeclark/css-reset/reset.css';
```

### Download the file

You can download the [CSS file](https://raw.githubusercontent.com/j-e-clark/css-reset/main/reset.css) or the [minified file](https://raw.githubusercontent.com/j-e-clark/css-reset/main/reset.min.css) and use it in your own project.
