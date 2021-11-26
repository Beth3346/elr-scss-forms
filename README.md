# elr-scss-forms

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-forms.svg?style=flat)](https://npmjs.com/package/elr-scss-forms)

a library of sass mixins

[View Demo](https://elr-scss-forms.netlify.app/)

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-forms --save
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

## License

SEE LICENSE IN LICENSE.md
