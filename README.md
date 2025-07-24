# EXP 4: Bitwise Operators in C++

## 🔰 Aim

To understand and apply **bitwise operators** in C++ by:
1. Demonstrating the basic bitwise operations: AND (`&`), OR (`|`), XOR (`^`), NOT (`~`), Left Shift (`<<`), and Right Shift (`>>`)
2. Checking whether a **specific bit** in a given number is set (1) or not (0)

---

## 📚 Theory

Bitwise operators perform operations at the **binary level**, allowing manipulation of individual bits of integer values. These are particularly useful in systems programming, embedded systems, and low-level optimization.

### 🔹 Common Bitwise Operators:

| Operator | Symbol | Description                        |
|----------|--------|------------------------------------|
| AND      | `&`    | Sets each bit to 1 if both bits are 1 |
| OR       | `|`    | Sets each bit to 1 if one of the bits is 1 |
| XOR      | `^`    | Sets each bit to 1 if only one bit is 1 |
| NOT      | `~`    | Inverts all the bits (1 becomes 0, 0 becomes 1) |
| Left Shift | `<<` | Shifts bits to the left, inserting 0s from right |
| Right Shift | `>>` | Shifts bits to the right, discarding rightmost bits |

---

## 🧠 Algorithms

### ✅ Program 1: Basic Bitwise Operations

1. Start  
2. Declare two integers, `a` and `b`  
3. Apply and display the results of:
   - `a & b`
   - `a | b`
   - `a ^ b`
   - `~a`
   - `a << 1`
   - `b >> 1`
4. End

---

### ✅ Program 2: Check Specific Bit

1. Start  
2. Input a number `n` and a bit position `pos` (starting from 0)  
3. Use the formula: `bit = (n >> pos) & 1`  
4. If bit is 1 → print "Bit is set"  
5. Else → print "Bit is not set"  
6. End

---

## ✅ Conclusion

This experiment successfully demonstrates how **bitwise operations** can be applied to manipulate and analyze individual bits in integers. The first program introduces all core operators, while the second program provides a practical use-case — checking the state of a specific bit, which is often used in embedded systems, flags, and hardware control.

---

## 📌 Topics Covered

- Binary representation of integers
- Bitwise AND, OR, XOR, NOT
- Left and right shifts
- Bit masking and checking specific bits
