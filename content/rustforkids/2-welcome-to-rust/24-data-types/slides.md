# Data Types: The Building Blocks of Rust

---

## 🧱 What Are Data Types?

A **data type** tells the computer what kind of value a variable holds.

In Rust, every value has a type:

- Numbers? 🧮
- Text? 📝
- Yes or no? ✅❌
- Groups of values? 📦

Rust uses types to make sure your program is correct and safe.

---

## 🔢 Scalar Types

These types hold **just one value**.

| Type   | Example             | Description                  |
| ------ | ------------------- | ---------------------------- |
| `i32`  | `let x = 10;`       | Integer                      |
| `f64`  | `let pi = 3.14;`    | Decimal (floating point)     |
| `bool` | `let is_ok = true;` | True or false                |
| `char` | `let letter = 'A';` | A single character or symbol |

> Rust gives you many number types (`i8`, `u32`, `f32`, etc.), but `i32` and `f64` are the defaults.

---

## 🔢 Integer Types

- An **integer** is a whole number (no decimals!).
- Rust gives you options based on:
  - how **big** the number can be (8, 16, 32, 64, 128 bits)
  - and whether it can be **negative**
- Signed integers allow negative numbers:

```rust
let x: i32 = -42;
```

- Common signed types:
  - `i8`, `i16`, `i32`, `i64`, `i128`
  - `isize` (size depends on your computer)

---

## ➕ Unsigned Integers

- **Unsigned integers*** can only store **positive numbers** (or 0).
- They're like regular integers but without the minus sign:

```rust
let points: u32 = 99;
```

- The `u` means `unsigned`.
- Common types:
  - `u8`, `u16`, `u32`, `u64`, `u128`
  - `usize` (size depends on your computer)

> Use `u*` when you're sure the value can't be negative, like age or score!

---

## 🌊 Floating Point Numbers

- Sometimes we need decimals, like `3.14`, `99.99`, or `0.5`.
- These are called **floating-point numbers**.

```rust
let price: f64 = 4.99;
```

- Rust gives you:
  - `f32` → less precise, smaller
  - `f64` → more precise, default

> Use `f64` unless you have a special reason to save space.

---

## 🗃️ Composite Types

These hold **multiple values**.

---

### 📦 Tuples

A tuple is a collection of values of different types:

```rust
let person = ("Zoe", 12, true);
```

Access values with a dot:

```rust
println!("{}", person.0); // Zoe
```

---

### 📚 Arrays

Arrays store **many values of the same type**:

```rust
let scores = [10, 20, 30];
```

Get values with square brackets:

```rust
println!("{}", scores[1]); // 20
```

> Arrays have a **fixed size** in Rust.

---

## 🧠 Type Inference vs. Annotation

Rust usually guesses the type for you:

```rust
let age = 8;         // inferred as i32
let happy = true;    // inferred as bool
```

But you can also be clear:

```rust
let pi: f64 = 3.1415;
let letter: char = 'R';
```

---

## 🧪 Challenge Time!

- ✅ Create a `tuple` with your name and age
- ✅ Make an `array` with your 3 favorite numbers
- ✅ Try creating a `bool` that says if Rust is fun
- ✅ Write a `char` with your favorite emoji!

---

## ✅ Summary

- **Scalar types**: `i32`, `f64`, `bool`, `char`...
- **Composite types**: `tuple`, `array`
- Rust checks your types to keep your code safe
- You can let Rust guess, or you can write the type yourself
