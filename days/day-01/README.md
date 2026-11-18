# Day 1 — Setup & Hello World 👋

## 📖 Theory (45 min)

### What is JavaScript?

JavaScript is the programming language of the web. It runs in every browser
and lets you make pages interactive: react to clicks, fetch data, animate things.

### How to run JS code

There are three common ways:

1. **Browser console** — open DevTools with `F12` (or right-click → Inspect → Console tab)
   and type code directly:

   ```js
   console.log("Hello, JavaScript!");
   ```

2. **Inline in HTML**:

   ```html
   <button onclick="console.log('clicked!')">Click me</button>
   ```

3. **External script file** (the best practice — this is what we'll use):

   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <meta charset="UTF-8" />
     <title>Day 1</title>
   </head>
   <body>
     <!-- script goes at the end of body so the HTML is loaded first -->
     <script src="script.js"></script>
   </body>
   </html>
   ```

### `console.log()` — your best friend

It prints values to the console. You'll use it constantly to check what your code does:

```js
console.log("a string");
console.log(42);
console.log(true);
```

## ✏️ Exercise

Open `script.js` and complete these tasks:

1. Print your name to the console.
2. Print your age (a number).
3. Print the result of `10 + 5`.
4. Add your own `console.log` with something fun.

## ✅ Self-check

- [ ] I can open the browser console
- [ ] I created an HTML page with an external `script.js`
- [ ] My script prints at least 4 things to the console

**Tomorrow:** Variables & Constants — `let` vs `const`.
