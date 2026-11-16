# My Budget Tracker - HTML & CSS Project

## What I Built
A Budget Tracker webpage where you can see your expenses in a table and add new expenses with a form.

## What Each Part Does

**index.html:**
- Header with logo image and title
- Expense Table with thead, tbody, th, td and 5 sample expenses
- Add Expense Form with form, select dropdown, inputs with matching IDs, and button type="button"
- Details/Summary collapsible "How to use" section
- Iframe with YouTube budgeting tips video

**style.css:**
- Table styling with border-collapse, padding, colored header, nth-child(even) alternating rows, and hover effect
- Descendant selector: .expenses-section td
- Direct child selector: .add-expense-section > form > input
- Negation: input:not([type="submit"])
- Focus: input:focus, select:focus
- Button with cursor: pointer

## How to Run
Open index.html in any browser. No server needed.