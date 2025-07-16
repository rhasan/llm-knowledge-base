# llm-knowledge-base

A curated, evolving knowledge base for Large Language Model (LLM) research, engineering, and best practices.

## 🚀 Project Overview

**llm-knowledge-base** is a personal project aimed at collecting, organizing, and sharing key information, comparisons, and insights about state-of-the-art LLMs (Large Language Models) and related technologies.

- ✍️ **Markdown Articles:** In-depth and concise documentation on LLM architectures, techniques, and research (e.g., GPT-4.1 vs. GPT-4o, Agents, Chain-of-Thought, Context windows, etc.).
- 📓 **Jupyter Notebooks:** (Planned) Interactive explorations, experiments, and code snippets.
- 📚 **Knowledge Focus:** Documentation is written to be precise and actionable, targeting practitioners and enthusiasts.

---

## 📁 Project Structure

```text
.
├── docs/                  # Markdown articles about LLMs and related topics
├── notebooks/             # (Future) Jupyter notebooks with code and experiments
├── pyproject.toml         # Project metadata and dependencies
├── LICENSE                # License text file
└── README.md              # This file
````

---

## 🛠️ Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/rhasan/llm-knowledge-base.git
cd llm-knowledge-base
```

### 2. Create and activate a virtual environment using [uv](https://github.com/astral-sh/uv)

```sh
uv venv
source .venv/bin/activate    # Or .venv\Scripts\activate on Windows
```

### 3. Install project dependencies

```sh
uv pip install
```

* This will install everything listed in your `pyproject.toml` dependencies.

### 4. Add new dependencies (if needed)

```sh
uv add <package-name>
```

* This command updates your `pyproject.toml` and lockfile.

### 5. Explore the documentation in the `docs/` folder!

---

## 📝 Example Article

See [`docs/gpt4.1-vs-gpt4o.md`](docs/gpt4.1-vs-gpt4o.md) for a sample comparison focusing on **Agents**, **Chain-of-Thought (CoT)**, and **Context**.

---

## ✨ Contributing

This project is currently personal and experimental. Feel free to open an issue or discussion if you have ideas or suggestions!

---

## 📄 License

[MIT](LICENSE)

---

> **Maintainer:** Rakeb Hasan

