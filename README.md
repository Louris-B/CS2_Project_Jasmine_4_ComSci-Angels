# BaonBuddy: Student Expense Tracker

## Com.Sci. Angels (Group 4 · Section Jasmine)
* Magadia
* Amuale
* Rio
* Cerbo
* Bormuel
* Sarsalejo

---

### a. What problem are you trying to solve?
Many students—especially those on strict budgets or who tend to overspend—run out of money before the week or month ends because they lose track of small, daily expenses like snacks, *pamasahe*, and school supplies. Without a clear record, it is difficult to stick to a budget or save money. Today, most students rely on memory or messy, time-consuming notes to track their allowance, which often leads to forgotten purchases and poor spending habits.

### b. What are your app's features? How does the app help solve the problem?
**BaonBuddy** solves this problem by giving students one simple console app to log and manage their money:
* **Log Income:** Records daily *baon*, monthly stipends, and other allowances with the amount and date so users know their exact starting funds.
* **Log Expenses:** Tracks everyday purchases by item, category (e.g., Food, Transportation, School), amount, and date so small expenses don't go unnoticed.
* **Set Weekly Target:** Lets users set or update a maximum weekly spending limit to act as a clear budget benchmark.
* **The Spending Pipeline:** Calculates remaining weekly funds, suggests a daily spending cap, and gives a simple action plan (like cutting back on a high-spending category) to help students stay under budget.
* **Spend Summary & Savings:** Displays weekly and monthly totals, identifies which category costs the most, and calculates remaining savings.

### c. What specific data will you handle?
All user records are saved locally in a `JSON` file so data persists across sessions. Specifically, the app handles:
* **Income Data:** Source/Type (e.g., daily *baon*, stipend), Amount, and Date received.
* **Expense Data:** Item purchased (e.g., snacks, *pamasahe*), Category (Food, Transport, School), Amount spent, and Date of purchase.
* **Budget Settings:** Weekly Target (the user's maximum weekly spending limit) and menu navigation choices.
