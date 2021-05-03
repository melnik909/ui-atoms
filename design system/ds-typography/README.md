
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
