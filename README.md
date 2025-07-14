# Personal-Finance-Tracker
A full-stack web application to manage your personal finances efficiently — built with .NET 8 Web API and Angular.

📦 Project Overview
The Personal Finance Tracker helps individuals monitor, categorize, and analyze their income and expenses in a structured and user-friendly way. It supports financial planning, expense visualization, and savings tracking.

🧱 Tech Stack
Layer	Technology
Backend	ASP.NET Core 8.0 (Web API)
Frontend	Angular 16+
Database	SQL Server
Tools	Entity Framework Core, Swagger, Visual Studio Code

🔗 Live Demo / Screenshots
(Optional: Add screenshots of dashboard, add-transaction form, charts, etc.)

📁 Project Structure
lua
Copy
Edit
FinanceTrackerAPI/     --> .NET 8 Web API (Backend)
finance-tracker-ui/    --> Angular (Frontend)
🔧 Features
🔙 Backend (ASP.NET Core API)
Secure RESTful API with token-based auth (optional)

CRUD operations for:

Transactions

Categories (e.g., Food, Rent, Salary)

Accounts (e.g., Bank, Wallet)

Filtering by date range/category

Monthly & yearly summary endpoints

Swagger API docs for testing

🎨 Frontend (Angular)
Responsive dashboard UI

Add, edit, and delete transactions

Filter by category/date

Real-time charts (income vs expenses)

Category-wise spending breakdown

Dark/light theme toggle (optional)

🚀 How to Run Locally
✅ Prerequisites
.NET 8 SDK

Node.js & npm

Angular CLI

SQL Server (or SQL Express)

🔙 Backend Setup
bash
Copy
Edit
cd FinanceTrackerAPI
dotnet restore
dotnet ef database update   # If using EF Core migrations
dotnet run
🎨 Frontend Setup
bash
Copy
Edit
cd finance-tracker-ui
npm install
ng serve --open
📌 Future Enhancements
User authentication and role-based access

Budget planner module

Export to Excel/PDF

Email reports and reminders

PWA (Progressive Web App) support

🤝 Contributing
Feel free to fork and submit pull requests! Open to collaboration on improving features and UX.


