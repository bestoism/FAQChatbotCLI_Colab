# FAQChatbotCLI

A simple CLI-based FAQ Chatbot built in Python. This chatbot can answer frequently asked questions based on a text file (`faq.txt`) and responds directly via the terminal. If a question isn't recognized, it will politely decline to answer.

---

## Features

* **Loads Predefined FAQ:** Easily loads questions and answers from a plain text file (`faq.txt`).
* **Command Line Interface (CLI):** Seamless interaction with users directly via the terminal.
* **Exact Question Matching:** Matches user questions to stored answers precisely, ignoring case and leading/trailing whitespace for flexibility.
* **Graceful Unknown Question Handling:** Politely declines to answer questions that are not recognized in its knowledge base.

---

## Requirements

* **Python 3.x:** Ensure you have Python version 3 or higher installed.
* **No External Libraries:** Built purely with standard Python libraries, so no additional installations are needed.

---

## 🚀 How to Use

### 1. Prepare Your FAQ Data

Create or edit the `faq.txt` file in the project directory. Add your questions and answers using the following format:
