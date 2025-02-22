# Learning the Node Package Manager (NPM)

## What is NPM?

NPM (Node Package Manager) is a place where developers share and manage open-source Node modules. It allows you to install and use tools created by other developers to enhance your Node.js applications.

Think of it as a shared community toolbox where developers contribute useful utilities and tools.

## Initializing an NPM Project

1. Open your terminal and navigate to your project folder:
   ```sh
   cd your-project-folder
   ```
2. Run the following command to initialize NPM:
   ```sh
   npm init
   ```
3. Follow the prompts to create a `package.json` file.

## Installing an NPM Package

To install a package, use:
```sh
npm install package-name
```
Or, shorthand:
```sh
npm i package-name
```

### Example: Installing the `sillyname` Package
```sh
npm i sillyname
```
After installation, check `package.json` to see the added dependency.

## Using an NPM Package in Your Project

1. Require the package in your `index.js` file:
   ```javascript
   import generateName from 'sillyname';
   
   console.log(`My name is ${generateName()}.`);
   ```
2. Run the script:
   ```sh
   node index.js
   ```

## ECMAScript Modules (ESM) vs CommonJS (CJS)

By default, Node.js uses CommonJS (`require`), but you can switch to ECMAScript modules (`import`) by modifying `package.json`:
```json
{
  "type": "module"
}
```
Now, you can use `import` statements instead of `require`.

## Challenge: Use the `superheroes` Package

1. Install the `superheroes` package:
   ```sh
   npm i superheroes
   ```
2. Modify `index.js` to use the package:
   ```javascript
   import superheroes from 'superheroes';
   
   console.log(`I am ${superheroes.random()}!`);
   ```
3. Run the script:
   ```sh
   node index.js
   ```

## Error Handling

If you see:
```sh
SyntaxError: Cannot use import statement outside a module
```
Make sure you have added the following in `package.json`:
```json
{
  "type": "module"
}
```

## Summary

- **NPM** is a package manager for Node.js.
- Use `npm init` to create a `package.json` file.
- Install packages with `npm i package-name`.
- Use `import` to include packages (ensure `"type": "module"` in `package.json`).
- Explore packages at [npmjs.com](https://www.npmjs.com/).

Happy coding! 🚀
