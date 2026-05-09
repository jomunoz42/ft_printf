# ft_printf

A custom implementation of the standard `printf` function written in C as part of the 42 curriculum.

The objective of this project was to recreate the core behavior of `printf` while developing a deeper understanding of variadic functions, formatted output handling, parsing, and low-level output operations.

This implementation supports multiple format specifiers and dynamic argument handling using variadic arguments.

---

## 🧠 What I Learned

Working on ft_printf provided practical experience with:

- Variadic functions
- Format string parsing
- Dynamic argument handling
- Base conversions
- Low-level output operations
- String formatting
- Modular architecture
- Memory management

---

## ⚙️ Features

### ✅ Supported Format Specifiers

- `%c` → Character
- `%s` → String
- `%p` → Pointer address
- `%d` → Decimal integer
- `%i` → Integer
- `%u` → Unsigned integer
- `%x` → Lowercase hexadecimal
- `%X` → Uppercase hexadecimal
- `%%` → Percent sign

### ✅ Core Functionality

- Variadic argument handling with `va_list`
- Format string parsing
- Recursive number conversion
- Hexadecimal formatting
- Pointer formatting
- Error-safe output handling

---

## 🛠 Technologies

- C
- Variadic Functions
- Unix/Linux
- Makefile

---

## 🚀 Compilation

```bash
make
```

---

## ▶️ Usage

Include the header:

```c
#include "ft_printf.h"
```

Example:

```c
ft_printf("Hello %s!\n", "world");
```

---

## 💻 Example Output

```bash
Hello world!
Number: 42
Hex: 2a
Pointer: 0x7ffee4b8c
```

---

## 🧩 Core Concepts

### Parsing
- Format specifier detection
- String traversal
- Conditional formatting logic

### Variadic Functions
- `va_start`
- `va_arg`
- `va_end`

### Conversion Logic
- Integer conversion
- Hexadecimal conversion
- Pointer formatting
- Recursive printing functions

---

## 📚 Key Challenges

- Building a reliable format parser
- Managing variadic arguments correctly
- Implementing conversion functions efficiently
- Reproducing standard printf behavior
- Handling edge cases and formatting consistency

---

## 👤 Author

- João Muñoz
