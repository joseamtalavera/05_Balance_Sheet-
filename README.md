# AcmeWidgetCorp Balance Sheet

This project is a simple HTML page that displays a balance sheet for a fictional company, AcmeWidgetCorp. The balance sheet includes data for the years 2019, 2020, and 2021.

## Structure

The HTML document is structured as follows:

- `<head>`: Contains meta information and links to an external CSS file for styling.
- `<body>`: Contains the main content of the webpage, structured within a `<main>` tag and a `<section>` tag.
- `<h1>`: Displays the company name and the title of the document.
- `<div id="years">`: Displays the years for which the balance sheet data is available.
- `<div class="table-wrap">`: Contains three tables, each representing a different part of the balance sheet: Assets, Liabilities, and Net Worth.

Each table has the following structure:

- `<caption>`: Describes the content of the table.
- `<thead>`: Contains the headers for each column.
- `<tbody>`: Contains the data rows. Each row represents a different item in the balance sheet, and includes a description and the values for each year.

## Styling

The document uses several CSS classes to style the content:

- `.flex`: Arranges the company name and the title of the document in a row.
- `.year`: Styles the year labels.
- `.table-wrap`: Styles the container of the tables.
- `.data`: Styles the rows that contain the balance sheet data.
- `.total`: Styles the rows that contain the total values.
- `.current`: Highlights the values for the current year.
- `.sr-only`: Hides certain elements from visual rendering, but makes them accessible to screen readers.

## Accessibility

The document uses ARIA (Accessible Rich Internet Applications) attributes to improve accessibility. The `aria-hidden` attribute is used to hide the year labels from screen readers, as this information is already included in the tables. The `.sr-only` class is used to include additional information for screen readers that is not visually displayed.