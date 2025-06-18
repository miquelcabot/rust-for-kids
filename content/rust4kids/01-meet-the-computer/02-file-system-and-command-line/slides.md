# The File System and the Command Line

---

## 🗂️ What Are Files and Folders?

Your computer is like a big library 📚. Inside it are:

- **Files** 📄 → documents, pictures, music, code, and more.
- **Folders** 📁 → containers to help organize your files.

You can put files **inside** folders, and folders **inside** other folders. Just like boxes inside boxes!

---

## 🖥️ Different Operating Systems

There are three main types of operating systems (OS):

- 🐧 **Linux**: free, open-source, used on many servers and by programmers.
- 🍎 **macOS**: used on Apple computers.
- 🪟 **Windows**: very common in schools and offices.

They all **do the same basic things**, but the way you use the terminal or navigate folders might look a little different.

---

### 📌 This Book Uses: Linux & macOS

To keep things simple, this book focuses on:

- ✅ **Linux** (like Ubuntu or Debian)
- ✅ **macOS** (on a MacBook or iMac)

If you're using **Windows**, don't worry! You can still follow along.

---

### 💡 Windows Users: Use WSL

To get a Linux-like terminal on Windows, install:

🔧 **WSL** (Windows Subsystem for Linux)
It lets you run Linux commands inside Windows.
You can install it by following this guide:
👉 [https://learn.microsoft.com/en-us/windows/wsl/](https://learn.microsoft.com/en-us/windows/wsl/)

Once installed, you'll be able to use the same terminal commands we use in this book.

---

## 🏠 The Home Directory

Every user has a personal **home directory**. It's like your bedroom in the computer's house.

- On **Linux/macOS**, it looks like:

```text
/home/alex/
```

or

```text
/Users/alex/
```

> This is where all your stuff (documents, downloads, code) lives.

---

## 📜 Paths and File Extensions

- A **path** tells the computer **where** something is.
Example: `/home/alex/projects/rust_for_kids/main.rs`

- A **file extension** tells **what** kind of file it is:
- `.txt` → text
- `.jpg` → image
- `.rs` → Rust code
- `.exe` → Windows program

---

## 💻 The Terminal is a Magic Door 🧙‍♂️

The **terminal** (or "command line") is a tool to **talk directly to your computer**.

You don't click, you type! It's like writing spells.

Programmers love the terminal because it's **powerful and fast**.

---

## 🔤 Terminal Command Cheat Sheet

| Command             | What it does                                     |
|---------------------|--------------------------------------------------|
| `pwd`               | Show where you are right now                     |
| `ls`                | List everything in the current folder            |
| `cd foldername`     | Enter a folder                                   |
| `cd ..`             | Go up one level (to the parent folder)           |
| `cd .`              | Stay where you are (the "current directory")     |
| `mkdir my_folder`   | Make a new folder                                |
| `touch hello.txt`   | Create a new empty file                          |
| `cat hello.txt`     | Show what's inside the file                      |
| `rm file.txt`       | Delete a file (⚠️ careful!)                      |
| `mv file.txt newname.txt` | Rename a file                              |
| `mv file.txt folder/`     | Move a file into a folder                  |
| `clear`             | Clean the screen                                 |

> Tip: You can press the **up arrow** ↑ to repeat your last command!
---

## 🧭 Terminal Challenge!

Try this in your terminal:

```bash
mkdir rust_games
cd rust_games
touch hello.txt
cat hello.txt
```

> You're now a file system explorer!

---

## 🧭 Mini Terminal Adventure

Try this:

```bash
mkdir my_story
cd my_story
touch chapter1.txt
echo "Once upon a time..." > chapter1.txt
cat chapter1.txt
mv chapter1.txt intro.txt
cd ..
ls
```

You just:

- ✅ created a folder
- ✅ entered it
- ✅ created and edited a file
- ✅ renamed the file
- ✅ went back up a folder
- ✅ listed what's there!
