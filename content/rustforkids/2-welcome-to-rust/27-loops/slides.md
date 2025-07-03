# Loops: Repeating Actions in Rust

---

## 🔁 What Is a Loop?

A **loop** is used when you want to do something **over and over again**.

Examples:

- Count from 1 to 10
- Print a message 3 times
- Check a condition until it's false

Rust gives us 3 types of loops:

- `loop`
- `while`
- `for`

---

## ♾️ `loop`: Repeat Forever (or Until You Break)

```rust
loop {
    println!("This will go on forever!");
}
```

❗ You must **manually stop** an infinite loop with `break`:

```rust
let mut counter = 0;

loop {
    println!("Count: {}", counter);
    counter += 1;

    if counter == 5 {
        break;
    }
}
```

---

## 🔄 `while`: Repeat While a Condition Is True

```rust
let mut number = 3;

while number > 0 {
    println!("{}!", number);
    number -= 1;
}

println!("Liftoff! 🚀");
```

> `while` checks the condition **before** each loop.

---

## 🔢 `for`: Loop Over a Range

```rust
for number in 1..4 {
    println!("Number: {}", number);
}
```

🧠 `1..4` means: 1, 2, 3 (not including 4)

You can also include 4:

```rust
for number in 1..=4 {
    println!("Now: {}", number);
}
```

> Use `for` when you know **how many times** to loop.

---

## 🎯 Understanding Ranges in Rust

A **range** is a way to say:
"Start at this number, go up to (or through) that number."

### 🧮 Exclusive Range

```rust
1..4
```

Means: `1`, `2`, `3` (but **not** 4)

### ✅ Inclusive Range

```rust
1..=4
```

Means: `1`, `2`, `3`, `4` (includes 4)

---v

You can use them in `for` loops:

```rust
for n in 0..=5 {
    println!("{}", n);
}
```

---v

> 🔍 Ranges are **not just for numbers** — they work with letters too!

```rust
for c in 'a'..='e' {
    println!("{}", c);
}
```

---

## 🧪 Mini Challenge

- ✅ Use a `loop` to print numbers until you reach 10
- ✅ Use a `while` loop to count down from 5 to 1
- ✅ Use a `for` loop to print the letters A to Z (hint: use chars!)

---

## ✅ Summary

- `loop` runs forever unless you stop it with `break`
- `while` runs while a condition is true
- `for` is great for counting or looping through things
- Rust gives you flexible, safe looping tools!
