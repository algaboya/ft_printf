# ft_printf 🎯

**ft_printf** is a C project from the 42 curriculum that reimplements the standard `printf` function. The goal is to create a **custom formatted output function** that handles multiple conversion specifiers and flags, while practicing **variadic functions, formatting, and low-level output in C**.  

---

## 📚 Table of Contents
- [Extended Description](#extended-description)  
- [Installation & Make](#installation--make)  
- [Supported Specifiers](#supported-specifiers)  
- [License](#license)  

---

## 📝 Extended Description

The `ft_printf` project helps students master:  

- **Variadic functions** – handling an unknown number of arguments using `stdarg.h`.  
- **Formatted output** – implementing format specifiers (`%d`, `%s`, `%x`, etc.) and flags.  
- **Low-level output in C** – using `write()` efficiently instead of `printf`.  
- **Memory management** – dynamically allocating memory when needed and avoiding leaks.  
- **Modular and reusable code** – separating logic for each specifier into helper functions.  

Completing this project gives you a **deep understanding of C formatting, argument handling, and modular design**, which are essential skills for any C programmer.  

---

## 🛠 Installation & Make

Clone the repository and compile the project using `make`:

```bash
git clone https://github.com/algaboya/ft_printf.git
cd ft_printf
make
```
## 📝 Supported Specifiers

The following format specifiers are implemented in `ft_printf`:

```c
%c  - character
%s  - string
%d  - signed decimal integer
%i  - signed decimal integer
%u  - unsigned decimal integer
%x  - unsigned hexadecimal (lowercase)
%X  - unsigned hexadecimal (uppercase)
%p  - pointer address
%%  - percent sign
```

## 📄 License

This project is for educational purposes and follows the 42 school guidelines.
