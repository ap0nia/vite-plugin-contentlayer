# vite-plugin-contentlayer

Vite integration for Contentlayer!

## Getting Started

1. Install the package.

```bash
npm install vite-plugin-contentlayer
```

2. Use the vite plugin in `vite.config.js`.

```ts
import { defineConfig } from 'vite'
import contentlayer from 'vite-plugin-contentlayer'

const config = defineConfig({
  plugins: [contentlayer()],
})

export default config
```
