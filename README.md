# style-guide

Eleven James Style Guide

## Setup & Run Guide
- Install Git
- Install Node JS
- Install NPM packages: ``npm install``
- Install Less globally: ``npm install -g less``
- Install DocumentCSS globally: ``npm install -g documentjs``
- Compile Less: main styles: ``lessc styles/styles.less styles/styles.css``
- Compile Less: documentation styles: ``lessc styles/style-guide.less styles/style-guide.css``
- Run DocumentCSS to generate a documentation: ``documentjs -w``
- Run ``docs/index.html`` file to see the documentation


## CSS Syntax

Use classes. **Do not** use IDs.

Classes should be hyphen delimited. No `under_score` or `camelCase` should be used.

Naming follows the BEM conventions:

* **Block:** the sole root of the component.
* **Element:** a component of the Block. Delimited with 2 underscores (`__`).
* **Modifier:** a variant or extension of Block/Element. Delimited by 2 hyphens (`--`).