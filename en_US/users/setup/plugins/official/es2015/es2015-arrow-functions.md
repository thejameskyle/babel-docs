# ES2015 Arrow Functions

### Installation

```sh
$ npm install --save-dev babel-plugin-es2015-arrow-functions
```

### Usage

#### Via `.babelrc` (recommended)

**`.babelrc`**

```json
{
  "plugins": ["es2015-arrow-functions"]
}
```

#### Via CLI

```sh
babel script.js --plugin es2015-arrow-functions
```

#### Via Node API

```js
require("babel-core").transform("code", {
  plugins: ["es2015-arrow-functions"]
});
```