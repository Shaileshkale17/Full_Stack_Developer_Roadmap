# Basic HTML Structure

This document explains the basic structure of an HTML document, its essential tags, and their purposes. Additionally, it includes common interview questions related to the HTML structure for better understanding and preparation.

---

## Basic Tags and Their Purpose

### `<!DOCTYPE html>`

- Declares the document type and version of HTML (HTML5 in this case).

### `<html lang="en">`

- Represents the root element of the HTML document.
- `lang="en"` specifies the language of the content as English, helping with accessibility and SEO.

### `<head>`

- Contains metadata about the document, including its character encoding, viewport settings, and title.

#### `<meta charset="UTF-8">`

- Specifies the character encoding for the document (UTF-8 is the most common and supports most characters).

#### `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

- Ensures proper rendering and scaling on mobile devices by setting the viewport width to the device's width.

#### `<title>`

- Specifies the title of the document, displayed on the browser tab.

### `<body>`

- Contains all the visible content of the webpage, such as text, images, and interactive elements.

---

## Purpose

This structure serves as the foundation of any web page. You can start building your content inside the `<body>` tag by adding elements like headings, paragraphs, links, images, and more.

---

## Interview Questions

Here are some common **interview questions and answers** related to the basic HTML structure:

### **Q1: What is the purpose of `<!DOCTYPE html>` in an HTML document?**

**A:** The `<!DOCTYPE html>` declaration informs the web browser about the version of HTML being used. In this case, it specifies that the document uses HTML5. It ensures consistent rendering of the page across different browsers.

---

### **Q2: What does the `<meta charset="UTF-8">` tag do?**

**A:** This tag specifies the character encoding for the document. Using `UTF-8` ensures the document can display a wide range of characters, including special symbols, letters from different alphabets, and emojis. It's a best practice to include this tag for proper text rendering.

---

### **Q3: What is the significance of `<meta name="viewport" content="width=device-width, initial-scale=1.0">`?**

**A:** This tag ensures that the webpage is responsive by setting the width of the viewport to the device's screen width. The `initial-scale=1.0` ensures that the page is rendered at its natural size without zooming. This is essential for mobile-friendly web design.

---

### **Q4: Why is the `lang` attribute used in the `<html>` tag?**

**A:** The `lang` attribute specifies the language of the document. For example, `lang="en"` indicates English. This helps search engines and assistive technologies, like screen readers, to understand and interpret the content better.

---

### **Q5: What is the role of the `<head>` section in an HTML document?**

**A:** The `<head>` section contains metadata about the document that is not directly displayed on the webpage. This includes the title, links to stylesheets, meta tags for SEO, and scripts.

---

### **Q6: Can the `<body>` tag be omitted?**

**A:** Technically, modern browsers can render the content without explicitly including the `<body>` tag. However, it is a best practice to include it as it provides structure to the document and makes the HTML easier to read and maintain.

---

### **Q7: What happens if the `<!DOCTYPE>` declaration is missing in an HTML document?**

**A:** If the `<!DOCTYPE>` declaration is missing, the browser may render the page in **quirks mode**, which can lead to inconsistent and unpredictable behavior. Quirks mode is used to emulate old browser behavior for legacy web pages.

---

### **Q8: What is the purpose of the `<title>` tag?**

**A:** The `<title>` tag defines the title of the HTML document, which is displayed in the browser tab and used by search engines to identify the page. It is an important element for SEO and usability.

---
