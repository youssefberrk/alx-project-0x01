# 0x00 - Semantic HTML

## Overview
This directory contains exercises and tasks related to **Semantic HTML** aimed at improving accessibility and search engine optimization (SEO). The tasks involve structuring simple HTML documents using semantic elements, adding meta tags for SEO, and applying ARIA roles to enhance accessibility.

## Directory Structure

```
0x00-semantic_html/
├── 0-index.html
├── 1-index.html
├── 2-index.html
├── 3-index.html
└── README.md
```

## Tasks

### Task 0: Creating a Structured HTML Document Using Semantic Elements
- **Objective:** Structure a basic HTML document using semantic elements like `<header>`, `<footer>`, `<main>`, and `<nav>`.
- **Instructions:**
  - Inside the `<html>` tag, create the `<head>` and `<body>` tags (empty in this order).
  - Inside the `<body>` tag:
    - Add a `<header>` that contains a `<nav>` with at least three links.
    - Create a `<main>` section that contains an `<article>`, and inside the article, add an `<h1>` tag for the title and a `<section>` for the content.
    - Add a `<footer>` with some copyright information `@copyright`.
  - **File:** `0-index.html`

### Task 1: Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility
- **Objective:** Add meta tags and a title to the HTML document to improve SEO and accessibility.
- **Instructions:**
  - Copy the content of `0-index.html` into `1-index.html`.
  - Inside the `<head>` tag, add the following:
    - A `<meta>` tag for the charset: `<meta charset="utf-8">`.
    - Four additional meta tags:
      - `name="description" content="A blog post about semantic HTML and accessibility practices"`.
      - `name="keywords" content="HTML, Semantic, Accessibility, Blog, SEO"`.
      - `name="author" content="Your Name"`.
      - `name="viewport" content="width=device-width, initial-scale=1.0"`.
    - A `<title>` tag with the message: `Semantic HTML Blog Post`.
  - **File:** `1-index.html`

### Task 2: Creating a Blog Post Layout Using Semantic HTML Elements
- **Objective:** Use semantic HTML elements to create a blog post layout with headers, sections, and a footer.
- **Instructions:**
  - Copy the content of `1-index.html` into `2-index.html`.
  - Inside the `<header>` tag:
    - Add an `<h1>` tag with the content `My Blog`.
    - Add a `<nav>` tag and inside it, create a `<ul>` tag with 3 `<li>` elements referencing:
      - Home
      - About
      - Contact
  - Inside the `<article>` tag in the `<main>` tag:
    - Add a `<header>` tag with an `<h2>` tag, text: `Understanding Semantic HTML`.
    - Add a `<p>` tag with the text: `Published on <time datetime="2024-09-10">September 10</time>`.
    - Inside the `<section>` tag, add:
      - An `<h3>` tag with the text: `Introduction`.
      - A `<p>` tag explaining the importance of semantic HTML for accessibility and SEO.
    - Below the first section, add another `<section>` tag:
      - An `<h3>` tag with the text: `Main Content`.
      - A `<p>` tag discussing elements like `<article>`, `<section>`, `<header>`.
      - Add a `<figure>` with:
        - An `<img>` tag (with `src` and `alt` attributes).
        - A `<figcaption>` with the text: "An illustration of semantic HTML elements".
    - Add a third `<section>` tag with:
      - An `<h3>` tag with the text: `Conclusion`.
      - A `<p>` tag summarizing the benefits of adopting semantic HTML.
  - Add a `<footer>` with:
    - A `<p>` tag with the text: `Written by Your Name`.
    - A `<p>` tag with the text: `Published on 2024-09-11`.
  - **File:** `2-index.html`

### Task 3: Enhancing Form Accessibility with ARIA Roles and Attributes
- **Objective:** Implement ARIA roles and attributes to enhance the accessibility of a form.
- **Instructions:**
  - Copy the content of `2-index.html` into `3-index.html`.
  - Inside the `<main>` element, add a new `<section>` tag.
  - Inside the `<form>` tag, add:
    - `action="#"`, `method="POST"`, `aria-labelledby="form-title"`, `role="form"`.
    - A `<div>` containing:
      - A `<label>` with `for="name"`, an `<input>` tag with attributes `type="text"`, `id="name"`, `name="name"`, and `aria-required="true"`.
      - Another `<div>` containing a `<label>` for email and an `<input>` tag with similar attributes.
      - A `<div>` containing a `<button>` with `type="submit"` and `aria-label="Submit the form"`.
      - A `<div>` with `aria-live="polite"` and `role="alert"`.
  - **File:** `3-index.html`

---

## Instructions

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/youssefberrk/alx-intermediate-frontend.git
   cd alx-intermediate-frontend/0x00-semantic_html
   ```

2. **Edit HTML files** in this directory using your preferred text editor (e.g., VS Code, Sublime Text).

3. **Push changes** back to GitHub after completing tasks:
   ```bash
   git add .
   git commit -m "Completed task [task number] in semantic HTML directory"
   git push origin main
   ```

---

## Learning Resources
Here are some valuable resources to help you with this project and enhance your understanding of semantic HTML:

- **[HTML5 Doctor - Semantic HTML](http://html5doctor.com/)**  
  Learn more about the advantages of semantic HTML and how it impacts SEO and accessibility.

- **[MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)**  
  Comprehensive documentation on HTML elements and best practices.

- **[W3C ARIA Specifications](https://www.w3.org/TR/wai-aria/)**  
  A guide to ARIA (Accessible Rich Internet Applications), which helps enhance the accessibility of dynamic content.

- **[HTML5 Semantics and Accessibility](https://www.w3.org/WAI/WCAG21/Techniques/general/G58.html)**  
  Techniques to make your website more accessible with semantic elements.

---

## Project Deadline
- **Project must be completed by Dec 8, 2024, 10:00 PM.**
- **Manual review** is required once you finish.

---
