Agentic AI – Day 2: Prompts, Memory & Python for AI Agents

📌 Project Overview

This repository contains my hands-on learning and implementation from Day 2 of my Agentic AI learning journey.

The focus of this practical was understanding how to create better LLM interactions using structured prompts, few-shot examples, JSON outputs, conversation memory, and Python programming concepts.

As part of the practical implementation, I built a simple AI-powered customer support chatbot for Sweet Crumbs Home Bakery using Python and the Groq API.

🎯 Learning Objectives

- Understand LLM message roles: "system", "user", and "assistant".
- Create structured system prompts using Role, Facts, Rules, and Format.
- Implement few-shot prompting with example conversations.
- Generate and process structured JSON responses.
- Understand conversation history and memory management.
- Work with Python dictionaries and JSON.
- Create functions using type hints and docstrings.
- Understand and implement decorators.
- Handle errors using "try-except" blocks.

🛠️ Technologies Used

- Python
- Google Colab
- Groq API
- Large Language Models (LLMs)
- JSON
- Python Decorators
- Exception Handling

🤖 Project: Sweet Crumbs AI Chatbot

Built a simple conversational chatbot for a fictional home bakery.

Key Features

- Answers customer questions about bakery products.
- Provides product prices from a predefined menu.
- Supports questions about eggless cake options.
- Uses system prompts to control chatbot behaviour.
- Maintains conversation history to provide contextual responses.
- Uses a Python function to calculate product prices.
- Handles API errors with appropriate messages.
- Uses a decorator to log function calls.

Sample Menu

Product| Price
Plum Cake| ₹500
Chocolate Cake| ₹650
Cupcake| ₹80

Sample Function Output

[LOG] get_price('cupcake', 6) -> 480
Total for 6 cupcakes: 480

⚙️ How to Run

1. Clone this repository:

git clone https://github.com/razak242/24P31A0561_DriveReady_OPC_2026.git

2. Open the notebook in Google Colab.

3. Install the required dependencies if they are not already available:

!pip install groq openai

4. Configure your Groq API key securely.

5. Run the notebook cells in order.

6. Start interacting with the Sweet Crumbs AI chatbot.

Note: Never upload your API key or other credentials to GitHub.

📚 What I Learned

This practical helped me understand how Python concepts connect with LLM-based applications.

I learned that an AI chatbot needs more than just an API call. It also needs clear instructions, structured information, conversation history, reusable functions, and proper error handling.

🚀 Learning Journey

- Day 1: How LLMs Work and Your First API Call
- Day 2: Prompts, Memory and the Python Agents Need

👨‍💻 Author

Abdul Razak Shaik

B.Tech Computer Science and Engineering Student
