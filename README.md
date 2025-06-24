## 🏦 Flask Banking Application

## 🚀 Objectives
- Enable basic banking operations (Create Account, Deposit, Withdraw, Check Balance)

- Use SQLite for lightweight and persistent storage

- Build a modular and user-friendly Flask web application

- Demonstrate full-stack development including Docker deployment
## 🛠️ Tech Stack
- Backend Framework: Flask (Python)

- Database: SQLite

- Frontend: HTML (via Flask’s render_template_string)

- Containerization: Docker
Docker

## 🧩 Steps Included
1. Initialize Database

- Creates bank.db with a table for accounts (id, name, balance)

2. Flask Routes

`/create' – Create a new account

'/balance' – Check account balance

'/deposit' – Add funds to an account

'/withdraw' – Withdraw funds from an account

''/statement'– Placeholder for future transaction statement feature

3. Form-based Web UI

- Basic HTML and inline styles to create a simple UI layout

4. Dockerized Setup

- Dockerfile provided for containerized deployment on any platform

   ## 💡 Key Insights Key 
- Minimalist and beginner-friendly code to understand full web app lifecycle

- Stateless REST-style operations using simple HTML forms

- Effective use of SQLite for persistent local storage

- Clear route structuring for modular code growth

- Demonstrates how to combine frontend/backend in a lightweight environment

  ## 📦 How to Run the  (Locally without Docker)
  '''
# Install Requirements (only Flask is needed)
pip install flask
# Run the App
python app.py
# Access in Browser
http://localhost:5005
'''
## 📦 How to Run the App  (Locally using Docker)
  '''
# Build Image
docker build -t flask-banking-app .
# Run Container
docker run -p 5005:5005 flask-banking-app
# Access in Browser
http://localhost:5005
'''
## 🔮 Future Enhancements
- Add transaction history/statement functionality

- Implement user authentication

- Improve UI with templates and styling frameworks

- Add input validation and error handling

- Support multi-user concurrency

  concurrency

##  📁 Project Structure
'''
├── app.py            # Main Flask app
├── bank.db           # SQLite DB (auto-generated)
└── Dockerfile        # Docker container instructions
'''







