# QR Code Generator Project

## Overview
This project creates a QR Code Generator using **Node.js**. It takes a user-provided URL and generates a QR code image along with a text file storing the URL.

## Technologies Used
- **Node.js**
- **NPM Packages:**
  - `inquirer` (for user input)
  - `qr-image` (for QR code generation)
  - `fs` (for file system operations)

---

## Steps to Build

### 1️⃣ Install Required Packages
```sh
npm init -y  # Initialize package.json
npm install inquirer qr-image  # Install dependencies
```

### 2️⃣ Import Modules
```javascript
import inquirer from 'inquirer';
import fs from 'fs';
import qr from 'qr-image';
```

### 3️⃣ Get User Input
```javascript
inquirer
  .prompt([
    {
      type: 'input',
      name: 'userInput',
      message: 'Type in your URL:',
    },
  ])
  .then((answers) => {
    const url = answers.userInput;
```

### 4️⃣ Generate QR Code
```javascript
    var qr_svg = qr.image(url);
    qr_svg.pipe(fs.createWriteStream('qr_img.png'));
    console.log('QR code generated successfully.');
```

### 5️⃣ Save URL to a Text File
```javascript
    fs.writeFile('URL.txt', url, (err) => {
      if (err) throw err;
      console.log('URL saved to URL.txt');
    });
  })
  .catch((error) => {
    console.error('Error:', error);
  });
```

---

## Running the Project
```sh
node index.js
```
- Enter a valid URL when prompted.
- The QR code image (`qr_img.png`) and text file (`URL.txt`) will be created.

---

## Notes & Learnings
- **`inquirer`**: Used for interactive command-line prompts.
- **`qr-image`**: Converts text (URL) to a QR code.
- **`fs.writeFile()`**: Saves user input to a text file.
- **ES Module Syntax** (`import/export`) is required for consistency.
- Set `"type": "module"` in `package.json` for ES module support.

---
