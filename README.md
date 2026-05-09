# Expense Tracker MCP Server

A FastMCP-based Expense Tracker Server built with Python and SQLite for managing and automating expense tracking workflows.

---

# Features

* Expense management using SQLite database
* FastMCP server integration
* Lightweight and easy setup
* Local database support
* Automation-friendly architecture
* Python-based backend

---

# Tech Stack

* Python
* FastMCP
* SQLite3
* UV Package Manager

---

# Project Setup

## 1. Clone the Repository

```bash
git clone https://github.com/debjit2002/expense-tracker-mcp-server.git
cd expense-tracker-mcp-server
```

---

## 2. Create Virtual Environment

Create a Python virtual environment using `uv`:

```bash
uv venv
```

Activate the environment:

### macOS / Linux

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

---

## 3. Install UV

If `uv` is not installed:

### macOS / Linux

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Windows

```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Verify installation:

```bash
uv --version
```

---

## 4. Install Dependencies

Install FastMCP:

```bash
uv pip install fastmcp
```

Install SQLite3:

```bash
uv pip install sqlite-utils
```

Or install all dependencies together:

```bash
uv pip install fastmcp sqlite-utils
```

---

# Running the MCP Server

Run the FastMCP development server:

```bash
uv run fastmcp dev main.py
```

---

# Project Structure

```bash
expense-tracker-mcp-server/
│
├── main.py
├── database.db
├── requirements.txt
├── README.md
└── .venv/
```

---

# Database

This project uses SQLite as the local database.

SQLite is lightweight, serverless, and perfect for local expense tracking applications.

---

# Future Improvements

* User authentication
* Expense categories
* Monthly analytics
* AI-powered financial insights
* Cloud database support
* Dashboard integration

---

# Author

Debjit Acharjee

GitHub: [https://github.com/debjit2002](https://github.com/debjit2002)
