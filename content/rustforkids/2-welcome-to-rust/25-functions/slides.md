# Functions: The Magic of Reusable Code

---

## ✨ What Is a Function?

A **function** is a named block of code that does something.

It's like a **spell** you can use over and over again. 🧙‍♂️

Example:

```rust
fn greet() {
    println!("Hello, Rustacean!");
}
```

To run the function, you **call** it:

```rust
greet();
```

---

## 🧱 The Structure of a Function

Here's what a basic function looks like:

```rust
fn say_hello() {
    println!("Hello!");
}
```

- `fn` → means **function**
- `say_hello` → the name
- `()` → no input
- `{ ... }` → the code block

You can define many functions, but `main()` is always the one that runs first!

---

## 🧮 Functions With Parameters

Functions can take **inputs**:

```rust
fn greet(name: &str) {
    println!("Hello, {}!", name);
}
```

Call it like this:

```rust
greet("Zoe");
```

The `name: &str` means it expects a **string slice** (a bit of text).

> 🎁 Parameters are like ingredients you give to the function.

---

## ➕ Multiple Parameters in a Function

You can pass more than one input to a function!

Just separate them with commas:

```rust
fn add(a: i32, b: i32) {
    println!("Sum is: {}", a + b);
}
```

Call it like this:

```rust
add(3, 7); // Sum is: 10
```

---

## 🔙 Returning Values from a Function

Sometimes you want a function to give something **back**.

To do that, you define a **return type** and use the `return` keyword:

```rust
fn square(x: i32) -> i32 {
    return x * x;
}
```

Then you can save the result:

```rust
let result = square(5);
println!("5 squared is {}", result);
```

---

## 🧠 `return` Is Optional at the End

Rust allows you to **skip** `return` on the last line of a function:

```rust
fn square(x: i32) -> i32 {
    x * x  // no semicolon = return value
}
```

> ❗ Don't put a `;` if you want to return the value!

✅ This also works:

```rust
fn greet() -> String {
    String::from("Hello!")
}
```

---

## 🧪 Mini Challenge

Try this:

- ✅ Write a function called `say_name()` that prints your name
- ✅ Write a function `add(a, b)` that returns the sum of two numbers
- ✅ Call both from `main()` and print the results

---

## ✅ Summary

- Functions let you **organize** and **reuse** code
- Use `fn name() { ... }` to define them
- You can give functions **parameters** and get back **return values**
- Every program starts with the special `fn main()`
