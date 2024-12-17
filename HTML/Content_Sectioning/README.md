# **HTML5 Content Sectioning with Examples**

---

#### 1. `<header>`: Introductory content

Typically contains headings, logos, or introductory material.

**Example:**

```html
<header>
  <h1>Welcome to My Website</h1>
  <p>Your one-stop destination for tech updates.</p>
</header>
```

#### 2. `<nav>`: Navigation links

Used for major navigation blocks in a document.

**Example:**

```html
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

#### 3. `<section>`: Thematic grouping of content

Groups related content under a common theme.

**Example:**

```html
<section>
  <h2>About Our Services</h2>
  <p>We provide web development, design, and SEO services.</p>
</section>
```

#### 4. `<article>`: Self-contained content

Represents content that can stand alone, such as a blog post or news article.

**Example:**

```html
<article>
  <h2>Breaking News: Tech Conference 2024</h2>
  <p>The annual tech conference will be held in San Francisco this year.</p>
</article>
```

#### 5. `<aside>`: Related content

Used for sidebars or supplementary material.

**Example:**

```html
<aside>
  <h3>Upcoming Events</h3>
  <ul>
    <li>Webinar on AI - Dec 20th</li>
    <li>Hackathon - Jan 15th</li>
  </ul>
</aside>
```

#### 6. `<footer>`: Footer content

Used for page footers containing copyright, legal, or contact information.

**Example:**

```html
<footer>
  <p>&copy; 2024 My Website. All Rights Reserved.</p>
</footer>
```

#### 7. `<main>`: Main content area

Specifies the central content of the document.

**Example:**

```html
<main>
  <h1>Welcome to Our Blog</h1>
  <p>Explore our latest articles and tutorials.</p>
</main>
```

#### 8. `<address>`: Contact information

Used for presenting contact details.

**Example:**

```html
<address>
  Contact us: <a href="mailto:info@example.com">info@example.com</a><br />
  Call us: +1 555-555-5555
</address>
```

---

### **Interview Questions and Answers**

#### 1. **What is the purpose of sectioning elements in HTML5?**

**Answer:**
Sectioning elements organize content into meaningful and semantic blocks, improving readability, SEO, and accessibility. Examples include `<header>`, `<section>`, `<article>`, and `<aside>`.

---

#### 2. **When should you use `<article>` versus `<section>`?**

**Answer:**

- Use `<article>` for self-contained content that can be independently distributed or reused (e.g., blog posts, news articles).
- Use `<section>` to group content under a common theme, often as part of a document's hierarchy.

---

#### 3. **Can you use multiple `<header>` or `<footer>` tags on a single page?**

**Answer:**
Yes, multiple `<header>` and `<footer>` elements are allowed, typically within sections, articles, or the overall document structure.

---

#### 4. **What is the `<main>` element, and how does it improve accessibility?**

**Answer:**

- The `<main>` element defines the central content of a page, excluding repeated content like headers, footers, and navigation links.
- It improves accessibility by allowing assistive technologies to quickly identify and navigate the core content.

---

#### 5. **How does the `<nav>` element impact SEO?**

**Answer:**
Search engines recognize `<nav>` as a navigation block, improving crawlability and understanding of the website's structure. Proper use of `<nav>` with meaningful links enhances SEO.

---

#### 6. **What is the significance of semantic HTML for modern web development?**

**Answer:**
Semantic HTML provides meaning to content, making it easier for browsers, search engines, and assistive technologies to interpret. It improves SEO, accessibility, and maintainability.

---
