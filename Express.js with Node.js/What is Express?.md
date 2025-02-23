# Express Framework Notes

## Introduction
- **Express** is a framework built on top of **Node.js** to help create backends with ease.
- It ranks high among professional developers.
- Used widely due to its simplicity and effectiveness.

## Node.js vs Express.js
- **Node.js** is a **runtime environment**, not a framework.
  - Allows running JavaScript outside the browser.
  - Can be used for various tasks like web development, IoT, and desktop applications.
  - Example: **VS Code** is built using Node.js.
- **Express.js** is a **framework** specifically designed for building backends.
  - Makes backend development easier and more efficient.

## Why Use Express?
- **Node.js is too general-purpose**
  - Can be used for many things, but lacks a specialized focus for backend development.
  - Analogy: Node.js is a **Phillips screwdriver**, while Express is an **electric screwdriver** that makes backend development easier.
- **Code Simplicity & Readability**
  - Using plain Node.js for a simple website requires a lot of code.
  - Express reduces complexity and makes code more modular.

## Example: Creating a Simple Website
- **Using Node.js** (complicated and verbose)
- **Using Express** (cleaner and more modular)

```javascript
const express = require('express');
const app = express();

app.get('/', (req, res) => {
    res.send('Welcome to the Homepage!');
});

app.get('/about', (req, res) => {
    res.send('About Us');
});

app.listen(3000, () => {
    console.log('Server is running on port 3000');
});
```

## Advantages of Express
- **Better Readability**
- **Less Code to Write**
- **Middleware Support**
  - Acts like **Lego blocks**, allowing easy feature addition.
- **Widely Used in the Industry**
  - Backed by statistics from the **State of JavaScript** report.
  - Preferred choice among professional developers.

## Conclusion
- Express is the **best choice** for backend development with Node.js.
- It simplifies the process and improves productivity.
- Most professional developers **always use Express** when working with Node.js.
