# My Budget Tracker

A simple budget tracker website built with plain HTML and CSS. It lets you see your expenses in a table and has a form for adding new ones. At this stage it is only the visual layout, so the button does not do anything yet. The working version will come in later weeks with JavaScript.

## Features

- Page heading with a logo and a short description
- "How to use this tracker" section that opens and closes (`<details>` and `<summary>`)
- "Add Expense" form with an expense name, an amount and a category dropdown (Food, Transport, Rent, Entertainment, Other)
- "Your Expenses" table with 5 sample expenses, a colored header row, striped rows and a hover effect
- Embedded YouTube budgeting video

## Files

| File | What it does |
| --- | --- |
| `index.html` | The page structure (headings, form, table, image, video) |
| `style.css` | All the styling |
| `logo.svg` | The logo shown next to the heading |

## CSS selectors used

- Element selectors: `body`, `h1`, `table`, `input`, `button`
- Class selectors: `.card`, `.subheading`
- ID selectors: `#budget-form`, `#expenses-list`, `#how-to-use`
- Descendant selector: `.expenses-section td:nth-child(2)`
- Direct child selector: `.add-expense-section > h2`
- Position pseudo-classes: `tbody tr:nth-child(even)`, `tbody tr td:first-child`
- Negation pseudo-class: `input:not([type="checkbox"])`
- Focus state: `input:focus`, `select:focus`
- Hover state: `tbody tr:hover`, `button:hover`

## How to run it

1. Download or clone this repository.
2. Open the folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**, or just double-click `index.html` to open it in your browser.

## Author

Abubakar
