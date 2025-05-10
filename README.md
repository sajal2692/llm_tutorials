# LLM Tutorials

Welcome to the LLM Tutorials repository! This repository contains various tutorials on large language models (LLMs) designed to complement the blog posts hosted on [sajalsharma.com](https://sajalsharma.com/posts/). Each tutorial is organized inside its own directory, under the `blog_posts` directory for now.

## Repository Structure
```
llm_tutorials/
│
├── blog_posts/
│   ├── tutorial1/
│   │   ├── pyproject.toml
│   │   └── tutorial.ipynb
│   │
│   ├── tutorial2/
│   │   ├── pyproject.toml
│   │   └── tutorial.ipynb
│   │
│   └── …
│
├── .gitignore
└── README.md
```

---

## Setup Instructions

### Prerequisites

- Python 3.11+ (each tutorial may have its own Python version requirements)
- Git
- uv (replacing Poetry)

### 1. Clone the Repository

```bash
git clone https://github.com/sajal-2692/llm_tutorials.git
cd llm_tutorials
```

### 2. Install uv

If you haven't installed uv yet, you can do so using the official installer:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Alternatively, install via pip:

```bash
pip install uv
```

Verify the installation:
```bash
uv --version
```

---

## Running a Tutorial

1️⃣ Navigate to the tutorial directory:
```bash
cd blog_posts/tutorial_name
```

2️⃣ Install dependencies:
```bash
uv venv    # Create a virtual environment in the directory
uv pip install -r requirements.txt  # OR: use uv sync if you maintain a lockfile
```

> Note: If the tutorial has a `pyproject.toml` (most of them do), you can also run:
```bash
uv sync  # Install the project with its dependencies
```

3️⃣ Run the tutorial:

For example, if the tutorial is in a jupyter notebook, you can run:
```bash
uv jupyter notebook
```

Open the tutorial notebook in your browser and run the cells.

When finished, close Jupyter Notebook (`Ctrl+C` in terminal).

---

If you encounter any issues or unclear steps, feel free to open an issue on GitHub.

Happy learning! 💪