# Multi-Agent Customer Support System with CrewAI

This project demonstrates how to build an **AI-powered customer support system** using **CrewAI multi-agent architecture**.

Instead of relying on a single model, the system uses multiple specialized agents to handle different aspects of customer support, improving accuracy, structure, and reliability.

## Overview

The system simulates a real-world customer support pipeline where different agents collaborate to process and respond to user queries.

Each agent has a defined role:

- **Support Agent** – understands the customer query and generates an initial response
- **Issue Analyzer** – identifies the core problem and extracts key details
- **Response Improver / QA Agent** – refines the response for clarity, tone, and correctness

This modular design mimics how real customer support teams operate.

## Key Features

- Multi-agent collaboration using CrewAI
- Role-based task decomposition
- Structured and improved responses
- Reusable pipeline for different types of customer queries
- Easy customization for new domains

## Workflow

The system follows a sequential pipeline:

1. Analyze customer request
2. Generate initial response
3. Improve and validate the response

Each step builds on the output of the previous one.

## Technologies Used

- Python
- CrewAI
- crewai_tools
- LangChain (community)
- OpenAI GPT models
- Jupyter Notebook

## File

- `L3_customer_support.ipynb` – main implementation notebook

## Installation

Install dependencies:

```bash
pip install crewai crewai_tools langchain_community
