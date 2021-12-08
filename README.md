# Forms

[![npm version](http://img.shields.io/npm/v/elr-scss-forms.svg)](https://www.npmjs.org/package/elr-scss-forms)
[![Build Status](https://github.com/elr-scss-forms/workflows/CI/badge.svg)](https://github.com/elr-scss-forms/actions?workflow=CI)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-forms.svg?style=flat)](https://npmjs.com/package/elr-scss-forms)

a library of sass mixins

[View Demo](https://elr-scss-forms.netlify.app/)

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-forms
```

or

```sh
yarn add elr-scss-forms
```

## Implementation

```scss
@import "elr-scss-form/src/main";

.form {
  @include elr-form;
}
```

### Basic Form

```html
<form class="form">
  <div class="form-row">
    <div class="input-group">
      <label for="fav-animal">Favorite Animal</label>
      <div class="input-wrapper">
        <span class="input-icon"><i class="fa fa-lock"></i></span>
        <input id="fav-animal" type="text" placeholder="penguins" />
      </div>
      <small class="input-helper-text">This is some helper text</small>
    </div>
    <div class="input-group">
      <label for="fav-place">Favorite Place</label>
      <div class="input-wrapper">
        <input id="fav-place" type="text" placeholder="Italy" />
      </div>
    </div>
  </div>
  <div class="form-buttons">
    <button type="submit" class="button">Submit</button>
  </div>
</form>
```

## TODO

- inline form
- form states (loading, ready, error, submitted)
- form input error states

## License

SEE LICENSE IN LICENSE.md
