# HTML Basics – Questions and Answers

## 1. What is HTML?
HTML (HyperText Markup Language) is the standard markup language used to create and structure web pages. It defines the content of a webpage using elements such as headings, paragraphs, images, links, tables, and forms.

---

## 2. What does HTML stand for?
**HTML** stands for **HyperText Markup Language**.

- **HyperText:** Text that contains links to other pages or resources.
- **Markup:** Tags used to define the structure of content.
- **Language:** A standardized language for creating web pages.

---

## 3. What is the DOM?
The **Document Object Model (DOM)** is a tree-like representation of an HTML document. It allows JavaScript to access, modify, and manipulate HTML elements dynamically.

---

## 4. What is an HTML Tag?
An HTML tag is a keyword enclosed within angle brackets (`< >`) that tells the browser how to display or structure content.

**Examples:**
- `<h1>`
- `<p>`
- `<img>`

---

## 5. What is an HTML Element?
An HTML element consists of:
- Opening tag
- Content
- Closing tag

**Example:**
```html
<p>Hello World!</p>
```

---

## 6. What is an HTML Attribute?
An attribute provides additional information about an HTML element. Attributes are written inside the opening tag.

**Example:**
```html
<img src="image.jpg" alt="Nature Image">
```

Here:
- `src` is the image source.
- `alt` provides alternative text.

---

## 7. What is the purpose of `<!DOCTYPE html>`?
`<!DOCTYPE html>` tells the browser that the document is written in HTML5. It ensures the page is rendered in standards mode.

---

## 8. What is the root element of an HTML document?
The root element is:

```html
<html>
```

It contains all other HTML elements.

---

## 9. What is Metadata?
Metadata is information about the webpage that is not directly visible to users. It helps browsers, search engines, and other applications understand the page.

Examples include:
- Character encoding
- Author
- Description
- Viewport settings

---

## 10. What is a Favicon?
A favicon is the small icon displayed next to the page title in the browser tab.

Example:

```html
<link rel="icon" href="favicon.ico">
```

---

## 11. Explain the Structure of an HTML Document

```text
<!DOCTYPE html>
<html>
    <head>
        Metadata
    </head>

    <body>
        Visible Content
    </body>
</html>
```

### Components
- `<!DOCTYPE html>` → HTML5 declaration
- `<html>` → Root element
- `<head>` → Metadata
- `<body>` → Visible webpage content

---

## 12. Difference Between HTML Tags and HTML Elements

| HTML Tag | HTML Element |
|-----------|--------------|
| Written inside `< >`. | Complete structure including opening tag, content, and closing tag. |
| Example: `<p>` | Example: `<p>Hello</p>` |

---

## 13. Difference Between Absolute Path and Relative Path

| Absolute Path | Relative Path |
|---------------|---------------|
| Full URL or complete file location. | Location relative to the current file. |
| Example: `https://example.com/image.png` | Example: `images/image.png` |

---

## 14. Compare `<p>` and `<pre>`

| `<p>` | `<pre>` |
|--------|----------|
| Displays normal paragraphs. | Preserves spaces and line breaks. |
| Extra spaces are ignored. | Formatting is preserved exactly. |

---

## 15. Why are HTML Entities Used?

HTML entities are used to display reserved characters and special symbols.

Examples:

| Character | Entity |
|-----------|--------|
| < | `&lt;` |
| > | `&gt;` |
| & | `&amp;` |
| © | `&copy;` |
| ₹ | `&#8377;` |

---

## 16. Explain the Purpose of the Viewport Meta Tag

The viewport meta tag makes webpages responsive on different devices.

Example:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Benefits:
- Responsive layouts
- Better mobile experience
- Correct page scaling

---

## 17. Explain the Purpose of the `lang` Attribute

The `lang` attribute specifies the language of the webpage.

Example:

```html
<html lang="en">
```

Benefits:
- Helps screen readers
- Improves SEO
- Assists translation tools

---

## 18. Why is UTF-8 Used?

UTF-8 is a character encoding that supports almost every language and symbol.

Benefits:
- Displays multilingual text correctly
- Supports emojis and special symbols
- Prevents character encoding issues

---

## 19. What Information is Stored Inside the `<head>` Section?

The `<head>` section typically contains:

- Page title
- Meta tags
- Character encoding
- Viewport settings
- Favicon
- CSS links
- JavaScript links
- SEO information

---

## 20. Why Should Developers Use Comments in HTML?

Comments help developers:
- Explain code
- Improve readability
- Make maintenance easier
- Temporarily disable code without deleting it

Syntax:

```html
<!-- This is an HTML comment -->
```