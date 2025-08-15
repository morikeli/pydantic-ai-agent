# Tavily + Pydantic AI

# Overview
I used this program to learn and utilize Tavily API and Pydantic AI. The program prompts a user for an input and returns results based on the results fetched from the internet.

## 👩‍💻 Developer Instructions

1. Clone the repository:
```bash
  git clone github.com/morikeli/pydantic-ai-agent.git
  cd pydantic-ai-agent
```

2. Ensure you have Python 3.10+ installed.
3. Install uv (dependency manager):

    Use the commands below to install uv on your machine.
    
    Linux/macOS
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
    
    Windows
    ```powershell
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```
  
  ---
  **INFO ABOUT UV**
  
  What is uv?
  
  `uv` is an extremely fast Python package and project manager, written in Rust.
  
  Highlights
  - 🚀 A single tool to replace pip, pip-tools, pipx, poetry, pyenv, twine, virtualenv, and more.
  - ⚡️ 10-100x faster than pip.
  - 🗂️ Provides comprehensive project management, with a universal lockfile.
  - ❇️ Runs scripts, with support for inline dependency metadata.
  - 🐍 Installs and manages Python versions.
  - 🛠️ Runs and installs tools published as Python packages.
  - 🔩 Includes a pip-compatible interface for a performance boost with a familiar CLI.
  - 🏢 Supports Cargo-style workspaces for scalable projects.
  - 💾 Disk-space efficient, with a global cache for dependency deduplication.
  - ⏬ Installable without Rust or Python via curl or pip.
  - 🖥️ Supports macOS, Linux, and Windows.
  
  >uv is backed by Astral, the creators of Ruff.
  
  Follow the uv's [docs](https://docs.astral.sh/uv/) to install and learn more about uv.
  
  ---
  
5. Install dependencies from `pyproject.toml` and `uv.lock`
```bash
uv sync
```
 
5. Run the application
```bash
   uv run jupyter notebook
```


## 🤝 Contributions
Contributions are welcome! 🎉
Please fork the repository, create a new branch for your feature or fix, and submit a pull request.

Steps:
```git
git checkout -b <your-branch-name>
git commit -m "feat: added a new feature"
git push origin -u <your-branch-name>
```

## 🐞 Issues / Bugs

If you encounter any problems or bugs, open an issue on [GitHub Issues](https://github.com/morikeli/pydantic-ai-agent)

Kindly include:

- Steps to reproduce (how did you encounter the bug or what triggers the bug)
- Expected behavior
- Screenshots/logs if relevant


Don't forget to star ⭐ the repo.

