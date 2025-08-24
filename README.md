# DPO Economics Calculator

A user-friendly Excel-based calculator designed to help educational institutions and program managers assess the economic viability of creating new Continuing Professional Education (DPO) programs.

## 📖 Overview

Launching a new DPO program involves significant financial planning and risk assessment. This project addresses the challenge by transforming a complex, error-prone Excel spreadsheet into an intuitive and guided tool. Our calculator enables users to input various cost and revenue parameters for a proposed DPO program and instantly receive a detailed financial breakdown to determine its profitability.

## ✨ Features

*   **Guided Input Page:** A clean, organized data entry sheet with clear labels and instructions.
*   **Intelligent Calculation Engine:** Automatically computes total costs, revenue, and net profit based on user inputs.
*   **Modular Cost Breakdown:** Allows for detailed budgeting by breaking down the program into individual modules.
*   **Dynamic Discount System:** Includes functionality to model the financial impact of different discount strategies on the program's overall economics.
*   **Comprehensive Output Report:** A dedicated results page that clearly displays key financial metrics and a final verdict on profitability.
*   **"Foolproof" Validation:** Implements data validation rules to prevent common user input errors and ensure calculation integrity.
*   **Integrated User Guide:** Built-in instructions to assist users through the data entry process, making the tool accessible to non-experts.
*   **Pre-configured Resources:** Includes a dedicated sheet for managing a list of instructors and their hourly rates for easy cost calculation.

## 🛠️ Tech Stack

*   **Platform:** Microsoft Excel

## 🚀 How to Use

This calculator offers two distinct workflows: a simpler **Aggregated Model** and a more detailed **Modular Model**. Follow the steps below to get started.

### Quick Start: Aggregated Model (Simplified)

For a quick, high-level estimate of your DPO program's economics.

1.  **Read the Guide:** Begin on the **`Instruction`** sheet. It contains a navigational guide and essential tips for users.
2.  **Define the Program:** Navigate to the **`Учебный план`** sheet. to input the overall structure of your educational plan.
3.  **Input Financial Data:** Go to the **`Фин. модель`** sheet. Here, enter all your cost and revenue assumptions:
    *   Number of students, tuition fees.
    *   Partner discount parameters.
    *   All other operational and marketing expenses.
    *   **All user-input cells are highlighted in green.**
4.  **View the Result:** Check the **`Форма Калькуляции`** sheet to see the final aggregated profit/loss calculation.

### Detailed Analysis: Modular Model (Recommended)

For a precise, granular financial breakdown of your program by individual module.

1.  **Read the Guide:** Start with the **`Instruction`** sheet for navigation help.
2.  **Define Each Module:** Go to the **`Учебный план (модули)`** sheet. Input the detailed structure for each of your program's modules (up to 10 modules are pre-configured).
3.  **Input Financial Data per Module:** Navigate to the **`Фин. модель (модули)`** sheet.
    *   Enter fixed, one-time costs at the top of the sheet.
    *   The sheet will automatically pull module-specific details (like duration) from the previous sheet.
    *   Input module-varying costs (e.g., instructor fees per module) in the dedicated sections for each module.
4.  **View the Detailed Result:** The final, detailed profitability calculation, aggregated from all modules, is displayed on the **`Форма Калькуляции (модули)`** sheet.


## 👨‍💻 Team

This project was a collaborative effort by:
*   **Dmitry Malyuzhantsev:** Lead developer of the core cost calculation logic and module breakdown; team coordinator.
*   **Ivan Zolotunov:** Designed and implemented the input sheet structure and the final report formatting.
*   **Roman Galimov:** Created the user guide and developed the marketing cost calculation mechanics.
*   **Kirill Reshchuk:** Defined project goals and objectives, handled project design, and prepared the final presentation.
*   **Andrey Egorov:** Implemented data validation ("foolproofing") and managed the instructor database and payment sheet.

## 📄 License

This project is licensed under the Apache License 2.0.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

**Keywords:** `education` `economics` `calculator` `excel` `vba` `dpo` `business-planning` `financial-model` `continuing-education`
