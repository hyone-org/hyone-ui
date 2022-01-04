<h1 align="center">Welcome to HyONE-UI!</h1>

HyONE-UI - Library write in Vue 3 that will assist you in your project, 
providing visual components to facilitate the development of your application.

### Installation

```
# If you use npm: 
npm i @hyone/hyone-ui
# Or if you use Yarn: 
yarn add @hyone/hyone-ui
```

### Use

After installing, add HyONEPlugin to your vue instance.

- In main js:
```js
import { createApp } from 'vue';
import '@hyone/hyone-ui/dist/hyone-ui.css';
import { HyONEPlugin } from '@hyone/hyone-ui';
import App from './app.vue'

createApp
  .use(HyONEPlugin)
  .mount('#root');
```

- In template:

```html
<template>
  <AButton>Foi</AButton>
</template>
```

### Live documentation
[HyONE-UI Doc](https://hyone-ui.netlify.app/)
### Contributing

Guides:
[Click here, and discovery how to develop](docs/CONTRIBUTING.md)
