# Variables: Your Code's Memory

---

## 📦 What is a Variable?

A **variable** is like a box 🧰 with a name, where you can store a value.

In Rust, we use the keyword `let` to create one:

```rust
let age = 10;
```

This means:
"Create a box named `age` and put the number `10` inside."

---

## 🧠 Variables Store Information

You can store different **types** of values:

```rust
let age = 10;               // i32 → integer
let name = "Alex";          // &str → text
let is_rust_fun = true;     // bool → true or false
```

Rust usually figures out the type for you (this is called **type inference**).

But you can also be explicit:

```rust
let score: i32 = 100;
let name: String = String::from("Zoe");
```

---

## 🔄 What If I Want to Change It?

Rust makes variables **immutable** by default: **they cannot be changed**.

```rust
let age = 10;
age = 11; // ❌ error!
```

If you want to change it, use `mut` (for "mutable"):

```rust
let mut age = 10; // Now it's mutable
age = 11; // ✅ now it works!
```

> 💡 Tip: Rust helps you write safer code by making things immutable by default.

---

## 🧪 Mini Challenge

Try writing this in your `main.rs`:

```rust
let mut score = 0;
println!("Score: {}", score);

score = 5;
println!("New score: {}", score);
```

---

## 🧠 Common Variable Types

| Type | Example | Description |
|·--------·|·---------------------------------·|·-----------------------·|
| `i32` | `let x = 5;` | Integer (32-bit number) |
| `bool` | `let done = true;` | True or false |
| `String` | `let name = String::from("Zoe");` | Text (owned string) |

> Rust is a **statically typed** language: every variable has a type!

---

## ✅ Summary

- Variables hold information: like numbers, text, or true/false values
- Use `let` to create variables
- Use `mut` to make them changeable
- Rust has powerful, safe types like `i32`, `bool`, and `String`
