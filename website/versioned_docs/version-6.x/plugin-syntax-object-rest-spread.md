---
id: version-6.x-babel-plugin-syntax-object-rest-spread
title: babel-plugin-syntax-object-rest-spread
sidebar_label: syntax-object-rest-spread
original_id: babel-plugin-syntax-object-rest-spread
---

## Installation

```sh
npm install --save-dev babel-plugin-syntax-object-rest-spread
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["syntax-object-rest-spread"]
}
```

### Via CLI

```sh
babel --plugins syntax-object-rest-spread script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["syntax-object-rest-spread"]
});
```

