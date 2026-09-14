# Cold Email Generator

An AI-powered tool that extracts job details from a company career page, finds relevant portfolio projects, and generates a personalized cold email.

## Features

- Scrapes job descriptions from career pages
- Extracts role, experience, skills, and description using an LLM
- Searches portfolio projects using ChromaDB
- Generates personalized cold emails for potential clients
- Uses LangChain and Groq for AI processing

## Tech Stack

- Python
- LangChain
- Groq
- ChromaDB
- Pandas
- BeautifulSoup
- Jupyter Notebook

## Project Structure

```text
cold_email_generator/
├── email_gen.ipynb
├── my_portfolio.csv
├── requirements.txt
├── README.md
└── vectorstore/