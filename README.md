# 🧠 macOS Developer Starter Kit

A lightweight yet powerful starter kit to set up your macOS environment for Python development, especially for AI, machine learning, and LLM projects. This kit includes a setup script to streamline your tools, packages, environments, and test files — fully compatible with both Anaconda and Visual Studio Code.

![Platform](https://img.shields.io/badge/platform-macOS-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🚀 What's Included?

- ✅ Homebrew for system-level package management
- ✅ Pyenv for Python version control
- ✅ Visual Studio Code extensions setup
- ✅ AI/LLM-focused `requirements.txt`
- ✅ Hugging Face Transformers test example (`llm_test.py`)
- ✅ One-step environment installer (`setup.sh`)

---

## ⚙️ Quick Install

```bash
git clone https://github.com/yourusername/macos-dev-starter.git
cd macos-dev-starter
chmod +x setup.sh
./setup.sh
```

> 💡 If you're running this on a fresh macOS system, you may need to install Xcode Command Line Tools first:
> ```bash
> xcode-select --install
> ```

---

## 📂 Project Structure

```bash
macos-dev-starter/
├── README.md          # Project overview and setup instructions
├── setup.sh           # Main installation script
├── requirements.txt   # Python packages for AI/LLM development
└── llm_test.py        # Sample script to validate setup
```

---

## 🧪 How to Test

After setup is complete, you can run the following to verify your environment:

```bash
python llm_test.py
```

This will execute a sentiment analysis pipeline using Hugging Face's `transformers` and display results on sample text.

---

## 📦 Tools & Packages Installed

- **Python packages:**
  - `numpy`, `pandas`, `matplotlib`, `scikit-learn`
  - `jupyterlab`, `torch`, `transformers`, `sentence-transformers`
  - `langchain`, `llama-index`, `openai`, `bitsandbytes`, `peft`, `accelerate`

- **VS Code Extensions:**
  - Python
  - Jupyter
  - GitHub Copilot

---

## 👨‍💻 Author

Created by **Mehmet Tuğrul Kaya**  
Software Project Manager | AI/NLP Developer  
[Medium Profile](https://medium.com/@mehmettugrulkaya)

---

## 📄 License

MIT License or Creative Commons Attribution (choose your preferred license before publishing).

---

Happy coding on your Mac! 🍏💻

