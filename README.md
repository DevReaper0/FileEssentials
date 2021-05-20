# File Essentials

File Essentials is a package that contains
all of the necessary functions to create, delete,
write to, append to, read from, and so on, from files

---

### Getting Started
Add the following to your ParaCode file
```js
import("FileEssentials");
```

#### Creating a file
Just use the `CreateFile(name);` function.

#### Creating a file If It Does Not Exist
Just use the `CreateFile(name, true);` function.

#### Deleting a File
Just use the `DeleteFile(name);` function.

#### Deleting a Directory
Just use the `DeleteDirectory(name);` function.

#### Reading From a file
Just use the `ReadFile(name);` function.

#### Reading Lines From a file
Just use the `ReadFileLines(name);` function.

#### Reading Specific Line From a file
Just use the `ReadFileLine(name, line);` function.

#### Writing To a file
Just use the `WriteFile(name, text);` function.

#### Appending To a file
Just use the `AppendFile(name, text);` function.

#### Checking If a file Exists
Just use the `CheckFileExists(name);` function.

#### You can also run the same functions, except without the word `File`, and for `DeleteDirectory`, the shortened version is `DeleteDir`