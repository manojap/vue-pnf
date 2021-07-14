# vue-pnf

This Vue library consisting of one or more component for showing Page Not Found / 404.

[Demo]()

[![NPM](https://img.shields.io/npm/v/@codehat/vue-404.svg)](https://www.npmjs.com/package/@codehat/vue-404) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

<img src="./404.png"/>

## Installation

```bash
npm i --save @codehat/vue-404
```
## Components

This library includes following components

* **Animated**, an animate 404 Page with CSS animation

## Usage

```javascript
<template>
  <div class="home">
    <v-404/>     
  </div>
</template>
<script>

 import { Animated } from "@codehat/vue-404";
export default {  
  components: {
 "v-404": Animated,    
  },
};
</script>

```

## License

MIT © [manojap](https://github.com/manojap)