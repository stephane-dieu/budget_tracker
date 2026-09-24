
# Personal Budget & Expense Tracker

## Project Description

This project is a simple Personal Budget and Expense Tracker built with HTML and CSS. It was developed from the Budget Tracker created in Week 1 and upgraded in Week 2 with a structured expense table, an improved expense form, multimedia content, an interactive information section, and advanced CSS selectors.

## Files

### index.html

The `index.html` file provides the structure of the Budget Tracker. It includes:

- A main heading and budget tracker icon
- An Add Expense form
- Expense name, amount, category, and date fields
- A category dropdown with five options
- An Add Expense button
- An expense table containing five sample expenses
- A collapsible instructions section
- An embedded budgeting video

### style.css

The `style.css` file controls the appearance of the project. It includes:

- Page and section styling
- Form styling
- Table borders and cell spacing
- A colored table header
- Alternating table row colors
- Table row hover effects
- Input focus effects
- Button styling
- Advanced CSS selectors

## Advanced CSS Selectors

The project uses several advanced CSS selectors:

1. Descendant selector:
   `#expenses td`

2. Direct child selector:
   `.expense-section > form`

3. Position-based pseudo-class:
   `tr:nth-child(even)`

4. Negation pseudo-class:
   `input:not([type="submit"])`

5. Focus pseudo-class:
   `input:focus`

## Future Improvements

The Add Expense button is not connected to JavaScript yet. In a future week, JavaScript will be used to make the form interactive and allow users to add new expenses dynamically.