# AI Agent – Automated Data Analysis & Email Reporting

## 💡 Project Objective

The objective of this project is to demonstrate how AI Agents can automate data retrieval, conversational data analysis, and email reporting by integrating multiple applications into a single intelligent workflow.

**Built with:** n8n | OpenAI | Google Sheets | Gmail


### n8n AI Agent Workflow
<img width="395" height="254" alt="workflow" src="https://github.com/user-attachments/assets/fba2c837-4b76-459d-a43c-cde4a15cfacc" />

# 🤖 AI Data Analyst Agent – Automated Data Analysis & Email Reporting

An AI-powered Data Analyst Agent built using **n8n, OpenAI, Google Sheets, and Gmail**. It allows users to interact with spreadsheet data through a chat interface, perform customer data analysis, and receive automated analytical reports via email.

## 📸 Project Workflow

### n8n AI Agent Workflow

![AI Data Analyst Agent Workflow](https://github.com/user-attachments/assets/ebcdaa11-4c80-476e-a26d-ce00a6b5491a)

## 🛠️ Tools & Technologies

- **n8n** – Workflow automation and orchestration.
- **OpenAI Chat Model** – AI-powered query understanding and data analysis.
- **System Prompt** – Defines the AI Agent's role, instructions, behaviour, and analysis guidelines.
- **Simple Memory** – Maintains conversational context across interactions.
- **Google Sheets** – Data source and retrieval.
- **Gmail** – Automated email reporting.

## ⚙️ How It Works

1. **Chat Trigger:** User submits a query through the n8n chat interface.
2. **AI Agent:** Receives and interprets the user's request.
3. **System Prompt:** Provides instructions and defines how the AI Agent should understand requests, interact with tools, and generate responses.
4. **OpenAI Chat Model:** Processes the query and generates intelligent responses.
5. **Simple Memory:** Maintains conversational context for follow-up questions.
6. **Google Sheets Integration:** Retrieves relevant customer records from the spreadsheet.
7. **Data Analysis:** The AI Agent analyses the retrieved information based on the user's query.
8. **Gmail Integration:** Sends the generated analytical report directly to the user's email.

## 🚀 Key Features

- Conversational data analysis through an AI Agent.
- System prompt-based agent instructions.
- Google Sheets integration for dynamic data retrieval.
- AI-powered customer data analysis.
- City-wise customer analysis.
- Customer information retrieval.
- Conversational memory for contextual interactions.
- Automated analytical report generation.
- Gmail integration for email reporting.
- End-to-end workflow automation using n8n.

## 📊 Data Analysis

The AI Agent analyses customer information using the following fields:

| Field | Description |
|---|---|
| CUSTOMERNAME | Customer name |
| CITY | Customer city |

### Sample Analysis

The agent can respond to queries such as:

- How many customers are from each city?
- Show the customers belonging to a particular city.
- Retrieve customer details from Google Sheets.
- Generate a city-wise customer summary.
- Send the analytical report through Gmail.


