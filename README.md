# SassFrame

SassFrame is a lightweight CSS framework built with Sass and Sass partials. It provides a consistent theme for common HTML elements, reusable components, layout classes, and utility classes.

## Features

* Sass variables and partials
* Typography styles
* Buttons
* Forms and inputs
* Lists
* Tables
* Cards
* Grid and Flexbox layouts
* Color utilities
* Font-size and font-weight utilities
* Margin utilities
* Compiled CSS files for development and production

## Installation

Clone the repository:

```bash
git clone https://github.com/zhan0832/mtm6407-sassframe.git
```

Open the project folder:

```bash
cd mtm6407-sassframe
```

Install the required dependencies:

```bash
npm install
```

## Usage

Add the compiled stylesheet to the `<head>` of your HTML file:

```html
<link rel="stylesheet" href="css/sassframe.css">
```

### Buttons

```html
<button class="btn-primary">Primary Button</button>
<button class="btn-secondary">Secondary Button</button>
<button class="btn-success">Success Button</button>
<button class="btn-danger">Danger Button</button>
```

### Text and background colors

```html
<p class="text-primary">Primary text</p>
<p class="text-danger">Danger text</p>

<div class="bg-warning">Warning background</div>
<div class="bg-success">Success background</div>
```

### Typography utilities

```html
<p class="font-bold">Bold text</p>
<p class="font-black">Black weight text</p>
<p class="text-xl">Extra-large text</p>
```

### Margin utilities

```html
<div class="margin-md">Medium margin</div>
<div class="margin-top-lg">Large top margin</div>
<div class="margin-bottom-sm">Small bottom margin</div>
```

### Grid layout

```html
<div class="grid grid-3">
  <div class="card">Card One</div>
  <div class="card">Card Two</div>
  <div class="card">Card Three</div>
</div>
```

### Table

```html
<table class="table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SassFrame</td>
      <td>A custom CSS framework built with Sass.</td>
    </tr>
  </tbody>
</table>
```

## Development

Run the Sass watcher while editing the framework:

```bash
npm run dev
```

This compiles:

```text
src/sassframe.scss
```

into:

```text
css/sassframe.css
```

To create the compressed production build, run:

```bash
npm run build
```

This generates:

```text
dist/sassframe.css
```

The compiled CSS files are included in the repository.

## Customization

The framework can be customized by editing the Sass files inside the `src` folder.

Colors can be changed in:

```text
src/variables/_colors.scss
```

Typography can be changed in:

```text
src/variables/_typography.scss
```

Margin values can be changed in:

```text
src/variables/margins.scss
```

Component styles can be edited in:

```text
src/components/
```

After making changes, run:

```bash
npm run dev
```

Do not edit `css/sassframe.css` directly because it is generated from the Sass source files.

## Demo

Open `index.html` in a browser to view examples of the framework.

## Team Members

* Yan Zhang
* Hui Chen
* Harsh Kumar
