Compiler Design – DSL Mini Project

 Project Overview

This project implements a **mini end-to-end compiler** for a simple **Domain-Specific Language (DSL)** using the **C programming language**. It demonstrates the fundamental phases of a compiler in a simplified and easy-to-understand manner.

 Objectives

* To simulate core compiler phases
* To process simple assignment statements
* To demonstrate tokenization, parsing, semantic checks, and code generation

Compiler Phases Implemented

🔹 1. Lexical Analysis

* Identifies tokens such as:

  * Identifiers (`x`, `y`, `z`)
  * Numbers (`5`, `10`)
  * Operators (`+`)

🔹 2. Syntax Parsing

* Recognizes valid statement patterns:

  * `z = x + y`

🔹 3. Semantic Analysis

* Ensures:

  * Variables are valid
  * Operations are type-compatible

🔹 4. Intermediate Code Generation

* Generates simple intermediate representation:

```id="qfxsaa"
temp = x + y
z = temp
```
Sample Input

```id="s8d3xj"
x = 5
y = 10
z = x + y
```
Sample Output

```id="4a5r3c"
[Lexer] Identifier tokens: x, y, z
[Lexer] Number tokens: 5, 10
[Parser] Assignment recognized: z = x + y
[Semantic] Valid integer operation
[CodeGen] temp = x + y
[CodeGen] z = temp

Final Result: z = 15
```
 Technologies Used

* **C Programming Language**
* Standard I/O functions (`stdio.h`)

Project Structure

```id="9lbkcb"
Compiler-Design-DSL/
├── docs/        → Explanation document
├── output/      → Execution screenshots
├── src/         → C source code
├── test/        → Input file
└── README.md
```

 Key Features

* Simple and beginner-friendly implementation
* Clear demonstration of compiler workflow
* Structured and modular output
* Easy to extend for advanced concepts

 Conclusion

This project successfully demonstrates how a compiler processes source code step-by-step through different phases. It provides a strong foundation for understanding compiler design concepts in a practical way.

 Done By

**Name: Rithanya Suresh Reg No: RA2311026050254 Course: BTech CSE AIML**
