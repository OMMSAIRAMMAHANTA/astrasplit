AstraSplit - Premium Trip Manager

AstraSplit is a fast, beautiful, and highly optimized single-file web application designed to track group trip expenses and automatically calculate the smartest way to settle debts.

Built with a focus on premium UI/UX and seamless WhatsApp integration, it eliminates the headache of manual math after a trip.

✨ Key Features

🧠 Smart Settlement Engine: Uses a greedy algorithm to calculate "who owes whom". Instead of every person paying multiple small amounts, the engine optimizes debts to ensure the absolute minimum number of UPI transactions are needed.

📱 Direct WhatsApp Integration: One click generates a clean, professional, emoji-free text summary of all expenses and final settlements, then automatically opens WhatsApp ready to send to your group.

🧮 Built-in Smart Calculator: A floating glassmorphism calculator allows you to tally up multiple small expenses (e.g., snacks + tea + tickets) and directly inject the final amount into the expense form.

💎 Premium "Fintech" UI: Designed with a "Trusted Premium" color palette (Primary Blue, Soft Indigo) and modern glassmorphism (frosted glass) effects. Looks and feels like a funded SaaS startup app.

⚡ Zero-Backend & Offline Ready: Everything runs entirely in the browser using Vanilla JavaScript. No database required, no server delays, and 100% privacy.

🛠️ Tech Stack

HTML5: Semantic structure.

Tailwind CSS (via CDN): Rapid, responsive, and modern styling.

Vanilla JavaScript: DOM manipulation, transaction state management, and settlement algorithms.

Google Fonts: Inter for clean data readability and Poppins for strong, trustworthy headings.

🚀 How to Use

Open the App: Simply double-click index.html to open it in any modern web browser. No installation or setup required.

Add an Expense: * Enter what the expense was (e.g., "Auto to Khandagiri").

Enter the amount (use the built-in Calc if needed).

Select who paid from the dropdown.

Click Add to Bill.

View Live Settlements: The app instantly updates the "Total Spent" and recalculates the most efficient settlement paths.

Share Report: Click the Send Bill via WhatsApp button at the bottom. A clean summary will be generated and WhatsApp will open automatically.

📐 The Settlement Algorithm

AstraSplit uses a customized debt-simplification algorithm:

Calculates the Total Cost and the Per Head share.

Maps how much each person actually paid vs. how much they were supposed to pay.

Separates the group into two lists: Debtors (people who owe money) and Creditors (people who need to get paid).

Sorts both lists by amount and iteratively matches the largest debtor with the largest creditor until all balances reach ₹0.

🤝 Project Members (Hardcoded for convenience)

Omm Sairam Mahanta

Satyapragnya Samal

Biswaranjan Sahoo

Neeraj Behera

Designed & Built for seamless trip management.
