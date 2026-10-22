# 🌿 CFG Parse Tree Generator

A Python-based web application that validates mathematical expressions using **Context-Free Grammar (CFG)** and generates visual parse trees using Natural Language Toolkit (NLTK).

## 📌 Project Overview

The CFG Parse Tree Generator is a Theory of Computation mini project. It demonstrates how mathematical expressions can be checked against a context-free grammar and how different parse trees can be generated for ambiguous expressions.

The application provides a simple, interactive interface built using Streamlit.

## 🎯 Objectives

- Validate the syntax of mathematical expressions using CFG.
- Generate and visualize parse trees.
- Demonstrate ambiguity in context-free grammars.
- Identify valid and invalid expressions.
- Understand syntax analysis through a practical application.

## ✨ Features

- Mathematical expression input.
- Syntax validation with accepted or rejected status.
- Visual parse tree generation.
- Parse tree counting for ambiguous expressions.
- Support for variables, numbers, arithmetic operators, and parentheses.
- Display of CFG production rules.
- Simple interface with a pastel green theme.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Streamlit** — Web application interface
- **NLTK** — Context-Free Grammar and parsing
- **Matplotlib** — Parse tree visualization
- **Regular Expressions** — Tokenization of mathematical expressions

## ➗ Supported Operators

| Symbol | Operation |
|---|---|
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `^` | Exponentiation |
| `( )` | Parentheses |

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/sameenashaik267-bit/CFG-Parse-Tree-Generator.git
```

### 2. Open the project folder

```bash
cd CFG-Parse-Tree-Generator
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the application

```bash
python -m streamlit run app.py
```

The application will open in your web browser.

## 🧪 Example Inputs

| Expression | Expected behavior |
|---|---|
| `a+b` | Accepted; one parse tree |
| `a+b*c` | Accepted; two parse trees |
| `a+b+c` | Accepted; two parse trees |
| `(a+b)*c` | Accepted; one parse tree |
| `a++b` | Rejected when unary plus is disabled |
| `(a+b` | Rejected due to unmatched parentheses |

**Note:** The exact results depend on the CFG rules configured in `app.py`. The grammar is intentionally ambiguous, so normal mathematical operator precedence is not enforced.

## 📚 Theory Concepts

This project demonstrates:

- Context-Free Grammar (CFG)
- Production rules
- Terminals and non-terminals
- Syntax analysis
- Parse tree construction
- Ambiguous grammar
- Valid and invalid strings

## ⚠️ Limitations

- The application checks syntax, not numerical answers.
- The grammar does not enforce normal operator precedence.
- Complex expressions can generate many parse trees.

## 🔮 Future Enhancements

- Support for operator precedence and associativity.
- Numerical evaluation of valid expressions.
- Improved parse tree layouts.
- Exporting parse trees as images.
- Deployment as an online web application.

## 👩‍💻 Author

**Sameena Shaik**

GitHub: [@sameenashaik267-bit](https://github.com/sameenashaik267-bit)

## 📄 License

This project is developed for educational purposes as a Theory of Computation mini project.
