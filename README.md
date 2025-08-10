**UNES University Website**
====================================

**1\. Project Overview**
------------------------

This project consists of a simple, single-page static website for "UNES," a fictional university. The page serves as a promotional landing page, outlining the institution's key strengths, academic quality, infrastructure, and student-focused environment.

The entire website is built using fundamental **HTML**, employing a `<table>` element to structure the layout. This approach, while not common in modern web development, demonstrates a foundational understanding of HTML for organizing content into a coherent, centered design.

**2\. File Structure**
----------------------

The project relies on a straightforward file structure:

```
/
|-- index.html       (The main HTML file)
|-- img/
|   |-- logo.png     (University logo)
|   |-- capa.png     (Header banner image)
|   |-- fundo2.png   (Background image for the page)

```

-   **`index.html`**: This is the core file containing all the content and structural markup for the website.

-   **`img/`**: This directory holds all the visual assets used on the page.

**3\. Technical Implementation**
--------------------------------

### **3.1. Layout and Structure**

The page's layout is managed by a single, centered HTML `<table>` with a width of 900 pixels. This table acts as a container for all visible content, which is organized into three main rows:

1.  **Header Row**: This row is divided into two columns.

    -   The left column contains the university's logo (`logo.png`).

    -   The right column contains the navigation links ("About Us," "Home Page").

2.  **Banner Row**: This row spans both columns (`colspan="2"`) and displays a large banner image (`capa.png`) that serves as the page's primary visual element.

3.  **Content Row**: This row also spans both columns and contains the main textual content of the page. It includes:

    -   A main heading (`<h2>`) "About the university."

    -   Several subheadings (`<h3>`) highlighting key features like teaching quality, modern infrastructure, and market connections.

    -   Paragraphs (`<p>`) that elaborate on each feature.

    -   Horizontal rules (`<hr>`) to visually separate content sections.

### **3.2. Styling and Content**

-   **Background**: A background image (`fundo2.png`) is applied directly to the `<body>` element using the `background` attribute.

-   **Text**: The content is written in a promotional and engaging tone, aimed at prospective students. It uses emojis to appear modern and relatable.

-   **Links**: The navigation links (`<a>`) are currently placeholders and do not link to other pages (`href="#"`).

**4\. How It Works**
--------------------

When a user opens the `index.html` file in a web browser, the browser renders the HTML markup. It fetches the images from the `img` directory and displays them according to the table structure. The `align="center"` attribute on the main table ensures that the entire 900px-wide layout is centered horizontally in the browser window.

This project serves as an excellent example of basic HTML structure and content organization without relying on CSS for layout, showcasing an older but functional method of web page design.
