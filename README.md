HTML Fundamentals Assignment - Documentation
--------------------------------------------

1. What each HTML element does:

- <!DOCTYPE html>: Declares the document type and version (HTML5).
- <html>: The root element of an HTML page.
- <head>: Contains metadata about the HTML document (title, links, styles).
- <title>: Specifies the title of the webpage (shown in the browser tab).
- <body>: Contains all visible content on the webpage.
- <h1> to <h6>: Define headings from most to least important.
- <p>: Paragraph text.
- <a>: Anchor tag for hyperlinks.
- <img>: Embeds an image.
- <ul>: Unordered list.
- <ol>: Ordered list.
- <li>: List item inside ul or ol.
- <table>: Creates a table.
- <thead>, <tbody>, <tr>, <th>, <td>: Used inside a table to structure rows and columns.
- <form>: Wraps all form fields.
- <input>: Accepts user input (text, email, radio, etc.).
- <select>: Creates a dropdown menu.
- <option>: Specifies options inside a dropdown.
- <textarea>: Multiline text input.
- <label>: Defines labels for form elements.
- <header>, <nav>, <main>, <section>, <article>, <footer>: Semantic elements used for better structure and accessibility.

2. Why I chose specific input types:

- type="text": For basic text fields like Name and Message.
- type="email": Ensures correct email format and allows browser validation.
- type="tel": Accepts numeric values for phone numbers.
- type="radio": Allows the user to select only one inquiry type.
- type="checkbox": Allows multiple preferred contact methods.
- type="date": Lets the user select a date using a date picker.
- type="range": Used for rating urgency levels between 1 to 5.
- <select>: Useful for choosing a country code or reason for contact from a predefined list.

3. How my navigation structure works:

Each page has a navigation bar with links using <a> tags:
- Home: Links to portfolio.html
- About: Links to about.html
- Contact: Links to contact.html

These links are placed inside a <nav> element for semantic clarity and accessibility.
Clicking any link will take the user to the corresponding page using relative file paths.
 
