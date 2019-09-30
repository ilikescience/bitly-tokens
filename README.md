# Bitly Style Tokens

This repo contains all of Bitly's style tokens.

### What are style tokens?

Style tokens (sometimes called design tokens) are low-level specifications for design decisions. They can be used to maintain consistency accross multiple platforms and applications. More info can be found [here](https://css-tricks.com/what-are-design-tokens/).

## Installation

To install Bitly's style tokens via npm, run the following:

```
npm install bitly-tokens --save
```

## Usage

### Javascript

In Javascript, all tokens are available via the `tokens` object.

```
import tokens from "bitly-tokens";
console.log(tokens.color.blue.50);
```

### SCSS

```
// Using variables
@import '~bitly-tokens/dist/scss/_variables';
```

### CSS

```
// Custom properties
@import '~bitly-tokens/dist/css/_variables.css';
```
