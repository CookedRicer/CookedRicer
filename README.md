# Notes
## React
---
- Setup
#### React Project
```
//CLI
npm init react-ts-template
yarn init
```
#### Tailwind
```
//CLI
yarn add -D tailwindcss
npx tailwindcss init

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

//daisyui (Tailwind base plugin)
yarn add -D daisyui@latest

//App.css
@tailwind base;
@tailwind components;
@tailwind utilities;
//
```
