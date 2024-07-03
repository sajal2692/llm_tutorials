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


## Setup Instructions

### Prerequisites

- Python 3.11+ (each tutorial may have its own Python version requirements)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/sajal-2692/llm_tutorials.git
cd llm_tutorials
```

### 2. Install Poetry
If you haven't installed Poetry yet, you can do so by running:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Verify the installation:
```bash
poetry --version
```

### 3. Configure Poetry
Set Poetry to create virtual environments in the project directory:

```bash
poetry config virtualenvs.in-project true
```

## Running a tutorial

Navigate to the experiment directory:
```bash
cd blog_posts/tutorial_name
```

Install dependencies:
```bash
poetry install
```

Activate the virtual environment:
```bash
poetry shell
```

Example: If the tutorial is a jupyter notebook:

Start Jupyter Notebook:
```bash
jupyter notebook
```

Open the tutorial notebook in your browser and run the cells.

When finished, close Jupyter Notebook (Ctrl+C in terminal) and deactivate the virtual environment:
```bash
exit
```

Feel free to open an issue on Github if you run into issues, or if the instructions are unclear.

Happy learning! 💪

