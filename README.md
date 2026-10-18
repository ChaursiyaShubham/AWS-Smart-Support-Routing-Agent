# AWS-Smart-Support-Routing-Agent
AWS Smart Support & Routing Agent

Project Overview

The AWS Smart Support & Routing Agent is a Python-based customer support ticket routing prototype built using Streamlit. It accepts customer queries, analyzes the text, identifies the likely support category, and suggests the appropriate support team.

The project demonstrates how automated ticket classification can help organize customer support requests.

Features

- Simple and interactive web interface.
- Accepts customer support messages.
- Classifies tickets into support categories.
- Suggests an appropriate support team.
- Displays demo processing time.
- Beginner-friendly Python implementation.

Technologies Used

- Python
- Streamlit

Support Categories

- Billing & Finance
- Technical Support
- Account Support
- General Support

Installation and Setup

1. Clone the Repository

git clone https://github.com/ChaursiyaShubham/AWS-Smart-Support-Routing-Agent.git
cd AWS-Smart-Support-Routing-Agent

2. Install Dependencies

pip install -r requirements.txt

3. Run the Application

streamlit run app.py

The application will open in your browser.

How It Works

1. Enter a customer support message.
2. Click the Analyze and Route Ticket button.
3. The application identifies a likely support category.
4. It recommends a support team for the ticket.
5. The demo processing time is displayed.

Project Scope

This is an educational prototype demonstrating rule-based ticket classification. Actual AWS services and the Strands Decider model are not integrated unless explicitly configured in a future version. The displayed processing time represents local demo execution, not verified AWS response latency.

Future Improvements

- Integrate an AI-based ticket classification model.
- Connect AWS services for real support workflows.
- Store tickets in a database.
- Add ticket history and status tracking.

Author

Shubham Kumar

License

No license has been selected for this repository yet.
