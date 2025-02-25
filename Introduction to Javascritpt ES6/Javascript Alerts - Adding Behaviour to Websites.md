# JavaScript Basics

## Opening the JavaScript Console
1. Open **Google Chrome**.
2. Go to **View** > **Developer** > **JavaScript Console**.
3. Start typing JavaScript commands directly.

## Using `alert()` in JavaScript Console
```javascript
alert("Hello");
```
- This will display a pop-up with "Hello".
- Press **OK** to dismiss it.

### Multi-line Instructions
```javascript
alert("Hello");
alert("World");
```
- Press **Shift + Enter** to continue writing on the next line.
- Press **Enter** to execute both alerts sequentially.

## Using Snippets in Chrome DevTools
1. Open **Chrome DevTools**.
2. Navigate to the **Sources** tab.
3. Click the **Snippets** section.
4. Click **+ New snippet** and name it `index.js`.
5. Write JavaScript code inside the snippet.
6. Click **Run** to execute it.

### Example Snippet Code
```javascript
alert("Hello!");
alert("World");
```

## Understanding Errors
- If you type an undefined function, e.g., `say("Hello")`, you will get:
  ```
  Uncaught ReferenceError: say is not defined
  ```
- This means JavaScript does not recognize `say` as a valid function.

## Learning from MDN Web Docs
- Visit [MDN JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript) for official references.
- Example: Searching for `alert` shows `window.alert()`.

## JavaScript Syntax Breakdown
```javascript
alert("Hello!");
```
- `alert` → A **keyword** (predefined function).
- `"Hello!"` → A **string** (text enclosed in quotes).
- `;` → A **semicolon** (marks the end of a statement).

## Best Practices for Writing JavaScript
1. **Use consistent spacing**: No spaces between function names and parentheses.
2. **Use double quotes (`" "`) for strings**.
3. **Follow style guides**: Check [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
4. **Avoid copying quotes from Word/Docs** (use code editors like VSCode or Atom).
5. **Maintain uniform style**: Code should look as if written by one person.

## Additional Resources
- **[JavaScript Style Guide](https://github.com/airbnb/javascript)**
- **[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**
