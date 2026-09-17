# GENAI_project

# OpenAI Python Projects

A collection of beginner-friendly **Python projects using the OpenAI API**.
This repository demonstrates different AI concepts such as text generation, classification, code explanation, moderation, sentiment analysis, multiple responses, and streaming responses.

## 🚀 Technologies Used

* Python
* OpenAI API
* OpenAI Python SDK
* python-dotenv
* UV Package Manager
* Virtual Environment
* VS Code

## 📂 Project Structure

```text
openai_project/
│
├── codes/
│   ├── text/
│   │   ├── config.py
│   │   ├── chatbot.py
│   │   ├── classification.py
│   │   ├── code_explainer.py
│   │   ├── error_handling.py
│   │   ├── incontext_learning.py
│   │   ├── moderator.py
│   │   ├── multi_responses.py
│   │   ├── sentiment_analyzer.py
│   │   └── stream_responses.py
│   │
│   └── .env
│
└── README.md
```

## ✨ Features

### 1. AI Chatbot

Uses the OpenAI API to generate answers to user questions.

### 2. Text Classification

Classifies companies into categories such as:

* Technology
* Pharmaceutical
* Finance

### 3. Code Explainer

Accepts programming-related input and explains what the code does in simple language.

### 4. Error Handling

Demonstrates handling errors while working with the OpenAI API.

### 5. In-Context Learning

Demonstrates how examples can be provided to an AI model so that it understands the expected response format.

### 6. Content Moderation

Uses the OpenAI moderation API to identify potentially unsafe content.

### 7. Multiple Responses

Generates multiple AI responses for the same prompt and demonstrates how different outputs can be handled.

### 8. Sentiment Analyzer

Analyzes text and identifies whether the overall sentiment is positive, negative, or neutral.

### 9. Streaming Responses

Demonstrates streaming AI responses token-by-token instead of waiting for the complete response.

## 🛠️ Installation

### Step 1: Install Python

Make sure Python is installed on your system.

Check the version:

```bash
python --version
```

### Step 2: Create a Virtual Environment

This project uses `uv` for environment and package management.

```bash
uv venv --python 3.14.0 openai_project
```

Activate the environment on Windows:

```bash
openai_project\Scripts\activate
```

### Step 3: Install Dependencies

```bash
uv pip install openai python-dotenv
```

The project uses the OpenAI Python SDK and `python-dotenv` for environment variables.

## 🔑 API Key Setup

Create a `.env` file inside the project folder.

Add:

```env
OPENAI_API_KEY=your_api_key_here
```

**Important:** Never upload your real API key to GitHub.

Add `.env` to your `.gitignore` file:

```gitignore
.env
.venv/
__pycache__/
```

## ▶️ How to Run

Navigate to the folder containing the Python files:

```bash
cd codes
cd text
```

Run any project using:

```bash
python chatbot.py
```

Other examples:

```bash
python classification.py
python code_explainer.py
python error_handling.py
python incontext_learning.py
python moderator.py
python multi_responses.py
python sentiment_analyzer.py
python stream_responses.py
```

## 📌 Example Outputs

### Classification

```text
Technology: Microsoft Corporation, Apple Inc, Amazon.com, Inc
Pharmaceutical: Roche Holding AG, Pfizer Inc, Johnson & Johnson
Finance: JPMorgan Chase & Co., Bank of America Corporation
```

### Code Explanation

```text
This code asks the user for a number, checks whether it has any
divisors from 2 up to one less than itself, and prints whether
the number is prime or not.
```

### Sentiment Analysis

```text
Sentiment: Positive
```

## 🎯 Learning Objectives

Through this project, I learned how to:

* Connect Python applications with the OpenAI API
* Work with API keys and environment variables
* Create and use virtual environments
* Install Python packages using UV
* Generate AI-based text responses
* Perform text classification
* Analyze sentiment
* Implement content moderation
* Generate multiple responses
* Stream AI responses
* Handle API-related errors
* Build simple AI-powered Python applications

## 🔒 Security

API keys should always be stored in environment variables.

Do not commit the `.env` file to GitHub.

If an API key is accidentally exposed, revoke it and create a new key.

## 👩‍💻 Author

**Sania Mumtaz**

BCA Graduate | Python | SQL | Frontend Development | AI & Data Analytics

## 📄 License

This project is created for learning and educational purposes.
