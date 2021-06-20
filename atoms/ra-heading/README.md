# The ra-heading

## Purpose
Reset h1-h6 elements' default styles

## How to use
Put the ra-heading.css file into your CSS file before other styles

```css
@import 'ra-heading.css';

/* other styles */
```

If you want to change settings you should declare the :root pseudo-class and set new values

```css
@import 'ra-heading.css';

:root {
  --ra-heading-margin-block-start: 1rem;
  --ra-heading-margin-block-end: 1rem;
}

/* other styles */
```

## Settings
| Name | Description | Default |
| ----- | ----- | ----- |
| --ra-heading-margin-block-start | the gap before the element | 0 |
| --ra-heading-margin-block-end | the gap after the element | 0 |

## Dependencies
The atom has no dependencies

## Research alternatives
The atom has no research alternatives

## Resources
The atom has no resources

## Test cases
1. You should ensure all settings of the atom might be changed
2. You should ensure that if the heading is the first element inside of the parent its margin-top is reset
3. You should ensure that if the heading is the last element inside of the parent its margin-bottom is reset
