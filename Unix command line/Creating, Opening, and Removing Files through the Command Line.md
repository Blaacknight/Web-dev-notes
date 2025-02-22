# Command Line Basics - Notes

## 1. Creating Directories & Files
- `mkdir folder_name` → Create a new directory.  
- `cd folder_name` → Move into a directory.  
- `ls` → List contents of a directory.  
- `touch file_name.ext` → Create an empty file.  

## 2. Opening Files
- `open file_name.ext` *(Mac)* → Opens file in the default app.  
- `open -a "Application Name" file_name.ext` → Opens file in a specific app.  

## 3. Removing Files & Directories
- `rm file_name.ext` → Remove a file.  
- `rm *` → Remove all files in the current directory.  
- `rm -r folder_name` → Remove a folder and all its contents.  

## 4. Dangerous Commands (Use with Caution!)
> ⚠ **Warning:** Running these commands can delete your entire system!

- `sudo rm -rf / --no-preserve-root` → **DO NOT RUN** (Deletes everything on the system).  

## 5. Checking Current Directory
- `pwd` → Prints the current working directory.  

## Additional Learning Resources
- [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial)
