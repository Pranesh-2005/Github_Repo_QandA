# Github_Repo_QandA

# Github_Repo_QandA 🚀

Welcome to **Github_Repo_QandA** — a powerful tool to ask questions and get insightful answers about any GitHub repository! This project leverages AI and interactive frontend technologies to help users analyze codebases, understand software architecture, and clarify project details with ease.

---

## 📚 Introduction

**Github_Repo_QandA** is designed for developers, contributors, and curious minds who want to interactively query GitHub repositories. With a combination of Python backend (using Gradio, LangChain, and Azure OpenAI) and a modern JavaScript frontend, the app provides an intuitive interface for engaging with code repositories.

---

## ✨ Features

- **Clone & Analyze Repos:** Easily clone any public GitHub repository for instant analysis.
- **AI-Powered Q&A:** Get natural language answers to your questions using Azure OpenAI models.
- **Interactive Web UI:** User-friendly interface powered by Gradio and a responsive frontend.
- **Environment Configuration:** Securely manage API keys and endpoints via `.env` files.
- **Cross-Platform:** Works on any system with Python 3.8+ and Node.js.

---

## 🛠️ Installation

### 1. Backend Setup

```bash
# Clone the repository
git clone https://github.com/your_username/Github_Repo_QandA.git
cd Github_Repo_QandA

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt
```

### 2. Frontend Setup

Navigate to the `frontend/` directory and make sure you have Node.js installed.

```bash
cd frontend
# Install frontend dependencies if any (e.g. npm install)
```

### 3. Environment Variables

Create a `.env` file in the root directory:

```env
AZURE_OPENAI_API_KEY=your_api_key
AZURE_OPENAI_ENDPOINT=your_endpoint
CHAT_DEPLOY=your_deployment_name
```

---

## 🚦 Usage

### 1. Start the Backend

```bash
python app.py
```

### 2. Launch the Frontend

Open `frontend/index.html` in your browser. The app will connect to the backend and you can start asking questions about any GitHub repo!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Please check the [issues page](https://github.com/your_username/Github_Repo_QandA/issues) first and feel free to submit pull requests.

> **How to contribute:**
> 1. Fork the repository
> 2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
> 3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
> 4. Push to the branch (`git push origin feature/AmazingFeature`)
> 5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Made with ❤️ for the open-source community!**

---

> **Files included:**
> - `app.py` (Python backend)
> - `frontend/script.js` (Frontend JavaScript logic)

---

Feel free to customize and expand this tool for your needs! 😊

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/selvaganesh19/Github_Repo_QandA