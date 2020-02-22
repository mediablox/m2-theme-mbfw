# Magento 2 - MBFW theme

A bare bones Magento 2 Blank theme, which includes most of the template and xml files from magento/modul-theme ready for customisation.

## Installation
1. Clone this to your project to app/code/frontend/<vendor>/<theme>
2. Find and replace all references of 'mediablox' and 'mbfw' to your vendor and theme name
3. Set you application to `developer` mode
3. Run `bin/magento setup:upgrade` to register theme

## Usage Guidelines

In no particular order, the following set of rules are the current basis for how to work with this theme.

### Layouts

- Do not extend any layouts, instead copy the original file to the theme and edit as needed.

### CSS

- All css is to be compiled from scss. The scss source files are found under `src/scss'.
- To compile scss run the command `npm run styles`.
- CSS will be compiled as `main.css` in the `web/css` directory.