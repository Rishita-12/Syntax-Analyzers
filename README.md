# 🔍 C Syntax Analyzer (Web-Based)

This is a **web-based syntax analyzer** for the C programming language. It includes a **tokenizer (lexer)** and a **recursive descent parser**, built using **JavaScript**, **HTML**, and **CSS**. The tool can identify valid C syntax, report syntax errors, and display tokenized output with helpful error messages.

---

## 🚀 Features

- ✅ Tokenization of C source code (keywords, identifiers, literals, operators, etc.)
- ✅ Recursive descent parser for checking C syntax
- ✅ Interactive, real-time validation and error feedback
- ✅ Syntax-highlighted output with line numbers
- ✅ Lightweight, runs fully in-browser (no server required)

---

## 📂 Project Structure


---

## 🧠 How It Works

### 1. Lexer (Tokenizer)

The lexer splits input C code into tokens such as:

- **Keywords** (`int`, `return`, `if`, etc.)
- **Identifiers** (`main`, `x`, `sum`, etc.)
- **Operators** (`+`, `-`, `=`, `==`, etc.)
- **Literals** (numbers, strings)
- **Delimiters** (`;`, `()`, `{}`, etc.)

### 2. Parser

Implements a **recursive descent parsing** strategy to validate:

- Variable declarations
- Function definitions
- Conditional and loop statements
- Return statements
- Block and expression rules

### 3. Error Handling

- Reports the **line and type of syntax error**
- Shows **meaningful feedback** like _"Expected ';' after expression"_
- Continues checking further tokens after the error

---

## 🧪 Sample Code Example

```c
int main() {
    int a = 5;
    if (a > 0) {
        return a;
    }
}
