
## What is it?
Always for every project I need to create styles for typography. I copy-paste code from a project in another. But I tired to do that. So I've created the CSS file that can help to simplify customization typography using the special settings.

## How use it
For using uia-typography you need to import the uia-typography.css file in your CSS file.
```css
@import 'uia-typography.css';
```
**Note:** Don't forget to use build systems so that the @import CSS at-rule doesn't get on production.

That's all. The default styles apply to elements. If you'd like to customize it you can use settings.
```css
@import 'uia-typography.css';

:root {
  --uiaTypographyHeadingFontFamily: 'Roboto Slab', serif;
  --uiaTypographyHeadingLineHeight: 1.5;
}
```
## Settings

| Option | Default |
| ----- | ----- |
| --uiaTypographyMainFontFamily | -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Open Sans, Ubuntu, Fira Sans, Helvetica Neue, sans-serif |
| --uiaTypographyMainFontSize | 1rem |
| --uiaTypographyMainTextColor | #222 |
| --uiaTypographyBasicMargin | 1em |
| --uiaTypographyLineHeight | 1.78 |
| --uiaTypographyLiMargin | .75em |
| --uiaTypographyHeadingMarginTop | 1em |
| --uiaTypographyHeadingMarginBottom | .25em |
| --uiaTypographyHeadingLineHeight | 1.78 |
| --uiaTypographyHeadingFontFamily | inherit |
| --uiaTypographyH1FontSize | 2.25rem |
| --uiaTypographyH2FontSize | 2rem |
| --uiaTypographyH3FontSize | 1.75rem |
| --uiaTypographyH4FontSize | 1.5rem |
| --uiaTypographyH5FontSize | 1.25rem |
| --uiaTypographyH6FontSize | 1rem |
| --uiaTypographyLinkColor | #5e4ef3 |
| --uiaTypographyImgDisplay | block |
| --uiaTypographyImgMaxWidth | 100% |
