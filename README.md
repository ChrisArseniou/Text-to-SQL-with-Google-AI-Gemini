# Text-to-SQL Query Generator with Google AI Gemini

A Python tool that converts natural language text into SQL queries using Google's Gemini AI and executes them on a database.

## Features
- **Natural Language to SQL**: Convert plain English queries into SQL using Gemini.
- **Database Interaction**: Execute generated SQL on PostgreSQL/MySQL/SQLite.
- **Schema-Aware**: Context-aware query generation based on your DB schema.
- **Safety Checks**: Basic SQL injection prevention.

## Prerequisites
- Python 3.9+
- Google Gemini API key ([Get it here](https://ai.google.dev/))
- Database credentials (if using remote DB)

## Installation
```bash
git clone https://github.com/yourusername/text-to-sql-gemini.git
cd text-to-sql-gemini
pip install -r requirements.txt
add the Google API key in the .env
