# ES2015 Literals

Compile ES2015 unicode string and number literals to ES5

## Example

**Input**

```js
0b10
"\u000A"
```

**Output**

```js
2
"\n"
```

> Note that the output may not be exactly what is above. Babel's implementation
> may have changed since this document was last updated, or the output may have
> been cleaned up for clarity.

## Setup

### Installation

```sh
$ npm install --save-dev babel-plugin-transform-es2015-literals
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["transform-es2015-literals"]
}
```

#### Via CLI

```sh
babel script.js --plugin transform-es2015-literals
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["transform-es2015-literals"]
});
```
