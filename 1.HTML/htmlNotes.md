# HTML Interview Notes (Most Used Tags)

## 1. Basic Structure Tags

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

- `<!DOCTYPE html>`: Declares HTML5 document.
- `<html>`: Root element of the page.
- `<head>`: Metadata (not visible on UI).
- `<body>`: Visible content.

---

## 2. Metadata Tags (SEO + Browser Behavior)

- `<title>`: Page title (browser tab).
- `<meta>`: Metadata.
  - `charset="UTF-8"`
  - `name="description"`
  - `name="viewport" content="width=device-width, initial-scale=1.0"`

- `<link>`: External resources (CSS, icons).
- `<style>`: Internal CSS.
- `<script>`: JavaScript.

**Interview Note:** Meta tags improve SEO and responsiveness.

---

## 3. Text Content Tags

- `<h1>` to `<h6>`: Headings (importance decreases).
- `<p>`: Paragraph.
- `<br>`: Line break (self-closing).
- `<hr>`: Horizontal rule.
- `<strong>`: Important text (semantic).
- `<b>`: Bold (visual only).
- `<em>`: Emphasized text.
- `<i>`: Italic (visual).
- `<span>`: Inline container.
- `<div>`: Block-level container.

**Interview Tip:** Prefer semantic tags (`strong`, `em`) over purely visual ones.

---

## 4. Links and Media

### Anchor

```html
<a href="https://example.com" target="_blank">Visit</a>
```

- `href`: URL
- `target="_blank"`: Opens in new tab

### Images

```html
<img src="image.jpg" alt="description" />
```

- `alt`: Accessibility + SEO (mandatory)

### Media

- `<audio>`
- `<video>`
- `<source>`

---

## 5. Lists

### Unordered List

```html
<ul>
  <li>Item</li>
</ul>
```

### Ordered List

```html
<ol>
  <li>Item</li>
</ol>
```

### Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>Markup Language</dd>
</dl>
```

---

## 6. Tables

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jayant</td>
      <td>26</td>
    </tr>
  </tbody>
</table>
```

- `<table>`: Table container
- `<tr>`: Row
- `<th>`: Header cell
- `<td>`: Data cell

---

## 7. Forms (Very Important for Interviews)

```html
<form action="/submit" method="POST">
  <input type="text" name="username" />
  <input type="password" name="password" />
  <button type="submit">Submit</button>
</form>
```

### Common Input Types

- `text`
- `password`
- `email`
- `number`
- `radio`
- `checkbox`
- `file`
- `date`
- `submit`

### Other Form Tags

- `<label>`
- `<textarea>`
- `<select>`
- `<option>`
- `<fieldset>`
- `<legend>`

**Interview Note:** `name` attribute is required for form submission.

---

## 8. Semantic HTML (Highly Asked)

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

**Why Semantic HTML?**

- Better SEO
- Better accessibility
- Cleaner code

---

## 9. Inline vs Block Elements

### Block Elements

- `<div>`
- `<p>`
- `<h1>`
- `<ul>`
- `<li>`

### Inline Elements

- `<span>`
- `<a>`
- `<img>`
- `<strong>`

---

## 10. Attributes (Core Concept)

```html
<input type="text" placeholder="Enter name" required />
```

Common attributes:

- `id`
- `class`
- `style`
- `src`
- `href`
- `alt`
- `title`
- `disabled`
- `readonly`

---

## 11. Accessibility (A11y)

- Use `alt` for images
- Use `<label for="id">`
- Use semantic tags
- `aria-*` attributes

---

## 12. HTML Interview One-Liners

- HTML is **not case-sensitive**
- HTML5 introduced semantic tags
- HTML does **not** support logic
- CSS handles styling, JS handles behavior
- HTML is parsed top-to-bottom

---

## 13. Common Interview Questions

**Q: Difference between `<div>` and `<span>`?**

- `div`: Block
- `span`: Inline

**Q: Difference between `id` and `class`?**

- `id`: Unique
- `class`: Reusable

**Q: Why `alt` attribute?**

- Accessibility + SEO

---

## 14. Best Practices

- Always declare `<!DOCTYPE html>`
- Use semantic tags
- Avoid inline styles
- Keep structure clean
- Validate HTML

---

### End of Notes

If you want:

- HTML + CSS combined notes
- HTML interview MCQs
- HTML + React interview mapping

Say the word.
