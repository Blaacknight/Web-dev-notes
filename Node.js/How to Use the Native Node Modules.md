# Using Native Node Modules

## Introduction

In this lesson, we will explore **Native Node Modules**—pre-built modules in Node.js that enhance JavaScript's capabilities beyond the browser.

## What Are Native Node Modules?

Native Node Modules are built-in modules in Node.js that provide essential functionalities for building applications, particularly on the server side. Some common examples include:

- **File System (`fs`)**: Read and write files on your local machine or server.
- **Networking (`http`, `https`)**: Enable communication over the internet.
- **Path (`path`)**: Work with file and directory paths.

These modules function similarly to built-in applications on an operating system, such as Minesweeper or Solitaire on Windows.

## The File System Module (`fs`)

JavaScript running in the browser cannot access a user’s local files. However, Node.js enables file manipulation using the `fs` module.

### Importing the `fs` Module

We use `require` to load the `fs` module:

```javascript
const fs = require("fs");
```

### Writing to a File

We can use the `fs.writeFile()` method to create and write to a file.

```javascript
fs.writeFile("message.txt", "Hello from NodeJS!", (err) => {
  if (err) throw err;
  console.log("File has been saved!");
});
```

- **First argument**: File name (`message.txt`)
- **Second argument**: Content to write (`"Hello from NodeJS!"`)
- **Third argument**: Callback function to handle errors

### Running the Script

1. Open a terminal.
2. Navigate to the project folder (`cd <your-folder>`).
3. Run the script using:
   ```sh
   node index.js
   ```
4. You should see `File has been saved!` in the terminal, and a new file (`message.txt`) will be created with the specified content.

## Challenge: Reading from a File

Now, try using the `fs.readFile()` method to read the contents of `message.txt` and print it to the console.

### Solution

```javascript
fs.readFile("message.txt", "utf8", (err, data) => {
  if (err) throw err;
  console.log(data);
});
```

### Explanation
- **First argument**: Path to the file (`message.txt`)
- **Second argument**: Encoding (`"utf8"`) to return text instead of a buffer
- **Third argument**: Callback function that logs the file’s contents

### Running the Read Script
1. Modify `message.txt` with a new message.
2. Run `node index.js` to see the updated file contents printed in the terminal.

## Summary

- **Native Node Modules** expand JavaScript’s capabilities beyond the browser.
- **The `fs` module** allows reading and writing files.
- **Challenge**: Implement `fs.readFile()` to read file contents and display them in the terminal.


