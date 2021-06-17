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
  --ra-heading-margin-top: 1rem;
  --ra-heading-margin-bottom: 1rem;
}

/* other styles */
```

## Settings
| Option | Description | Default |
| ----- | ----- | ----- |
| --ra-heading-margin-top | The value for the margin-top property | 0 |
| --ra-heading-margin-bottom | The value for the margin-bottom property | 0 |

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
