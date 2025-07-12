# Installing Rust

---

## 🚀 Let's Get Started!

To write Rust programs, we need to install:

- 🦀 `rustc`: the Rust compiler
- 📦 `cargo`: the Rust project manager (like a magic toolbox)

These tools come together in something called **rustup**.

---

## 🛠️ Step 1: Install Rust

Open your terminal and paste this command:

```bash
curl https://sh.rustup.rs -sSf | sh
```

Then follow the instructions that appear.

✅ Works on Linux, macOS, and WSL (Windows Subsystem for Linux)

---

## 🌐 Alternative Options

If you don't want to install anything locally, you can use:

- [Google Cloud Shell](https://shell.cloud.google.com/): a free cloud-based terminal and editor.
  - ➕ Great for coding from anywhere
  - ⚠️ You'll still need to install Rust manually with `rustup`
- [Rust Playground](http://play.rust-lang.org/): a browser-based Rust editor for quick experiments.
  - ➕ No installation needed
  - ➖ Limited to small examples and no file system access

Perfect for testing or learning on the go! 🚀

---

## 🧪 Step 2: Check the Installation

Once it's done, check that everything works:

```bash
rustc --version
cargo --version
```

You should see something like:

```text
rustc 1.xx.x
cargo 1.xx.x
```

---

## 📝 Step 3: Write Your First Rust Program!

Let's create a folder for our first project:

```bash
cargo new hello_rust
cd hello_rust
```

Now open the file `src/main.rs` and you'll see:

```rust
fn main() {
    println!("Hello, world!");
}
```

---

## ▶️ Step 4: Run Your Program

In the same folder, run:

```bash
cargo run
```

You should see:

```text
   Compiling hello_rust v0.1.0
    Finished dev [unoptimized + debuginfo]
     Running `target/debug/hello_rust`
Hello, world!
```

🎉 Congratulations! You just wrote and ran your first Rust program!

---

## 🧰 Extra Cargo Commands

Rust gives you extra tools to help you while you code!

---v

### 🛠️ `cargo build`

This command compiles your program:

```bash
cargo build
```

It creates an executable, but **doesn’t run it**.

Great for checking that your program builds without running it.

---v

### ✅ `cargo check`

Checks your code for errors — but **doesn’t build** the final program:

```bash
cargo check
```

⚡ It’s much faster than `cargo build`, and great while you’re writing!

---v

### 🧹 `cargo fmt`

This command **automatically formats** your Rust code:

```bash
cargo fmt
```

It keeps your code **clean and readable**, following Rust style rules.

> Like a digital toothbrush for your code! 🪥✨

---

## ✅ Summary

- Installed Rust with `rustup`
- Verified `rustc` and `cargo` are working
- Created a new project with `cargo new`
- Ran your first Rust code with `cargo run`
- Checked your code with `cargo check`
- Built your program with `cargo build`
- Formatted your code with `cargo fmt`

Let's move on and learn what this code means! 🦀💡
