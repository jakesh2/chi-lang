# ChiLang: Chichewa Programming Language

![PyPI version badge for chi-lang package](https://img.shields.io/pypi/v/chi-lang)
![Supported Python versions badge for chi-lang](https://img.shields.io/pypi/pyversions/chi-lang)
![Apache 2.0 license badge](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![GitHub stars badge for jakesh2/chi-lang](https://img.shields.io/github/stars/jakesh2/chi-lang?style=social)

ChiLang is a **Chichewa-inspired programming language** built to make programming more accessible through familiar Chichewa keywords, while still fitting into Python-based workflows.

> ChiLang  project focuses on accessibility and learning programming in our Local language hence eliminating langauge barrier and syntanx barrier and also offering transion ready environment with its features to seamlessly work with python to and from.

## ✨ Features

- Beginner-friendly syntax inspired by Chichewa
- Clean command-line workflow (`chi run`, `chi repl`)
- Python ecosystem compatibility through CLI workflows
- Helpful built-in examples to get started quickly
- Lightweight setup via PyPI
- Growing documentation and learning resources

## 📦 Installation

For installation instructions and platform-specific guides, see the official site: https://chi.yazaai.tech

## 🚀 Quick Start

| Goal | Command |
|---|---|
| Start interactive mode | `chi repl` |
| Run a Chi file | `chi run hello.chi` |
| Run built-in example | `chi run --example hello_world` |

## 👋 First Chi Program

Create `hello.chi`:

```chi
onetsa("Moni, dziko!")
```

Run it:

```bash
chi run hello.chi
```

## 💻 CLI Usage Examples

```bash
chi repl
chi run hello.chi
chi run --example hello_world
```

## 🧪 REPL Example

```bash
$ chi repl
>>> onetsa("Moni kuchokera mu REPL!")
Moni kuchokera mu REPL!
```

## 🔗 Python Interoperability Example

You can use Chi alongside Python scripts and tooling:

```python
import subprocess

subprocess.run(["chi", "run", "hello.chi"], check=True)
```

## 🧾 Language Syntax Examples

```chi
ika age = 20

ngati age wafananitsa 18:
    onetsa("Adult")
sizoona:
    onetsa("Minor")
```

_Note: This snippet is intentionally shown using the current Chi tutorial-style syntax._

## 📚 Example Programs Included

Chi ships with runnable examples to support learning:

```bash
chi run --example hello_world
```

## 🌍 Why Chi Exists

Many people learn faster when programming concepts are introduced in familiar language patterns. Chi exists to make coding feel more approachable for Chichewa speakers and beginners, while still connecting to practical Python-based workflows.

## 🤝 Community and Contribution

Contributions are welcome—bug fixes, examples, docs improvements, and ideas all help. Documentation is still growing, and community feedback is valuable.

To contribute:

1. Fork the repository
2. Create a feature branch
3. Open a pull request

## ⭐ Support the Project

If Chi has helped you, taught you something new, or inspired one of your own ideas, please consider giving the repository a star on GitHub. It is a small gesture, but it helps more learners discover the project and encourages continued development.

### 💛 Financial Contributions

If you would like to support Chi financially, contributions are warmly appreciated, but never expected. Please visit the donations page when it feels right for you:

https://chi.yazaai.tech/donations

## 🔗 Links

- [GitHub Repository](https://github.com/jakesh2/chi-lang)
- [PyPI Package](https://pypi.org/project/chi-lang/)
- [Issues](https://github.com/jakesh2/chi-lang/issues)

## 📄 License

This project is licensed under the Apache License 2.0.

## 👤 Author

**Duncan Masiye**
