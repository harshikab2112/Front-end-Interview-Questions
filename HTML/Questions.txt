# HTML Interview Questions and Answers

This document contains **50 HTML interview questions and answers** ranging from **beginner to advanced** levels.

## Beginner Level Questions (1-20)

1. **What is HTML?**  
   HTML (HyperText Markup Language) is the standard markup language for creating web pages. It structures content using elements and tags.

2. **What are HTML tags?**  
   HTML tags are elements enclosed in `< >` that define different parts of a webpage. Example: `<p>`, `<h1>`, `<a>`.

3. **What is the difference between HTML and HTML5?**  
   HTML5 introduces semantic elements (`<article>`, `<section>`), new APIs, multimedia support (`<audio>`, `<video>`), and improved form controls.

4. **What is the function of `<!DOCTYPE html>`?**  
   It tells the browser that the document is written in HTML5.

5. **What are block-level and inline elements?**  
   - **Block-level**: Take full width (`<div>`, `<p>`, `<h1>`).  
   - **Inline**: Occupy only necessary space (`<span>`, `<a>`, `<strong>`).

6. **What are self-closing tags?**  
   Tags that don’t require a closing tag, like `<img>`, `<br>`, `<hr>`.

7. **What is the difference between `<strong>` and `<b>`?**  
   `<strong>` gives semantic importance, while `<b>` is purely for bold styling.

8. **What is the purpose of the `<meta>` tag?**  
   Provides metadata like character set, viewport settings, and SEO information.

9. **How do you create a hyperlink in HTML?**  
   ```html
   <a href="https://www.example.com">Visit Example</a>
   ```

10. **What is the difference between `<em>` and `<i>`?**  
    `<em>` emphasizes text (semantic), while `<i>` italicizes text for styling.

## Intermediate Level Questions (21-40)

21. **What is the difference between GET and POST in forms?**  
    - `GET`: Sends data in the URL, less secure.  
    - `POST`: Sends data in the request body, more secure.

22. **How do you create a dropdown list in HTML?**  
    ```html
    <select>
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
    </select>
    ```

23. **What are the different input types in HTML forms?**  
    `text`, `password`, `radio`, `checkbox`, `email`, `number`, `file`, `submit`.

24. **What is the purpose of the `<label>` tag?**  
    It associates a label with a form element for accessibility.

25. **What is the difference between `<thead>`, `<tbody>`, and `<tfoot>`?**  
    - `<thead>`: Table headers.  
    - `<tbody>`: Table body.  
    - `<tfoot>`: Table footer.

26. **How do you add a video in HTML?**  
    ```html
    <video controls>
      <source src="video.mp4" type="video/mp4">
    </video>
    ```

## Advanced Level Questions (41-50)

41. **What are Web Components?**  
    Web Components are a set of technologies that allow developers to create reusable, encapsulated components for web applications.

42. **How does the browser render an HTML page?**  
    - **Parsing HTML** – The browser reads and constructs the DOM (Document Object Model).  
    - **Parsing CSS** – It builds the CSSOM (CSS Object Model).  
    - **Constructing the Render Tree** – Combines DOM and CSSOM.  
    - **Layout Calculation** – Determines the position of elements.  
    - **Painting** – Converts elements into pixels.  
    - **Compositing** – Displays the final page on the screen.

43. **What is Shadow DOM?**  
    Shadow DOM allows encapsulation of HTML, CSS, and JavaScript within a component, preventing conflicts with the global document styles.

44. **What is a Service Worker?**  
    A Service Worker is a background script that runs in a browser separately from a web page, enabling features like offline support and push notifications.

45. **What is a PWA (Progressive Web App)?**  
    A PWA is a web app that offers a native-like experience using modern web technologies.

46. **How does HTML5 improve SEO?**  
    - **Semantic Elements** (`<article>`, `<section>`, `<header>`, `<nav>`) – Helps search engines understand content structure.  
    - **Microdata & Schema Markup** – Provides additional metadata to search engines.

47. **What is Microdata in HTML?**  
    Microdata is a way to embed metadata within HTML elements to improve SEO and provide structured data to search engines.

48. **What are Custom Elements in HTML?**  
    Custom Elements allow developers to create new HTML tags with custom behavior using JavaScript.

49. **How do you make an HTML page print-friendly?**  
    Use **CSS media queries** (`@media print`) to optimize the page for printing.

50. **What are `<slot>` elements?**  
    The `<slot>` element is used inside Web Components to define placeholders where content can be inserted dynamically.

---

This document provides a structured list of essential **HTML interview questions and answers**, helping developers prepare for technical interviews effectively. 🚀
