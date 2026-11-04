# My Budget Tracker

A budget tracker website built with plain HTML and CSS. It has a form for adding expenses and a table that shows them. At this stage the page is only the visual layout, so the Add Expense button does not do anything yet. The working version will come in later weeks with JavaScript.

## Features

- Page heading with a logo and a short description
- "How to use this tracker" section that opens and closes (`<details>` and `<summary>`)
- "Add Expense" form with an expense name, an amount and a category dropdown (Food, Transport, Rent, Entertainment, Other)
- "Your Expenses" table with 5 sample expenses
- Embedded YouTube budgeting video

## Week 3: Visual design (CSS only)

No HTML was added this week. Only `style.css` and the logo color changed.

### Color palette

| Color | Code | Used for |
| --- | --- | --- |
| Teal | `#0f766e` | Buttons, table header, focus rings, card accents |
| Dark teal | `#115e59` | Headings, button hover |
| Amber | `#f59e0b` | Accent line on the expenses card |
| Soft grey-green | `#eef3f2` | Page background |
| White | `#ffffff` | Cards |

The colors are stored as CSS variables at the top of `style.css`, so changing one value updates the whole page.

### Typography (Google Fonts)

- **Poppins** for headings, the "How to use" title and table headers
- **Inter** for body text, labels, form inputs, buttons and table cells

### Box model

The page heading, the Add Expense form and the expense table are each a separate card. Every card uses margin to space it from the next one, padding inside, a border, and `border-radius: 12px` for rounded corners. `box-sizing: border-box` is set for all elements.

### Table and form

- Table: cell padding, a teal header row, borders, alternating row colors and a row hover effect
- Form: padded inputs with rounded corners, matching input and dropdown styling, and a teal focus ring

## CSS selectors used

- Element selectors: `body`, `h1`, `h2`, `table`, `input`, `button`
- Class selectors: `.card`, `.subheading`
- ID selectors: `#budget-form`, `#expenses-list`, `#how-to-use`
- Descendant selector: `.expenses-section td:nth-child(2)`
- Direct child selector: `.add-expense-section > h2`
- Position pseudo-classes: `tbody tr:nth-child(even)`, `tbody tr td:first-child`
- Negation pseudo-class: `input:not([type="checkbox"])`
- Focus and hover states: `input:focus`, `tbody tr:hover`, `button:hover`

## Files

| File | What it does |
| --- | --- |
| `index.html` | The page structure (headings, form, table, image, video) |
| `style.css` | All the styling |
| `logo.svg` | The logo next to the heading |

## How to run it

1. Download or clone this repository.
2. Open the folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server**, or double-click `index.html` to open it in your browser. You need internet for the fonts and the video to load.

## Author

Abubakar mohamed
