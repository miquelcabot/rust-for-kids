# The Language of Machines: Binary Basics

---

## 🧠 What Is a Bit?

A **bit** is the smallest piece of data a computer can store.

It can only be **1** (on 💡) or **0** (off ⚫), like a flashlight switch!

A **byte** is a group of **8 bits**. With 8 bits, we can count from `0` to `255` because:

```math
2^8 = 256
```

---

## 🧮 Decimal vs Binary

We usually count in **decimal** (base 10):

| Digit Position  | Sixth  | Fifth | Fourth | Third | Second | First |
|-----------------|--------|-------|------|-----|----|---|
| Power of 10     | 10⁵    | 10⁴   | 10³  | 10² | 10¹|10⁰|
| Decimal Value   | 100000 | 10000 | 1000 | 100 | 10 | 1 |
| Digit           | 6      | 5     | 4    | 3   | 2  | 1 |

Each digit is worth 10 times more than the one next to it (1, 10, 100...).

---

### But computers count in **binary** (base 2):

We use only **0** and **1** (base 2):

| Bit Position     | 8th   | 7th  | 6th  | 5th  | 4th  | 3rd | 2nd | 1st |
|------------------|-------|------|------|------|------|-----|-----|-----|
| Power of 2       | 2⁷    | 2⁶   | 2⁵   | 2⁴   | 2³   | 2²  | 2¹  | 2⁰  |
| Decimal Value    | 128   | 64   | 32   | 16   | 8    | 4   | 2   | 1   |
| Example Bits     | 0     | 1    | 0    | 1    | 0    | 1   | 0   | 1   |

This is what `01010101` means:

Just **add up the positions where there’s a 1** to get the number!

> `01010101` → 64 + 16 + 4 + 1 = **85**

---

## 🧮 Binary Conversion Table

Here are the first 16 numbers in **decimal** and **binary**

| Decimal | Binary | Decimal | Binary |
|---------|--------|---------|--------|
| 0       | 0000   | 8       | 1000   |
| 1       | 0001   | 9       | 1001   |
| 2       | 0010   | 10      | 1010   |
| 3       | 0011   | 11      | 1011   |
| 4       | 0100   | 12      | 1100   |
| 5       | 0101   | 13      | 1101   |
| 6       | 0110   | 14      | 1110   |
| 7       | 0111   | 15      | 1111   |

Try finding your age in binary!

> 🔢 Tip: With 4 bits, you can count from **0 to 15**. That’s `2⁴ = 16` combinations!

---

## 🔤 What About Letters?

Computers also store **text as numbers**, using something called **ASCII**.

For example:

| Character | ASCII Decimal | Binary       |
|-----------|----------------|--------------|
| A         | 65             | 01000001     |
| B         | 66             | 01000010     |
| C         | 67             | 01000011     |
| a         | 97             | 01100001     |

So `"Hi"` = `01001000 01101001` in binary!

---

## 💾 Bytes, Kilobytes, Megabytes…

Let’s zoom out!

| Unit        | Description                   |
|-------------|-------------------------------|
| 1 Byte      | = 8 bits                      |
| 1 Kilobyte  | = 1024 Bytes                  |
| 1 Megabyte  | = 1024 KB                     |
| 1 Gigabyte  | = 1024 MB                     |
| 1 Terabyte  | = 1024 GB                     |
| 1 Petabyte  | = 1024 TB                     |

---

## Binary Numbers for Kids

<!-- markdownlint-disable MD033 -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hvteVokz7jE?si=J4ji6DsdHMNsc7CQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- markdownlint-enable MD033 -->

---

## 🧪 Try This!

1. Write the number `7` in binary
2. Convert the word `OK` to ASCII + binary
3. What’s the biggest number you can make with **8 bits**?
4. Find the binary for the word `RUST`

---

## ✅ Summary

- Computers only understand **1s and 0s**: **binary**.
- A **bit** is one 1/0; a **byte** is 8 bits.
- We use **ASCII** to turn text into numbers.
- Memory is measured in units like **KB, MB, GB, TB**, etc.
