# Hello, Rustacean!

---

## 👋 Hello, World!

Now that Rust is installed...
Let's write your first program!

Open the `main.rs` file inside your project folder (`hello_rust/src/main.rs`), and you'll see this:

```rust
fn main() {
    println!("Hello, world!");
}
```

Let's break it down...

---

## 🧱 Anatomy of a Rust Program

```rust
fn main() {
    println!("Hello, world!");
}
```

- 🔹 `fn` means **function**
- 🔹 `main()` is where the program starts
- 🔹 `{ ... }` is a **code block**
- 🔹 `println!` prints a message to the terminal
- 🔹 `"Hello, world!"` is a string
- 🔹 `!` means it's a **macro**
- 🔹 Every line ends with a **semicolon** `;`

---

## 🖨️ What is `println!`?

`println!` is a macro that prints text to the screen.

```rust
println!("Hello, Rustacean!");
```

You can print anything inside the quotes!

Example:

```rust
println!("My favorite number is {}", 42);
```

The `{}` gets replaced with the value. It's like a mini magic placeholder!

---

## 💬 Add Some Comments

Comments are notes for humans. Rust ignores them.

You write them like this:

```rust
// This is a single-line comment

/*
This is a
multi-line comment
*/
```

> Comments help you explain what your code does!

---

## ✨ Challenge Time!

Try changing your code:

- ✅ Print your name
- ✅ Print your age
- ✅ Print something in your own language
- ✅ Add a comment that explains what you did

---

✅ Summary

- You wrote your first Rust program!
- Learned about `fn`, `main`, and `println!`
- Understood how macros and strings work
- Learned how to write comments
