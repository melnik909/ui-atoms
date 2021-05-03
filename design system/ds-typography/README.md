
## What is it?
Always for every project I need to create styles for typography. I copy-paste code from a project in another. But I tired to do that. So I've created the CSS file that can help to simplify customization typography using the special settings.

## How use it
For using uia-typography you need to import the ds-typography.css file in your CSS file.
```css
@import 'ds-typography.css';
```
**Note:** Don't forget to use build systems so that the @import CSS at-rule doesn't get on production.

That's all. The default styles apply to elements. If you'd like to customize it you can use settings.
```css
@import 'ds-typography.css';

:root {
  --ds-typography-heading-font-family: 'Roboto Slab', serif;
  --ds-typography-heading-line-height: 1.5;
}
```
## Settings

| Option | Default |
| ----- | ----- |
| --ds-typography-main-font-family | -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Open Sans, Ubuntu, Fira Sans, Helvetica Neue, sans-serif |
| --ds-typography-main-font-size | 1rem |
| --ds-typography-main-color | #222 |
| --uiaTypographyBasicMargin | 1em |
| --uiaTypographyLineHeight | 1.78 |
| --ds-typography-list-item-margin | .75em |
| --ds-typography-heading-margin-top | 1em |
| --ds-typography-heading-margin-bottom | .25em |
| --ds-typography-heading-line-height | 1.78 |
| --ds-typography-heading-font-family | inherit |
| --ds-typography-h1-font-size | 2.25rem |
| --ds-typography-h2-font-size | 2rem |
| --ds-typography-h3-font-size | 1.75rem |
| --ds-typography-h4-font-size | 1.5rem |
| --ds-typography-h5-font-size | 1.25rem |
| --ds-typography-h6-font-size | 1rem |
| --ds-typography-link-color | #5e4ef3 |
| --ds-typography-img-display | block |
| --ds-typography-img-max-width | 100% |
