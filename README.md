# HTML Fundamentals Assignment – Documentation

## 1. 📄 What Each HTML Element Does

- `<!DOCTYPE html>`: Declares the document type and version (HTML5).
- `<html>`: Root element of the HTML page.
- `<head>`: Contains meta information, title, and links to styles/scripts.
- `<title>`: Sets the browser tab title.
- `<body>`: Contains all visible content of the page.
- `<h1>` to `<h6>`: Define headings (largest to smallest).
- `<p>`: Paragraph of text.
- `<a>`: Anchor tag to create hyperlinks.
- `<img>`: Displays images.
- `<ul>`: Unordered (bullet) list.
- `<ol>`: Ordered (numbered) list.
- `<li>`: List item within a list.
- `<table>`: Creates a table.
- `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`: Structure table headers and data.
- `<form>`: Wraps user input elements.
- `<input>`: Accepts various types of user inputs.
- `<select>`: Dropdown menu.
- `<option>`: Options inside a `<select>`.
- `<textarea>`: Multi-line text input.
- `<label>`: Associates a text label with a form field.
- Semantic HTML5 elements:
  - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`: Provide meaningful structure and improve accessibility.

---

## 2. 🎯 Why I Chose Specific Input Types

- `type="text"`: For entering general text like name and message.
- `type="email"`: Ensures a valid email format; enables browser validation.
- `type="tel"`: For phone numbers with optional validation.
- `type="radio"`: Allows selection of only one inquiry type from a group.
- `type="checkbox"`: Used for multiple preferred contact methods.
- `type="date"`: Lets users pick a date with a calendar.
- `type="range"`: Creates a slider, used for urgency level.
- `<select>`: For selecting country codes or reason for contact from a list.

---

## 3. 🧭 How My Navigation Structure Works

A consistent navigation bar appears on every page using `<nav>` and `<a>` tags:

- **Home** → `portfolio.html`
- **About** → `about.html`
- **Contact** → `contact.html`

These links are placed inside the `<nav>` element to improve accessibility and semantic clarity. They use **relative paths** to connect the HTML pages.

---

## ✅ Notes

- All pages follow valid HTML5 structure.
- Forms include validation attributes (`required`, `pattern`, etc.).
- Alt text is added for accessibility on all images.
- Semantic HTML is used wherever applicable.

