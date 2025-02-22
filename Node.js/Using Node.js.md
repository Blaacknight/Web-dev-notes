## Checking Node.js Version

To check your Node.js version, open the terminal and run:

```sh
node -v
```

If you've installed Node.js correctly, you should see a version number, preferably **18 or higher**.

If you see an older version, you may need to update Node.js.

---

## Opening VS Code and Terminal

1. Open **Visual Studio Code**.
2. Go to **View** > **Terminal** or press **Ctrl + `** to open the terminal.
3. Run:

```sh
node -v
```

If the version is correct, you’re good to go!

---

## Using the Node REPL

REPL stands for **Read-Eval-Print Loop**. It allows you to run JavaScript directly in Node.

To enter REPL mode, type:

```sh
node
```

You’ll see a `>` prompt. Try the following:

```js
5 + 8
```

```js
let a = 3;
a + 12;
```

To exit REPL:

- Type `.exit`
- Or press **Ctrl + C** twice

---

## Running JavaScript Files with Node.js

1. Create a new file **index.js**.
2. Add the following code:

```js
console.log("Hello from Node");
```

3. Save the file.
4. Navigate to the file’s directory in the terminal:

```sh
cd path/to/your/folder
```

5. Run the script using Node.js:

```sh
node index.js
```

Output:

```sh
Hello from Node
```

---

## Navigating and Running Scripts

If you are unsure about the file path:

- Use `cd` to change directories.
- Type part of the file name and press **Tab** for auto-completion.

Example:

```sh
node ind<TAB>
```

If the file does not autocomplete, you are likely in the wrong directory.

---

## Extra Practice

Try creating another JavaScript file and running it with Node!

---

### Next Steps

In the next section, we will explore **Node.js built-in modules** and learn how to leverage them for powerful applications.
