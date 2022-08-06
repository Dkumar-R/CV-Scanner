# CV-Scanner
### 🙏 Hello Viewers 🙏
**To build this website useing - HTML, JAVASCRIPT, Tailwindcss**
<h4>That is website link 👉 https://dkumar-r.github.io/CV-Scanner/</h4>
<hr>
<h4>Files of CV-Scanner website - https://github.com/Dkumar-R/CV-Scanner.github.io</h4>

**Create a folder Like - CV-Scanner**

<h2>I am using build up for this website Tailwindcss now First command</h2>

### (1) initialising a folder
```npm
npm init
```
** (2) Install tailwindcss and its peer dependencies via npm, and create your tailwind.config.js file**
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```
**(3) Add tailwindcss and autoprefixer to your postcss.config.js file, or wherever PostCSS is configured in your project.**
```js
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}
```
**(3) Add the paths to all of your template files in your tailwind.config.js file.**
```js
/** @type {import('tailwindcss').Config} */ 
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
**(4) Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.**
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
**(5) Install VITE**
```
npm install vite
```
**(6) Change script in json file**
```json
 "scripts": {
    "start": "vite",
    "build": "vite build"
  },
  ```
  **(7) Start using Tailwind in your HTML**
  **(8) complete your HTML file and run this command**
  ```
  npm run start
  ```
**(9) Start using Tailwind in your HTML**
**(10) Optimizing for Production**
```
npm run build
```
**you run this command in creating ***{dist}*** folder**
**And you see this type of error**
***<script src="/index.js"> in "/index.html" can't be bundled without type="module" attribute***

**please you can manually add index.html file many link**

**Previous** <(link) rel="stylesheet" href="/assets/index.d0f9c472.css">

**After** <(link) rel="stylesheet" href="assets/index.d0f9c472.css">

<img src="https://i.ibb.co/231R933/Screenshot-2022-08-05-142406.png" alt="Screenshot-2022-08-05-142406" border="0"></p>
