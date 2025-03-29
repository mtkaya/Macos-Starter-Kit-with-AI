🧠 macOS Developer Starter Kit

A lightweight yet powerful starter kit to set up your macOS environment for Python development, especially for AI, machine learning, and LLM projects. This kit includes a setup script to streamline your tools, packages, environments, and test files — fully compatible with both Anaconda and Visual Studio Code.

🚀 What's Included?

✅ Homebrew for system-level package management

✅ Pyenv for Python version control

✅ Visual Studio Code extensions setup

✅ AI/LLM-focused requirements.txt

✅ Hugging Face Transformers test example (llm_test.py)

✅ One-step environment installer (setup.sh)

⚙️ Quick Install

git clone https://github.com/yourusername/macos-dev-starter.git
cd macos-dev-starter
chmod +x setup.sh
./setup.sh

Note: If you're running this on a fresh macOS system, you may need to install Xcode Command Line Tools first:

xcode-select --install

📂 Repository Structure

macos-dev-starter/
├── README.md          # Project overview and setup instructions
├── setup.sh           # Main installation script
├── requirements.txt   # Python packages for AI/LLM development
└── llm_test.py        # Sample script to validate setup

🧪 Run the Test Script

Once installation is complete, verify everything by running:

python llm_test.py

This uses a Hugging Face pipeline to perform sentiment analysis on a sample input text.

🛠 Requirements Installed via setup.sh

Python packages:

numpy, pandas, matplotlib, scikit-learn

jupyterlab, torch, transformers, sentence-transformers

langchain, llama-index, openai, bitsandbytes, peft, accelerate

VS Code Extensions:

Python

Jupyter

GitHub Copilot

👨‍💻 Author

Created by Mehmet Tuğrul KayaSoftware Project Manager | AI/NLP Developer

📄 License

MIT License or Creative Commons Attribution (your choice — to be added here).

Happy coding on your Mac! 🍏💻

