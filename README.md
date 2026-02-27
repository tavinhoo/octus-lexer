# 🐙 Octus Lexer

## 📖 Overview
**Octus Lexer** is a lexical analyzer implementation built from scratch, without the use of parser generators (such as Lex/Yacc) or external automation tools.

The project focuses on transforming raw source code into a structured sequence of tokens through **deterministic scanning** and pattern recognition.

> **The Challenge:** This project was developed with the goal of deep learning, using **as little AI assistance as possible**. The focus is on manually solving logical problems and achieving full mastery of compiler architecture.

---

## 🎯 Goals
- **Understand lexical analysis**: Gain a deep understanding of the first phase of a compiler.
- **Build compiler foundations**: Create a solid base for future translation and syntactic analysis stages.
- **Study language architecture**: Explore how grammars and automata operate in pattern recognition.

---

## ⚙️ Features
The lexer identifies and categorizes the following elements:

- 🆔 **Identifiers**: Names of variables, functions, and user-defined types.
- 🔢 **Number Parsing**: Numeric literals (integers and decimals).
- 🔑 **Keyword Recognition**: Reserved words of the language.
- ⚡ **Operator Handling**: Arithmetic, logical, and assignment symbols.
- 📍 **Line Tracking**: Line and column tracking for precise error reporting.
- 🏁 **EOF Detection**: Robust end-of-file handling.

---

## 📐 Example

### Input:
```javascript
let x = 10 + 20;
```

### Output:
<pre>
LET
IDENTIFIER(x)
EQUAL
NUMBER(10)
PLUS
NUMBER(20)
SEMICOLON
EOF
</pre>

# 🏗 Architecture
The data flow follows the classic compiler front-end pipeline:

Source Code ➔ Lexer (Scanning & Pattern Recognition) ➔ Token Stream


## 🚀 Roadmap
- [ ] Token definitions
- [ ] Number parsing
- [ ] Identifier parsing
- [ ] Keyword recognition
- [ ] Error handling
- [ ] Parser implementation (future)
