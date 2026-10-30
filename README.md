
# 🚀 RepoGenius AI — GitHub Repository Analyzer

An AI-powered web application that analyzes public GitHub repositories and generates AI-powered insights.

## ✨ Features

- 🔍 Analyze public GitHub repositories
- 📊 View repository statistics, stars, forks, and open issues
- 💻 Explore programming languages and repository files
- 🤖 Generate AI-powered repository insights using Ollama
- 🌐 Responsive web interface
- 🔒 Secure configuration using environment variables

## 🛠️ Tech Stack

- Python
- Flask
- GitHub REST API
- Ollama — Qwen 2.5
- HTML and CSS
- JavaScript

## ⚙️ Requirements

- Python
- GitHub Personal Access Token
- Ollama installed locally
- Qwen 2.5 model

## 🚀 Setup Instructions

### 1. Clone the repository

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository URL after uploading the project to GitHub.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Create a virtual environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```powershell
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and add your GitHub token:

```env
GITHUB_TOKEN=your_github_token_here
```

**Never share or upload your actual token.**

### 5. Start Ollama

Make sure Ollama is running and the `qwen2.5:7b` model is available.

```powershell
ollama run qwen2.5:7b
```

### 6. Run the application

```powershell
python app.py
```

Open your browser at:

http://127.0.0.1:5000

## 🔐 Security

- Keep `.env` private.
- Never upload API tokens or secrets.
- Keep `.venv` out of version control.

## 🎯 Project Goal

RepoGenius AI combines web development, REST APIs, repository metadata extraction, and locally hosted AI to make GitHub repositories easier to understand.

## 🔮 Future Improvements

- Code quality analysis
- Downloadable analysis reports
- Improved error handling
- Online deployment

---

**Built with Python, Flask, GitHub API, and Ollama.**
