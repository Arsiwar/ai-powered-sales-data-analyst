# AI-Powered Sales Data Analyst

An automated sales analytics solution built with **n8n, Python, JavaScript, and AI**.

## Project Overview

This project automates sales data analysis and provides an AI-powered assistant that answers questions about sales performance.

It combines data extraction, Python-based analysis, structured data storage, an AI Agent, and an interactive web dashboard.

## Project Objectives

- Automate sales data processing and analysis.
- Calculate key sales performance indicators.
- Store analytical results in a structured Data Table.
- Use an AI Agent to answer questions based on available sales data.
- Visualize sales insights through an interactive dashboard.

## Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Python | Data analysis |
| JavaScript | Data processing and dashboard generation |
| HTML / CSS | Dashboard structure and styling |
| Chart.js | Data visualization |
| OpenAI | AI-powered analysis |
| n8n Data Tables | Store analysis results |
| Webhook | Dashboard access |

## Workflow Architecture

The project consists of two main workflows.

### 1. Sales Data Analysis & AI Agent

- Import sales data from a CSV file.
- Extract and process the data.
- Perform analysis using Python.
- Calculate total sales, sales by product line, sales by country, monthly sales, and top customers.
- Store the results in an n8n Data Table.
- Connect an AI Agent to the Data Table to answer users' questions.

### 2. Sales Dashboard

- Retrieve analytical results from the Data Table.
- Process and organize the results using JavaScript.
- Generate an HTML dashboard.
- Display key performance indicators and sales charts.
- Expose the dashboard through a production Webhook URL.

## Data Analysis

The project includes the following analyses:

- Total Sales
- Sales by Product Line
- Sales by Country
- Monthly Sales Trends
- Top 10 Customers

## AI Agent

The AI Agent acts as a sales analysis assistant.

It can answer questions such as:

- What is the total sales?
- Which product line generates the highest sales?
- Which country generates the highest sales?
- What are the monthly sales trends?
- Who are the top customers?

The assistant retrieves the available analytical results from the Data Table before answering.

## Dashboard Preview

### Sales Dashboard
![Sales Dashboard](screenshots/sales-dashboard.png)

### Data Analysis Workflow
![Data Analysis Workflow](screenshots/data-analysis-workflow.png)

### Sales Dashboard Workflow
![Sales Dashboard Workflow](screenshots/sales-dashboard-workflow.png)

### AI Agent
![AI Agent](screenshots/ai-sales-agent.png)

## Key Results

- Total Sales: 10,032,628.85
- Highest-performing Product Line: Classic Cars
- Highest-performing Country: USA

## How to Run

1. Install and configure n8n.
2. Import the project workflows.
3. Configure the required OpenAI credentials.
4. Prepare the sales CSV file.
5. Create the required Data Table.
6. Execute the data analysis workflow.
7. Run the AI Agent workflow to ask questions.
8. Publish and access the Sales Dashboard using its Production Webhook URL.

## Project Skills

Data Analytics | Workflow Automation | Python | JavaScript | AI Agents | Data Visualization | n8n

---

**Developed as a practical project combining Data Analytics, Automation, and Artificial Intelligence.**
