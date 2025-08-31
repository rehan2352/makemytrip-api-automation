# 🧳 MakeMyTrip Tourism API - Automation Testing

This project simulates a **tourism packages API** (like MakeMyTrip) using `json-server` and validates it with **Postman + Newman** automated tests.  
It includes assertions for **status codes, response times, data validation, error handling**, and generates **HTML reports** with `newman-reporter-htmlextra`.

---

## 🚀 Features
- Fake REST API with `json-server`
- Postman collection with 14+ test assertions
- Automated testing using `Newman`
- Fancy HTML reports via `htmlextra`
- Ready to integrate with CI/CD (GitHub Actions / Jenkins)

---

## 📦 Installation & Setup

Clone the repository:
```bash
git clone https://github.com/USERNAME/makemytrip-tourism-api-pro.git
cd makemytrip-tourism-api-pro
Install dependencies:

bash
Copy code
npm install
Start the JSON server:

bash
Copy code
npm run start
API will be available at 👉 http://localhost:3001/packages

🧪 Run Tests
Run Postman tests with Newman:

bash
Copy code
npm run test:api
Generate HTML report:

bash
Copy code
newman run postman/collection.json -e postman/environment.local.json -r htmlextra
Report will be saved inside the newman/ or reports/ folder.

📊 Test Report
Dashboard Screenshot

Detailed HTML Report
👉 View Report

📂 Project Structure
pgsql
Copy code
makemytrip-tourism-api-pro/
│── postman/
│   ├── collection.json
│   └── environment.local.json
│── reports/
│   ├── screenshot.png
│   └── newman-report.html
│── db.json
│── package.json
│── README.md
🛠️ Tech Stack
Node.js

json-server

Postman + Newman

newman-reporter-htmlextra

📌 Notes
Reports are static snapshots; re-run Newman to update them.

Can be integrated with CI/CD pipelines (GitHub Actions, Jenkins) for automation.

👨‍💻 Author: Mohammad Rehan Fazal
📅 Last Updated: August 2025


