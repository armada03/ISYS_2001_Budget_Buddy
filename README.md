# Budget Buddy – Smart Finance Assistant (Damara Arsana - 20732192)

<!-- BADGES:START -->
[![curtin](https://img.shields.io/badge/-curtin-f57c00?style=flat-square)](https://github.com/topics/curtin)
[![ai-assistant](https://img.shields.io/badge/-ai--assistant-blue?style=flat-square)](https://github.com/topics/ai-assistant)
[![finance](https://img.shields.io/badge/-finance-blue?style=flat-square)](https://github.com/topics/finance)
[![gradio](https://img.shields.io/badge/-gradio-blue?style=flat-square)](https://github.com/topics/gradio)
[![python](https://img.shields.io/badge/-python-3776ab?style=flat-square)](https://github.com/topics/python)
[![rag](https://img.shields.io/badge/-rag-blue?style=flat-square)](https://github.com/topics/rag)
<!-- BADGES:END -->

## Project Overview

Budget Buddy is a Smart Finance Assistant built for the ISYS2001 Final Programming Project. The assistant helps users understand their spending habits by analysing CSV transaction data, generating spending insights, answering finance questions, retrieving budgeting guidance, and calculating savings goals.

The project was developed using Python, Google Colab, pandas, hands-on-ai, and Gradio.

## Main Features

- CSV transaction data cleaning
- Spending analysis by category
- Financial recommendation report
- Finance chatbot using hands-on-ai
- Simple RAG system for budgeting guidance
- Custom savings goal calculator tool
- Gradio web interface
- Step 6 foundation and integration testing

## Dataset

The main dataset used is:

```text
data/transactions.csv

The CSV file should contain these columns:

Date
Amount
Category
Description

Example:

Date	Amount	Category	Description
2024-08-01	$45.50	Groceries	Woolworths Weekly Shop
2024-08-02	$12.00	Transport	Opal Card Top-up
2024-08-03	$89.95	Entertainment	Concert Tickets
How to Run the Notebook
Open smart_finance_assistant.ipynb in Google Colab.
Run the setup cells to install the required packages.
Run the hands-on-ai configuration cell.
Run the data cleaning, spending analysis, recommendation, chatbot, RAG, and savings calculator cells.
Run the Gradio UI cell.
Open the Gradio public link.
Test each tab in the interface.
Hands-on-AI Configuration

The notebook uses this configuration:

import os

os.environ['HANDS_ON_AI_SERVER'] = 'https://ollama.locollm.org'
os.environ['HANDS_ON_AI_MODEL'] = 'gemma3:4b'
os.environ['HANDS_ON_AI_API_KEY'] = 'Curtin2026ISYS20015002'
Gradio Interface

The Gradio app includes four tabs:

1. CSV Spending Analysis

Allows the user to upload a transaction CSV file. Budget Buddy cleans the data, analyses spending by category, and generates a financial recommendation report.

2. Finance Chatbot

Allows the user to ask finance-related questions. The chatbot uses a friendly Budget Buddy finance personality.

3. RAG Financial Guidance

Retrieves relevant budgeting guidance before generating a finance response.

4. Savings Goal Calculator

Calculates how many months are needed to reach a savings goal based on current savings, monthly contribution, and target amount.

Sample Inputs and Outputs
CSV Spending Analysis

Input:

transactions.csv

Example output:

BUDGET BUDDY FINANCIAL RECOMMENDATION REPORT

Total positive spending: AUD 910.80
Total refunds or negative transactions: AUD -37.50
Average positive transaction: AUD 50.60
Highest spending category: Groceries
Finance Chatbot

Input:

I spend too much on coffee, what should I do?

Example output:

Budget Buddy gives practical advice about tracking coffee spending, setting a weekly limit, and replacing some purchases with homemade coffee.
Savings Goal Calculator

Input:

Current savings: 500
Monthly contribution: 250
Target amount: 2000

Output:

Estimated time to reach goal: 6.0 months
Testing

The notebook includes Step 6 testing with:

Normal transaction data
Dollar signs in amount values
Refunds and negative amounts
Missing values
Invalid dates
Invalid amount values
Missing required columns
Spending calculation validation
Financial recommendation validation
Savings calculator edge cases
Full workflow integration tests
Gradio empty input handling
AI Collaboration

AI was used throughout the project as a development assistant. The AI collaboration is documented in diary.md with weekly evidence packages from Weeks 8–12.

The diary includes:

AI prompts
AI responses
Screenshots of AI collaboration
Context for each interaction
Reflection on what worked, what changed, and what was learned
Repository Structure
smart-finance-assistant/
│
├── smart_finance_assistant.ipynb
├── README.md
├── diary.md
├── data/
│   └── transactions.csv
├── AI-CONVERSATIONS/
│   └── AI EVIDENCE/
│       └── screenshots
├── sample_transactions.csv
└── LICENSE
Developer

Created by Damara Arsana for ISYS2001.
