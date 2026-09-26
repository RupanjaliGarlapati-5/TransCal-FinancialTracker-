# 💰 TransCal — Financial Tracker

A web-based personal finance tracker designed to help users record, organize, and analyze their income and expenses in one place.

TransCal provides a simple interface for managing financial transactions, viewing spending patterns, and understanding overall financial activity through visual summaries.

---

## ✨ Features

- 💵 Track income and expenses
- 📝 Add and manage financial transactions
- 📄 Import transaction data from CSV/PDF files
- 🏦 Supports transaction records from UPI and bank statements
- 🏷️ Categorize transactions
- 📊 Visualize financial data using charts
- 🔎 View transaction details
- 📈 Monitor income and spending patterns
- ☁️ Firebase-based data storage
- 📱 Simple and user-friendly interface

---

## 🔄 Project Workflow

```mermaid
flowchart TD
    A[👤 User] --> B[💰 TransCal Dashboard]

    B --> C{Transaction Source}

    C -->|Manual Entry| D[📝 Enter Transaction]
    C -->|CSV / PDF| E[📄 Upload Statement]

    E --> F[📥 Extract Transaction Data]

    D --> G[💳 Transaction Details]
    F --> G

    G --> H[🏷️ Categorize Transaction]

    H --> I[☁️ Store in Firebase]

    I --> J[📊 Financial Dashboard]

    J --> K[💵 Income Analysis]
    J --> L[💸 Expense Analysis]
    J --> M[📈 Charts & Summaries]

    K --> N[🔍 Financial Insights]
    L --> N
    M --> N
🧠 How It Works
1. Add Financial Transactions

Users can enter transaction details such as:

Description
Amount
Date
Payment mode
Income / Expense
Category
2. Import Transaction Statements

The application can work with transaction data obtained from:

UPI transactions
Bank statements
CSV files
PDF files

Imported information can be used to build a consolidated transaction history.

3. Categorize Transactions

Transactions can be organized into meaningful categories to make spending patterns easier to understand.

4. Store Financial Data

Firebase is used to store and manage transaction-related data.

5. Analyze Finances

The dashboard presents financial information through summaries and charts, helping users understand:

Total income
Total expenses
Spending distribution
Transaction history
Financial trends
📊 Dashboard

The dashboard provides a centralized view of the user's financial activity.

It can display:

💵 Income
💸 Expenses
💳 Transaction History
🏷️ Categories
📈 Charts & Financial Summary
🛠️ Tech Stack
Technology	Purpose
HTML	Web page structure
CSS	Styling and layout
JavaScript	Application logic
React	Frontend development
Firebase	Data storage and backend services
CSV / PDF Processing	Transaction data import
Charts	Financial data visualization

📁 Project Structure
TransCal-Financial-Tracker/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── ...
│
├── package.json
├── README.md
└── ...

The exact structure may vary depending on the current project setup.

🚀 Key Highlights
💳 Unified Transaction Tracking

Instead of maintaining financial records across multiple sources, TransCal provides a centralized place to organize transaction information.

📄 Statement Import

Transaction records can be imported from supported CSV/PDF statement files, reducing the need for completely manual entry.

📊 Visual Analytics

Charts provide a quick visual understanding of income, expenses, and spending categories.

☁️ Firebase Integration

Firebase provides cloud-based storage for the application's financial transaction data.

🔮 Future Enhancements
🤖 AI-powered automatic transaction categorization
💬 AI financial assistant/chatbot
📊 Advanced spending analytics
🔔 Budget and spending alerts
🎯 Monthly budget tracking
📱 Improved mobile responsiveness
📈 Personalized financial insights
🔐 Enhanced authentication and security
▶️ How to Run
1. Clone the repository
git clone <YOUR_GITHUB_REPOSITORY_URL>
2. Navigate to the project
cd TransCal-Financial-Tracker
3. Install dependencies
npm install
4. Start the development server
npm run dev

The application will then be available through the local development URL provided by the development server.

📸 Project Preview

Add screenshots of the following screens here:

🏠 Dashboard
💰 Transaction page
📊 Financial charts
📄 Statement upload
🏷️ Transaction categories

Example:

![TransCal Dashboard](screenshots/dashboard.png)
🎯 Project Objective

The goal of TransCal is to simplify personal financial tracking by bringing transaction management, statement data, categorization, and financial visualization together in a single web application.

👩‍💻 Author

Rupanjali Garlapati

B.Tech — Computer Science and Engineering

GitHub
