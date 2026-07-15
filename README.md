#  Hello LLM - Groq API with Python

A beginner-friendly Generative AI project demonstrating how to interact with a Large Language Model (LLM) using the **Groq API** and Python. This project sends a prompt to the Llama 3.3 70B model and displays the generated response.

---

## 📌 Project Overview

This project covers the fundamentals of:

- Connecting to the Groq API
- Securely storing API keys using `.env`
- Sending prompts to an LLM
- Receiving and displaying AI-generated responses
- Managing dependencies with `uv`

---

## 🚀 Features

- 🔑 Secure API key management using `python-dotenv`
- 🤖 Uses **Llama 3.3 70B Versatile** model
- 💬 Sends custom prompts to the LLM
- ⚡ Fast inference using Groq API
- 📦 Dependency management with `uv`

---

## 🛠️ Tech Stack

- Python 3.11+
- Groq Python SDK
- python-dotenv
- uv

---

## 📂 Project Structure

```text
day1/
│
├── .venv/
├── .env
├── hello_llm.py
├── main.py
├── pyproject.toml
├── uv.lock
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

```bash
cd <repository-name>/week1/day1
```

---

### 2. Create a virtual environment

Using **uv**

```bash
uv venv
```

Activate it

#### Windows

```bash
.venv\Scripts\activate
```

#### macOS/Linux

```bash
source .venv/bin/activate
```

---

### 3. Install dependencies

```bash
uv pip install groq python-dotenv
```

or

```bash
pip install groq python-dotenv
```

---

## 🔐 Environment Variables

Create a `.env` file inside the project directory.

```env
GROQ_API_KEY=your_groq_api_key
```

> **Note:** Never commit your `.env` file to GitHub.

---

## ▶️ Run the Project

```bash
python hello_llm.py
```

or

```bash
python main.py
```

---

## 💻 Example Code

```python
message = {
    "role": "user",
    "content": "Write a poem about the beauty of nature."
}
```

---

## 📝 Example Output

```text
Nature whispers through the trees,
Dancing softly with the breeze.
Mountains stand in silent grace,
While rivers carve the earth's embrace...
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Setting up a Python project with `uv`
- Using the Groq Python SDK
- Working with Large Language Models
- Making Chat Completion API requests
- Managing secrets using `.env`
- Parsing and displaying LLM responses

---

## 📦 Dependencies

- groq
- python-dotenv
