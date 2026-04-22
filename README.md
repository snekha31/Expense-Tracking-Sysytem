# Expense Management System

💸 Expense Management System (FastAPI + Streamlit)

A full-stack expense tracking and analytics application built with FastAPI, Streamlit, and MySQL.

Track daily expenses, analyze category spending, and visualize monthly trends — all through a clean UI backed by REST APIs.

🚀 Features
➕ Add / update daily expenses
📊 Category-wise analytics with percentage breakdown
📅 Monthly expense trends (bar chart)
🔌 REST APIs for all operations
🗄️ Persistent storage with MySQL
🧪 Easily testable via Postman / Swagger UI
🧩 Modular code structure (frontend, backend, DB helper)


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py

  Author
 Snekha Balamurali

If you found this useful, feel free to ⭐ the repo!
   ```
