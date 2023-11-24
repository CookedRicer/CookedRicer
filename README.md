# Notes
## React
---
- Setup
#### React Project
```js
//CLI
npm init react-ts-template
yarn init
touch .prettierrc
```
#### Install TailwindCSS
```js
//CLI
yarn add -D tailwindcss
npx tailwindcss init
```
```js
//tailwind.config.js
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  //if using 'daisyui' lib
  plugins: [require("daisyui")],
  daisyui: {
    themes: ["light", "dark"],
  },
};
```
```css
/* App.css **/
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Install Daisyui 
##### (Tailwind base plugin) [OPTIONAL]
```js
yarn add -D daisyui@latest
```

