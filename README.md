# SCSS Mixin Placeholder

A package for integrating a mixin for styling input field placeholders.

![npm](https://img.shields.io/npm/v/@m2collective/scss-mixin-placeholder?style=for-the-badge)

___

## Installation

You can install the package automatically using NPM:

```
npm i @m2collective/scss-mixin-placeholder
```

## Usage

To use the package, import it into your project:

```scss
@use "@m2collective/scss-mixin-placeholder" as *;
```

```scss
.demo {
    @include placeholder {
        color: #000;
        font-size: 14px;
        font-weight: 400;
    }
}

// Return

.demo::-webkit-input-placeholder {
    color: #000;
    font-size: 14px;
    font-weight: 400;
}

.demo::-moz-placeholder {
    color: #000;
    font-size: 14px;
    font-weight: 400;
}

.demo:-ms-input-placeholder {
    color: #000;
    font-size: 14px;
    font-weight: 400;
}

.demo:-moz-placeholder {
    color: #000;
    font-size: 14px;
    font-weight: 400;
}

.demo::placeholder {
    color: #000;
    font-size: 14px;
    font-weight: 400;
}
```

## Changing the namespace

You can change the namespace during mixin import and use the mixin with a different namespace:

```scss
@use "@m2collective/scss-mixin-placeholder" as mixin;
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
