# LangChain Quickstart Agent

## Description
This repository contains a basic AI agent built using **LangChain** and **Claude** following the official LangChain Quickstart tutorial.  
The goal of this project is to understand how an agent interacts with tools and a language model.

This project is intended as a **learning and practice exercise** before building more advanced systems such as Retrieval-Augmented Generation (RAG).

---

## Features
- Uses a Large Language Model (Claude)
- Implements a simple tool (weather function)
- Demonstrates agent reasoning and tool invocation

---

## 📂 Project Structure

```text
langchain-quickstart-agent/
├── main.py
├── requirements.txt
├── .gitignore
├── .env
└── README.md
```

---

## Requirements

- Python 3.9 or higher
- An Anthropic API key

---

## Setup
1. Create and activate a virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

![image](https://github.com/CamiloFdez/Introduction-to-Creating-RAGs-with-OpenAI-langchain-quickstart-agent/blob/main/images/installingDependencies.PNG)


3. Set up your environment variables
Create a `.env` file in the root directory and add your Anthropic API key:

```env
ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

4. Run the agent

```bash
python main.py
```

Example output:

```
> Enter a question: What is the weather like in New York?
> Agent: I will use the weather tool to find out the current weather in New York.
> Agent: The current weather in New York is sunny with a temperature of 75°F.
```

![image](https://github.com/CamiloFdez/Introduction-to-Creating-RAGs-with-OpenAI-langchain-quickstart-agent/blob/main/images/runningMain.PNG)

---

## Technologies Used
- **Python**: Programming language
- **LangChain**: Framework for building language model applications
- **Claude**: Large language model by Anthropic
- **dotenv**: For managing environment variables

---