Day 1 – Understanding LLMs and Making Your First API Call

Overview

This task introduces the fundamentals of Large Language Models (LLMs) and demonstrates how to interact with an LLM through an API using Python, Groq, and LangChain.

The practical implementation includes developing a simple AI-powered chatbot for a home bakery and exploring prompt injection detection using Prompt Guard.

Objectives

- Understand the basic working concepts of Large Language Models.
- Establish an API connection with Groq using Python.
- Interact with an LLM using LangChain.
- Implement system prompts to control chatbot behaviour.
- Explore prompt injection detection using Prompt Guard.

Technologies and Tools

- Programming Language: Python
- Development Environment: Google Colab
- LLM API Provider: Groq
- Framework: LangChain
- Models: GPT-OSS 120B and Meta Llama Prompt Guard 2
- Concepts: Prompt Engineering, System Prompts, API Integration, and Prompt Injection Detection

Tasks Implemented

1. Groq API Integration

Established a connection between Python and the Groq API to access Large Language Models.

2. LLM Integration with LangChain

Used "ChatGroq" to send messages to an LLM and receive generated responses.

3. AI-Powered Bakery Chatbot

Developed a basic chatbot for Sweet Crumbs Home Bakery with predefined business rules.

The chatbot follows these instructions:

- Cakes are prepared on order.
- Orders require at least 24 hours' advance notice.
- Eggless cake options are available.
- Specific delivery times are never guaranteed.

4. System Prompt Implementation

Designed a system prompt to define the chatbot's role, business information, response rules, and communication style.

5. Prompt Injection Detection

Integrated Meta Llama Prompt Guard 2 to experiment with identifying potentially malicious or instruction-manipulating prompts.

Implementation Files

File| Description
"task.py"| Python source code for the practical implementation.
"agenticAI_Day1.ipynb"| Google Colab notebook containing code cells and execution results.
"README.md"| Documentation describing the task and implementation.

Key Learning Outcomes

By completing this task, I gained practical experience in:

- Connecting Python applications to external LLM APIs.
- Integrating Large Language Models using LangChain.
- Designing effective system prompts.
- Building a basic AI-powered chatbot.
- Understanding prompt injection risks and experimenting with detection models.
- Managing API credentials securely using environment variables and Colab Secrets.

Task Status

Completed – Successfully implemented and tested the Day 1 practical exercises.

Learning Journey

This is the first step in my Drive Ready – AI Agents | One Person Company (OPC) 2026 learning journey. More daily practical implementations and projects will be documented in this repository.