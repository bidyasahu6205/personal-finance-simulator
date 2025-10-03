# 💰 Personal Finance Simulator (Salesforce Project)

## 📌 Overview  
The **Personal Finance Simulator** is a Salesforce-based educational tool that helps users understand the basics of **personal finance**.  

Users can:  
- 📝 Create a financial profile (income, expenses, savings goals).  
- 📊 Simulate savings, loans, and investments over time.  
- 📈 View interactive dashboards showing financial growth or decline.  
- ❓ Use **“What If” scenarios** (e.g., *What if I increase savings by 10%?*).  
- 🏆 Unlock **achievements** for making good financial decisions.  

This project is built as part of the **PwC Salesforce Launchpad Training** to practice real-world Salesforce application development.  

---

## 🚀 Features  
1. **User Profile Setup** – Income, Expenses, Goals  
2. **Simulation Engine** – Savings, Loans, Investments growth/shrink over time  
3. **Dashboards & Reports** – Visualize financial trends  
4. **What-If Tool** – Try different financial decisions  
5. **Gamification** – Achievements & badges for good choices  

---

## 🛠️ Tech Stack  
- ☁️ **Salesforce (Developer Org / Trailhead Playground)**  
- ⚡ **Apex** (for simulation logic)  
- 🎨 **Lightning Web Components (LWC)** for interactive UI  
- 📊 **Salesforce Reports & Dashboards** for visualization  
- 🗂️ **GitHub** for version control  
- 💻 **VS Code + Salesforce Extensions** for local development  

---

## 👥 Team  
| Role | Member | Responsibility |
|------|---------|----------------|
| 👨‍💻 Developer 1 | **Bidya** | GitHub management, Apex backend (simulation logic) |
| 👩‍💻 Developer 2 | **Soumyashree** | UI/UX in Lightning Web Components + Dashboards |

---

## 📂 Project Structure  
```bash
personal-finance-simulator/
│── README.md
│── force-app/                  # Salesforce source code
│    ├── main/
│    │   ├── default/
│    │   │   ├── objects/       # Custom objects (Income, Expense, Goals, etc.)
│    │   │   ├── classes/       # Apex classes
│    │   │   ├── lwc/           # Lightning Web Components
│    │   │   └── dashboards/    # Reports and dashboards
│── .gitignore

🔧 Setup Instructions
1. Clone Repo
git clone https://github.com/<your-username>/personal-finance-simulator.git
cd personal-finance-simulator

2. Authorize Salesforce Org
sfdx force:auth:web:login -a PersonalFinanceOrg

3. Push Code to Org
sfdx force:source:push -u PersonalFinanceOrg

4. Open Org in Browser
sfdx force:org:open -u PersonalFinanceOrg
