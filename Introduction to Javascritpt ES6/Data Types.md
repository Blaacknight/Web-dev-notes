# JavaScript Basics: Strings, Numbers, and Booleans

## Using `alert()` in JavaScript
```javascript
alert("Hello");
```
- Displays a pop-up with "Hello".
- Click **OK** to dismiss it.

## Understanding Strings in JavaScript
- A **string** is a sequence of characters enclosed in quotation marks.
- Example:
```javascript
alert("Hello, World!");
```
- The browser interprets everything inside the quotes as text.

## Importance of Data Types
A **data type** tells the computer how to interpret a piece of data.

### Common Data Types in JavaScript:
1. **Strings** → Text enclosed in quotes.
   ```javascript
   typeof("Hello"); // Output: "string"
   ```
2. **Numbers** → Numeric values (no need for quotes).
   ```javascript
   typeof(23); // Output: "number"
   ```
3. **Booleans** → True/False values.
   ```javascript
   typeof(true); // Output: "boolean"
   ```

## Using the JavaScript Console
1. Open **Google Chrome**.
2. Go to **View** > **Developer** > **JavaScript Console**.
3. Type JavaScript commands and press **Enter**.

### Testing Data Types in Console
```javascript
typeof(2 + 3); // Output: "number"
typeof("My Name"); // Output: "string"
typeof(false); // Output: "boolean"
```

## Summary
- Strings are enclosed in `""` or `''`.
- Numbers don’t need quotes.
- Booleans are either `true` or `false`.
- `typeof()` helps determine the data type.

In the next lesson, we'll explore more foundational concepts in JavaScript.
