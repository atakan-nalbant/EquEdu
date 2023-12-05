---
Date: Monday 11-13-2023 | 11:08:55
Updated at: Monday 11-13-2023 | 11:08:58
---

# Introduction To Vite
Our React application will get loaded into
```html
<div id="root">Welcome to EquEdu!</div>
```
inside the index.html file. The React application will replace what is inside this root div.

The `createRoot` is placed inside the /src/main.tsx. React is running with Strict mode. 

The content we are seeing when we first launch the application is located at /src/App.tsx We start from scratch in this project, hence /src/index.css & App.css are cleared completely.

vite.config.ts includes the configuration for Vite. 
- To make the server launch on port 3000, we add a server property:
```tsx
server:{
    port: 3000
}
```

tsconfig.json is for the Typescript configuration. We are using strict mode to see all errors and do things the proper way.

Static images etc. will be added inside the public folder.