<a name="user-content-eslint-plugin-zod"></a>
<a name="eslint-plugin-zod"></a>
# eslint-plugin-zod

[![Canonical Code Style](https://img.shields.io/badge/code%20style-canonical-blue.svg?style=flat-square)](https://github.com/gajus/canonical)
[![NPM version](http://img.shields.io/npm/v/eslint-plugin-zod.svg?style=flat-square)](https://www.npmjs.org/package/eslint-plugin-zod)
[![Twitter Follow](https://img.shields.io/twitter/follow/kuizinas.svg?style=social&label=Follow)](https://twitter.com/kuizinas)

[Zod](https://github.com/colinhacks/zod) linting rules for ESLint.

* [eslint-plugin-zod](#user-content-eslint-plugin-zod)
    * [Installation](#user-content-eslint-plugin-zod-installation)
    * [Configuration](#user-content-eslint-plugin-zod-configuration)
    * [Rules](#user-content-eslint-plugin-zod-rules)
        * [`require-strict`](#user-content-eslint-plugin-zod-rules-require-strict)


<a name="user-content-eslint-plugin-zod-installation"></a>
<a name="eslint-plugin-zod-installation"></a>
## Installation

1. Install [ESLint](https://www.github.com/eslint/eslint).
1. Install [`eslint-plugin-zod`](https://github.com/gajus/eslint-plugin-zod) plugin.

<!-- -->

```sh
npm install eslint --save-dev
npm install eslint-plugin-zod --save-dev
```

<a name="user-content-eslint-plugin-zod-configuration"></a>
<a name="eslint-plugin-zod-configuration"></a>
## Configuration

1. Add `plugins` section and specify `eslint-plugin-zod` as a plugin.
1. Enable rules.

<!-- -->

```json
{
  "plugins": [
    "zod"
  ],
  "rules": {
    "zod/require-strict": [
      2,
    ],
  }
}

```

<a name="user-content-eslint-plugin-zod-rules"></a>
<a name="eslint-plugin-zod-rules"></a>
## Rules

<!-- Rules are sorted alphabetically. -->

<a name="user-content-eslint-plugin-zod-rules-require-strict"></a>
<a name="eslint-plugin-zod-rules-require-strict"></a>
### <code>require-strict</code>

_The `--fix` option on the command line automatically fixes problems reported by this rule._

Requires that objects are initialized with `.strict()`.



