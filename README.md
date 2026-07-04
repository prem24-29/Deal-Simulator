# 💼 Deal-Simulator — Integrated M&A Decision Platform

> **An interactive, web-based corporate transaction modeling and Sources & Uses simulator paired with an underlying financial audit spreadsheet.**

---

## 🔍 Overview
Deal-Simulator is an integrated financial decision tool designed to model corporate mergers & acquisitions (M&A). It allows analysts and students to simulate transaction structures, optimize debt/equity financing mixes, and audit transaction feasibility.

### 🌟 Key Features
*   💵 **Sources & Uses Modeling**: Calculates financing requirements, required equity contributions, and debt allocations based on deal purchase price multiples.
*   📈 **Dynamic Debt & Leverage Projections**: Computes post-deal leverage ratios (Debt/EBITDA) and debt service coverage capabilities under varying scenarios.
*   📊 **Interactive Visualization**: Uses **Chart.js** to visually compare funding sources, debt schedules, and valuation distributions.
*   📁 **Excel Audit Model**: Integrates with `Sources-Uses-Model (5).xlsx`, a pre-configured Excel workbook that calculates and audits core transaction accounting logic.

---

## 🛠️ Tech Stack
*   **Web Frontend**: HTML5, CSS3, JavaScript (ES6+), Chart.js
*   **Financial Spreadsheet Engine**: Microsoft Excel (`.xlsx` financial model)

---

## 📁 Project Structure
```text
Deal-Simulator/
├── index (1).html            # Main dashboard application page
├── deal-simulator (1).html   # Simulation panel page
├── Sources-Uses-Model (5).xlsx # Underlying Excel transaction model
└── .gitignore                # Ignores local settings and lock files
```

---

## 🚀 How to Use

### 1. Web Simulation
Open **`index (1).html`** directly in any web browser to access the M&A dashboard. Enter your transaction assumptions (Enterprise Value, EBITDA, Senior Debt Multiples, Equity Mix) to instantly simulate the deal structure, sources/uses table, and Chart.js graphics.

### 2. Excel Audit Modeling
Open the **`Sources-Uses-Model (5).xlsx`** sheet in Microsoft Excel to view the detailed formulas, purchase price allocations, and financing audit models that back the simulator's logic.
