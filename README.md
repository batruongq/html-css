# Learning HTML/CSS

## Setup husky, lint-stage, stylelint

### [stylelint](https://github.com/stylelint/stylelint) 
Modern linter that helps you avoid errors and enforce conventions in your styles.

#### 1. [stylelint-config-standard] https://github.com/stylelint/stylelint-config-standard/blob/main/index.js
The standard shareable config for Stylelint
How to setup
- `npm install --save-dev stylelint stylelint-config-standard`
- Create a configuration file `.stylelintrc` or `.stylelintrc.json` in the root of your project
  <pre>
  { 
    "extends": "stylelint-config-standard" 
  }
  </pre>

#### 2. [stylelint-order] https://github.com/hudochenkov/stylelint-order
A plugin pack of order-related linting rules for Stylelint
How to setup
- `npm install stylelint-order --save-dev`

### simple-git-hooks
