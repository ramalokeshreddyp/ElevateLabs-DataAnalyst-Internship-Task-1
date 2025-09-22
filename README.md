🚀 Elevate Labs – Data Analyst Internship (Task 1)
📌 Task 1: Data Cleaning and Preprocessing
🎯 Objective

To clean and prepare a raw dataset by handling:

🟢 Missing values

🟢 Duplicates

🟢 Inconsistent formats

using tools like Excel or Python (Pandas).
This task is part of the Data Analyst Internship assessment at Elevate Labs.

🛠 Tools Used

📊 Microsoft Excel (primary tool for cleaning)

📂 Dataset: Internal sample dataset (transaction records with dates, times, payment methods, etc.)

📝 What I Did

🔍 Missing Values

Checked for nulls manually + using Excel filters.

Filled/removals based on context (e.g., filled missing payments, removed fully empty rows).

📑 Duplicates

Removed duplicate rows using Excel’s Remove Duplicates feature.

📅 Inconsistent Date Format

Standardized all dates → DD/MM/YYYY using Excel formulas:

=TEXT(K2, "dd/mm/yyyy")


Fixed entries with dashes/spaces using SUBSTITUTE + DATEVALUE.

🔤 Standardized Text Fields

Unified inconsistent labels (e.g., "Ewallet", "ewallet", "EWallet" → "Ewallet").

🔢 Data Type Checks

Ensured numeric columns (e.g., sales, amount) were correctly formatted.

Converted times to a consistent AM/PM format.

📂 Files in This Repository

📄 original_dataset.xlsx – Raw dataset before cleaning (optional, if allowed)

📄 cleaned_dataset.xlsx – Final cleaned dataset ready for analysis

📝 README.md – Documentation (this file)

✅ Outcome

🧹 Created a clean, consistent dataset from a messy input file.

💡 Learned and applied Excel cleaning techniques effectively.

📈 Prepared dataset for future analysis & visualization.

🚀 Built confidence in handling raw datasets independently.
