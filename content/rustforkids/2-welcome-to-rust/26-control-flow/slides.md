# Control Flow: Making Decisions in Code

---

## 🤔 What Is Control Flow?

**Control flow** is how your program **makes decisions**.

You can ask questions like:

- Is the number bigger than 10?
- Is it sunny today?
- Is the user name correct?

Rust lets you use `if`, `else`, and `match` to control what happens!

---

## 🔀 `if` and `else`

```rust
let age = 10;

if age >= 18 {
    println!("You can vote!");
} else {
    println!("You are too young to vote.");
}
```

- ✅ The condition goes in parentheses
- ✅ The block runs only if the condition is **true**

---

## 🔁 else if

You can check **multiple conditions**:

```rust
let score = 75;

if score >= 90 {
    println!("A+");
} else if score >= 60 {
    println!("Passed!");
} else {
    println!("Try again!");
}
```

Rust checks conditions **in order**, top to bottom.

---

## ✅ Boolean Expressions

Inside `if (...)`, you can use:

| Expression         | Meaning                      |
| ------------------ | ---------------------------- |
| `x == 5`           | x is equal to 5              |
| `x != 3`           | x is NOT 3                   |
| `age >= 18`        | age is 18 or more            |
| `is_happy == true` | is\_happy is true (can omit) |

Example:

```rust
if is_happy {
    println!("Yay!");
}
```

---

## 🧠 `match`: Superpower of `if`

`match` is like a smart switch-case.

```rust
let grade = 'B';

match grade {
    'A' => println!("Excellent!"),
    'B' => println!("Great!"),
    'C' => println!("Good."),
    _   => println!("Keep trying!"),
}
```

- ✅ The `_` means "anything else"
- ✅ Every case uses `=>` and ends with a comma

---

## 🧪 Mini Challenge

Try these in your main.rs:

- ✅ Use `if` to check if a number is **even or odd**
- ✅ Use `else if` to print a **letter grade** from a score
- ✅ Use `match` to print a message for `'A'`, `'B'`, `'C'`, or `'F'`

---

## ✅ Summary

- Use `if`, `else`, and `else if` to control what your program does
- Conditions must be **true** or **false**
- Use `match` when you have many possible values
- Rust checks your logic to keep it safe and readable!
