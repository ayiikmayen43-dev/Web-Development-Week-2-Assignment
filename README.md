# SpendWise - Personal Budget Tracker

SpendWise is a responsive web application designed to help users track their income, record expenses, manage categories, and review personal finance insights. Built as part of a web development learning journey, this project showcases core HTML5 structure, CSS styling, layout selectors, multimedia integration, and interactive elements.

---

## What Each Part Does

### 1. Structure & Semantics (`index.html`)
* **Header Section (`<header>` & `<img>`)**: Features the app title, subtitle, and a custom logo image with descriptive alt text for accessibility.
* **Help Section (`<details>` & `<summary>`):** Provides a clean, interactive collapsible accordion explaining how users can navigate and utilize the tracker.
* **Add Expense Form (`<form>` & `<select>`):** Contains input fields for the expense name and amount, a styled `<select>` dropdown menu with 5 categories (*Food, Transport, Rent, Entertainment, Other*), and an interactive submission button.
* **Expense Table Section (`<table>`, `<thead>`, `<tbody>`):** Organizes historical financial data across four columns (Name, Amount, Category, Date) featuring 5 rows of sample records.
* **Multimedia Section (`<iframe>`)**: Embeds a helpful personal finance and budgeting YouTube video using a responsive container.

### 2. Styling & Design (`styles.css`)
* **Base Layout & Colors:** Implements a clean color palette (`#f4f6f9` background, `#2c3e50` dark slate primary elements) with centered max-width constraints and card-like container padding.
* **Advanced CSS Selectors:** 
  * *Direct Child Selector (`.add-expense-section > form > div`)* to cleanly space out form wrappers.
  * *Negation Pseudo-class (`input:not([type="button"])`)* to target and style text/number inputs without affecting action buttons.
  * *Focus States (`input:focus`, `select:focus`)* to provide a visual highlight glow when users interact with fields.
  * *Descendant Selector (`.expense-table-section th`)* to style table headings.
  * *Position Pseudo-class (`tr:nth-child(even)`)* for alternating row zebra striping.
* **Interactive Polish:** Adds `cursor: pointer` hand states to buttons and smooth background color transitions on table rows during `:hover`.
* **Responsive Video:** Utilizes a fluid 16:9 aspect-ratio wrapper for the embedded YouTube video.

---

## How to Run the Project
1. Clone or download this repository to your local machine.
2. Open the project folder in **Visual Studio Code**.
3. Use the **Live Server** extension to open `index.html` and view the app live in your browser.
