### npm i react-redux @reduxjs/toolkit @heroicons/react react-router-dom react-dropzone react-chat-engine-advanced

### npm i -d sass

### DOCS

- https://rest.chatengine.io/
- https://chatengine.io/docs/react/v2/overview
- chatengine storybook: https://chatengine-io.github.io/react-chat-engine-advanced/?path=%2Fdocs%2Fmultichatwindow--default-story

### npm i -D eslint eslint-config-react-app

- set up - eslint

```js
{ "extends": "react-app" }

```

### npm i -d @types/node

- Handle relative path

```
import { defineConfig } from "vite";
import react from "@vitejs/plugin-react";
import path from "path";

// https://vitejs.dev/config/
export default defineConfig({
  plugins: [react()],
  resolve: {
    alias: [{ find: "@", replacement: path.resolve(__dirname, "src") }],
  },
});

```

### Handle .env.local

`import.meta.env.VITE_PROJECT_ID`
