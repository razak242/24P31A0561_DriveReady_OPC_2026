🍰 Sweet Crumbs – AI Bakery Order Assistant

Day 4 of Agentic AI Learning | Tools, Structured Output & Google Sheets

📌 Project Overview

Sweet Crumbs is an AI-powered bakery order assistant built using Python, LangChain and Groq.

The assistant helps customers check bakery prices, view opening hours, and place cake orders through a conversational interface. It uses Python tools to perform specific tasks and Google Sheets to store validated orders.

🎯 Project Objectives

- Build an AI agent with custom tools.
- Implement structured output using Pydantic.
- Validate customer order information.
- Connect Python with Google Sheets.
- Save confirmed customer orders automatically.
- Understand agent tool calls and execution traces.

🛠️ Technologies Used

- Python
- Google Colab
- Groq API
- LangChain
- Pydantic
- Google Sheets
- gspread

⚙️ Features

1. Price Checking

The "get_price" tool calculates the total price using the bakery menu.

2. Opening Hours

The "is_open" tool checks the bakery's opening hours.

3. Structured Order Validation

Pydantic validates customer order information, including the menu item and quantity.

4. Google Sheets Integration

The "log_order" tool saves confirmed orders to a Google spreadsheet.

5. Conversational AI

The assistant uses conversation history and a system prompt to respond to customer requests.

🍰 Bakery Menu

Item| Price
Plum Cake| ₹500
Chocolate Cake| ₹650
Cupcake| ₹80

Eggless versions are available for all cakes.

🧪 Testing

The project includes tests for:

- Price and opening-hours queries.
- Invalid menu items.
- Missing pickup dates.
- Invalid quantities.
- Structured extraction from customer messages.

🚀 How to Run

1. Open the notebook in Google Colab.
2. Add your "GROQ_API_KEY" to Colab Secrets.
3. Run the notebook cells in order.
4. Authenticate your Google account when prompted.
5. Test the assistant and verify saved orders in Google Sheets.

📚 Learning Outcomes

Through this project, I practised:

- Creating tools using LangChain's "@tool".
- Connecting tools to an AI agent.
- Defining structured data with Pydantic.
- Validating customer information.
- Integrating Google Sheets with Python.
- Inspecting agent execution traces.

📅 Learning Progress

Day 4 – Agentic AI Workshop

Learning how AI agents use tools, produce structured data and interact with external applications.

---

Built as part of my hands-on Agentic AI learning journey.