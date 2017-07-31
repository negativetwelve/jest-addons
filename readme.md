# jest-addons

Super-package of jest addons. Currently includes:

* jest-context
* jest-set

## Getting Started

Install `jest-addons` using `yarn`:

```shell
yarn add --dev jest-addons
```

## Usage

Add an entry to your jest configuration `setupFiles` in your `package.json`:

```json
"jest": {
  "setupFiles": [
    "jest-addons/setup"
  ]
}
```
