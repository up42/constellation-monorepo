# Constellation Tokens

This project holds the design system tokens. We are using `style-dictionary` to compile our styles into different formats.

## Usage

We currently export tokens in 2 formats: `scss` and `json`. In order to include them in your products, you can use:

```js
import tokens from '@up42/constellation-tokens/dist/json/tokens.json'
```

Or in `scss`

```scss
@import '@up42/constellation-tokens/dist/scss/tokens';
```

Also `css` variables available at `dist/css/tokens.css`

### Tokens (properties)

Tokens live under `properties/` and are organized using [CTI structure](https://amzn.github.io/style-dictionary/#/properties?id=category-type-item).

### More Information

For more information please refer to style-dictionary [documentation](https://amzn.github.io/style-dictionary/)

Have a nice day.
