# @intouchg/stylelint-config

Stylelint configuration for the [Intouch Design System](https://ids.intouchg.co/)

## Getting Started

To use in your own custom configuration, install then extend this package in your Stylelint config:

1. Install dependencies
```sh
yarn add --dev @intouchg/stylelint-config stylelint-config-standard-scss stylelint-config-prettier stylelint-config-idiomatic-order stylelint-order stylelint
```

2. Configure Stylelint
```jsonc
// .stylelintrc
{
    "extends": ["@intouchg/stylelint-config"]
}
```
