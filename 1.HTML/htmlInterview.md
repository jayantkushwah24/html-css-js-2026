# HTML Interview Q&A for Product-Based Companies

## 1. Basic HTML Questions

**Q1: What is the difference between HTML and XHTML?**

- HTML: More flexible, ignores minor syntax errors.
- XHTML: Strict XML syntax, all tags must be properly closed, case-sensitive.

**Q2: Explain the difference between `<div>` and `<span>`.**

- `<div>`: Block-level, occupies full width.
- `<span>`: Inline, wraps around text/elements.

**Q3: Purpose of `<!DOCTYPE html>`**

- Declares HTML5 document type.
- Helps browsers render pages in standards mode.

**Q4: Semantic vs Non-Semantic HTML**

- Semantic: `<header>`, `<article>`, `<footer>` (meaningful for browser & SEO)
- Non-semantic: `<div>`, `<span>` (no meaning, just containers)

**Q5: Difference between `<b>` & `<strong>`, `<i>` & `<em>`**

- `<b>` / `<i>`: Visual only.
- `<strong>` / `<em>`: Semantic emphasis for accessibility and SEO.

---

## 2. Forms and Input

**Q6: Difference between GET and POST in forms**

- GET: URL parameters, limited length, less secure.
- POST: Body data, no size limit, more secure.

**Q7: Validate email input using HTML5**

```html
<input type="email" required />
```

**Q8: Difference between required, readonly, and disabled**

- `required`: Must fill.
- `readonly`: Cannot edit but submits value.
- `disabled`: Cannot edit and value not submitted.

**Q9: `<input type="text">` vs `<textarea>`**

- Text input: single line.
- Textarea: multi-line.

**Q10: How `<label>` improves accessibility**

- Clicking label focuses associated input.
- Supports screen readers.

---

## 3. Semantic HTML & SEO

**Q11: Why semantic elements important?**

- SEO, accessibility, maintainable code.

**Q12: Difference `<section>` and `<article>`**

- `<section>`: Thematic group.
- `<article>`: Standalone content.

**Q13: Difference `<header>` and `<nav>`**

- `<header>`: Page/section heading.
- `<nav>`: Navigation links.

**Q14: Meta tags influence SEO**

- Description, viewport, keywords affect indexing and ranking.

**Q15: Inline, block, inline-block difference**

- Inline: flows in line, cannot set width/height.
- Block: new line, can set width/height.
- Inline-block: inline with width/height control.

---

## 4. Media & Assets

**Q16: `<img>` vs `<picture>`**

- `<picture>`: Responsive images with multiple sources.

**Q17: `srcset` and `sizes`**

- Defines multiple image sources and sizes for responsive design.

**Q18: Lazy-load images**

```html
<img src="image.jpg" loading="lazy" />
```

**Q19: `<iframe>` usage & security**

- Embeds another page.
- Security: use `sandbox`, `allow` attributes.

**Q20: `<audio>` vs `<video>`**

- Both support `controls`, `autoplay`, `loop`.
- Video has visual content, audio is sound only.

---

## 5. Tables & Lists

**Q21: `<thead>`, `<tbody>`, `<tfoot>`**

- Header, body, footer for semantic & styling.

**Q22: `<ol>` vs `<ul>`**

- Ordered vs unordered list.

**Q23: Merge table cells**

- `colspan` (horizontal), `rowspan` (vertical).

**Q24: Responsive tables**

- Wrap table in scrollable container or use CSS media queries.

**Q25: `<dl>`, `<dt>`, `<dd>`**

- Description list: term (`dt`) + description (`dd`).

---

## 6. Advanced / Edge Cases

**Q26: Difference between `id` and `class`**

- `id`: unique, one per page.
- `class`: reusable.

**Q27: Can multiple elements have same `id`?**

- Technically yes, but breaks CSS & JS selectors.

**Q28: `data-*` attributes vs normal attributes**

- `data-*`: store custom info, accessible via JS (`dataset`).

**Q29: `<p>` inside `<span>`?**

- Invalid HTML; `<p>` is block, `<span>` inline.

**Q30: `hidden` vs `display: none`**

- `hidden`: HTML attribute, CSS `display: none` effect.
- `display: none`: CSS only.

---

## 7. Accessibility & Best Practices

**Q31: ARIA**

- Accessible Rich Internet Applications; helps screen readers understand UI.

**Q32: `alt` vs `title` vs `aria-label`**

- `alt`: image description.
- `title`: tooltip.
- `aria-label`: accessibility label.

**Q33: Accessible forms**

- Use `<label>`, proper input types, error messages.

**Q34: Purpose of `tabindex`**

- Controls tab order for keyboard navigation.

**Q35: Semantic HTML vs div-heavy code**

- Semantic better for accessibility, SEO, maintainability.

---

## 8. Scenario/Coding Questions

**Q36: Responsive card HTML structure**

```html
<div class="card">
  <img src="img.jpg" alt="image" />
  <h3>Card Title</h3>
  <p>Card description</p>
</div>
```

**Q37: Structure HTML page for SEO**

- `<header>` with nav, `<main>` content, `<article>` sections, `<footer>` links, meta tags.

**Q38: Convert design to semantic HTML**

- Identify sections, articles, headings, lists, buttons.

**Q39: Fix invalid HTML**

- Example: nesting block inside inline; solution: use `<div>` instead of `<span>`.

**Q40: Optimize images/media**

- Use compressed formats (WebP), `srcset`, lazy-loading, correct dimensions.

---

**Tip for Interviews:** Focus on **why** a tag or attribute exists, not just syntax. Product-based interviews test **thinking, edge cases, and maintainability awareness**.
