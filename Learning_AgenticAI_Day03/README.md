Day 3 of Learning Agentic AI | Sweet Crumbs Home Bakery

Building an AI Customer Support Assistant with LangChain and Groq

As part of Day 3 of my Agentic AI learning journey, I explored how Large Language Models (LLMs), prompt engineering, automated testing, and agent concepts work together to build an intelligent customer support assistant.

For this practical assignment, I continued working with Sweet Crumbs Home Bakery, a fictional home bakery business, and developed an AI-powered assistant to handle customer queries about products, pricing, and order policies.

Project Overview

The objective of this project was to understand how to build, configure, test, and improve an LLM-powered application using Python and LangChain.

The chatbot uses a custom SYSTEM prompt containing business information and behavioural instructions to generate relevant and consistent customer responses.

Technologies & Tools

- Python
- Google Colab
- LangChain
- Groq API
- GPT-OSS-120B
- CSV-based testing

Key Implementations

1. SYSTEM Prompt Engineering

- Defined the chatbot's role and responsibilities.
- Added five business facts and three behavioural rules.
- Established guidelines to prevent incorrect pricing and unconfirmed business promises.

2. LLM Chain Development

- Built a LangChain pipeline using "ChatPromptTemplate".
- Integrated the Groq LLM.
- Implemented conversation history to maintain context.

3. Automated Testing

- Created "tests.csv" containing 10 customer questions and expected response keywords.
- Developed a Python testing function to evaluate chatbot responses.
- Measured performance using test pass rates.

4. Prompt Improvement Experiment

- Modified the SYSTEM prompt by adding a price-calculation instruction.
- Reran the automated tests.
- Compared the baseline and improved prompt results.

5. Temperature Experiment

Tested the model with a temperature setting of 1.0 and executed the evaluation twice.

Experiment| Temperature| Pass Rate
Run 1| 1.0| 60%
Run 2| 1.0| 60%

Observation: Both experiments achieved the same pass rate, demonstrating that a change in temperature does not necessarily result in a different overall test score.

6. Understanding AI Agents

Explored the differences between:

- Plain Python code
- A single LLM call
- AI agents

Also created two Python functions to prepare for future agent-tool integration:

- "get_price()" – Calculates product prices based on quantity.
- "check_order_availability()" – Checks the bakery's 24-hour advance order policy.

Repository Structure

agenticAI-Day3/
│
├── agenticAI_Day3.ipynb
├── tests.csv
└── README.md

Key Learning Outcomes

By completing Day 3, I gained practical experience in:

- Writing structured SYSTEM prompts.
- Building LLM chains using LangChain.
- Managing conversation history.
- Evaluating LLM responses through automated testing.
- Experimenting with prompt improvements and temperature settings.
- Understanding the fundamentals of AI agents.
- Writing reusable Python functions for business operations.

Learning Journey: Agentic AI – Day 3
Project: Sweet Crumbs Home Bakery AI Assistant