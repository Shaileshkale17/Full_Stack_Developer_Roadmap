# HTML Basic Tags Explained

This document provides an overview of key HTML tags such as `<title>`, `<meta>`, `<link>`, `<style>`, and `<base>` with examples and interview questions to enhance understanding.

---

## 1. `<title>`

Specifies the title of the document, which appears in the browser's title bar or tab.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <h1>Welcome to My Webpage</h1>
  </body>
</html>
```

---

## 2. `<meta>`

Defines metadata about the HTML document, such as character set, viewport settings, and page description.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="A sample webpage for learning HTML." />
  </head>
  <body>
    <h1>Metadata Example</h1>
  </body>
</html>
```

---

## 3. `<link>`

Used to link external resources like stylesheets or icons.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
    <link rel="icon" href="favicon.ico" type="image/x-icon" />
  </head>
  <body>
    <h1>Linked Resources Example</h1>
  </body>
</html>
```

---

## 4. `<style>`

Allows you to embed CSS directly into the HTML document.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
      }
      h1 {
        color: blue;
      }
    </style>
  </head>
  <body>
    <h1>Styled with &lt;style&gt;</h1>
  </body>
</html>
```

---

## 5. `<base>`

Sets the base URL for relative URLs in the document.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <base href="https://example.com/" />
  </head>
  <body>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
  </body>
</html>
```

In this example, the links will point to:

- `https://example.com/about.html`
- `https://example.com/contact.html`

---

# Interview Questions and Answers

### 1. **What is the purpose of the `<title>` tag?**

**Answer:**
The `<title>` tag defines the title of the HTML document. It is displayed in the browser's title bar or tab and is crucial for SEO and accessibility.

- Example:

```html
<title>My Website</title>
```

- This would display "My Website" in the browser tab.

---

### 2. **What is the role of the `<meta>` tag in an HTML document?**

**Answer:**
The `<meta>` tag provides metadata about the HTML document. It does not display content but is used for browser compatibility, SEO, and responsiveness.

Common attributes include:

- `charset`: Defines character encoding (e.g., UTF-8).
- `viewport`: Controls the layout on mobile devices.
- `description`: Provides a summary of the page for search engines.

Example:

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Learn HTML with examples" />
```

---

### 3. **How does the `<link>` tag work, and what is it used for?**

**Answer:**
The `<link>` tag links external resources like stylesheets, icons, or web fonts to an HTML document. It is commonly used in the `<head>` section.

Common attributes:

- `rel`: Specifies the relationship, such as `stylesheet` or `icon`.
- `href`: URL of the resource.

Example:

```html
<link rel="stylesheet" href="styles.css" />
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```

---

### 4. **What is the difference between `<style>` and `<link>` for CSS?**

**Answer:**

- `<style>` is used to embed CSS directly into the HTML document.
- `<link>` is used to link an external CSS file.

Example of `<style>`:

```html
<style>
  body {
    font-family: Arial;
    color: blue;
  }
</style>
```

Example of `<link>`:

```html
<link rel="stylesheet" href="styles.css" />
```

**When to use each:**

- Use `<style>` for small, specific customizations.
- Use `<link>` for maintaining external, reusable styles.

---

### 5. **What is the purpose of the `<base>` tag?**

**Answer:**
The `<base>` tag sets a base URL for all relative links in the document. If a base URL is specified, all relative paths (e.g., for images or links) will be resolved based on it.

Example:

```html
<base href="https://example.com/" /> <a href="page.html">Visit</a>
```

The link would resolve to `https://example.com/page.html`.

---

### 6. **What happens if you omit the `<meta charset="UTF-8">` tag?**

**Answer:**
Without specifying the character encoding, browsers might misinterpret special characters, leading to incorrect rendering, such as garbled text for non-English languages.

---

### 7. **Why should you include the `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag?**

**Answer:**
This ensures that the webpage is responsive by adjusting its width and scale to fit the device's screen. Without it, the webpage might appear zoomed out or poorly scaled on mobile devices.

---

### 8. **Can you explain the difference between metadata and content?**

**Answer:**

- **Metadata:** Provides information about the webpage, such as description, author, or viewport settings. It is invisible to users.
- **Content:** The actual data (text, images, etc.) displayed to users.

Example:

- Metadata:

```html
<meta name="description" content="Learn HTML" />
```

- Content:

```html
<h1>Welcome to HTML</h1>
```
