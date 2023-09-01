# NETFLIX-clone-using-HTML-CSS
🎬 Netflix Landing Page Clone 🍿

Welcome to the Netflix Landing Page Clone project, a stunning replication of Netflix's iconic user interface using HTML and CSS.

### Project Highlights:
- 🖥️ Pixel-perfect replica of Netflix's homepage.
- 📱 Fully responsive design on all devices.
- 🚀 Optimized for performance and quick loading times.
- 🧩 Clean and organized codebase, perfect for learning and experimentation.

# Explanation of HTML code
1. `<!DOCTYPE html>`: This is the Document Type Declaration and specifies the document type and version of HTML being used. In this case, it's HTML5.

2. `<html lang="en">`: This is the opening `<html>` tag, which encloses the entire HTML document. The `lang` attribute indicates that the document is in English.

3. `<head>`: This section contains metadata about the HTML document, such as character encoding and page title.

4. `<meta charset="UTF-8">`: This `<meta>` tag defines the character encoding of the document as UTF-8, which is a widely used encoding for text on the web.

5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This `<meta>` tag sets the viewport properties for responsive design. It ensures that the page scales properly on various devices.

6. `<title>Netflix</title>`: This sets the title of the webpage, which appears in the browser's title bar or tab.

7. `<link rel="stylesheet" href="style.css">`: This `<link>` tag links an external CSS file named "style.css" to style the HTML content.

8. `<body>`: This is the opening `<body>` tag, which contains the main content of the webpage.

9. `<div class="header">`: This `<div>` tag with the class "header" defines the header section of your webpage.

10. `<nav>`: This is the navigation section within the header.

11. `<img src="./netflix-img/images/logo.png" alt="logo" class="logo">`: This `<img>` tag displays the Netflix logo. The `src` attribute specifies the image source, and `alt` provides alternative text for accessibility. The `class` attribute assigns the class "logo" for styling.

12. `<div>`: This is a `<div>` container within the navigation.

13. `<button class="language-btn">English<img src="./netflix-img/images/down-icon.png" alt="down-icon"></button>`: This `<button>` element is used for language selection and sign-in. It contains both text and an image (down icon).

14. `<div class="header-content">`: This `<div>` encloses the main content of the header section.

15. Various `<h1>`, `<h3>`, `<p>`, and `<form>` elements: These are used to structure and display text content within the header.

16. `<div class="features">`: This `<div>` defines the features section of your webpage.

17. Multiple `<div class="row">` elements: These represent individual feature rows, each containing an image and text content.

18. `<div class="faq">`: This `<div>` defines the Frequently Asked Questions section.

19. `<h2>`, `<ul>`, `<li>`, `<input>`, `<label>`, and `<div>` elements: These elements structure and display the FAQ content, with questions and answers hidden initially until clicked.

20. `<small>`: This element contains additional text within the FAQ section.

21. Another `<form>` element: This is a second form for email signup, similar to the one in the header.

22. `<div class="footer">`: This `<div>` defines the footer section of your webpage.

23. `<h2>`: This heading displays a contact phone number.

24. Three `<div class="col">` elements: These represent columns within the footer, containing links.

25. `<button class="language-btn">`: This button is similar to the one in the header and is used for language selection.

26. `<p class="cpyr8">Netflix India</p>`: This `<p>` element displays copyright or branding information.

That's a breakdown of my HTML code. It creates the structure and content of your Netflix landing page. CSS is likely used to style the page further based on the class and ID attributes assigned to elements.


# Explanation of CSS code
This CSS file is responsible for styling the elements in your Netflix landing page. Let's break it down section by section:

1. `*{margin: 0; padding: 0; font-family: 'Poppins', sans-serif; box-sizing: border-box;}`:
   - This is a CSS reset. It removes default margin and padding from all elements, sets a default font-family to 'Poppins' (if available), and uses the `box-sizing: border-box` property to include padding and borders in element widths.

2. `body { background: black; color: white; }`:
   - Sets the background color of the entire page to black and the text color to white.

3. `.header { ... }`:
   - Styles the header section of your page.
   - Uses a background image with a linear gradient overlay.
   - Sets the width to 100% and height to 100vh (viewport height).
   - Applies padding and positions it relative for child elements.

4. `nav { ... }`:
   - Styles the navigation section within the header.
   - Aligns items horizontally and adds padding.

5. `.logo { ... }`:
   - Styles the Netflix logo, setting its width and providing a pointer cursor.

6. `nav button { ... }`:
   - Styles the buttons within the navigation.
   - Defines the button's appearance, background color, padding, and margin.

7. `.language-btn { ... }`:
   - Styles the language button, displaying it as an inline flex container with specific padding.

8. `.header-content { ... }`:
   - Styles the content within the header, centering it both horizontally and vertically.

9. `.features { ... }`:
   - Styles the features section of your page, setting padding and font size.

10. `.row { ... }`:
    - Styles the rows in the features section, setting display, width, alignment, and padding.

11. `.text-col { ... }` and `.img-col { ... }`:
    - Styles the text and image columns within each feature row.

12. `.faq { ... }`:
    - Styles the FAQ section, including padding and font size.

13. `.accord { ... }`:
    - Styles the FAQ accordion, setting margin, width, and max-width.

14. `.accord li { ... }`:
    - Styles each list item within the accordion, removing list-style and adding padding.

15. `.accord li label { ... }`:
    - Styles the labels for the FAQ questions, setting padding, font size, and background.

16. `.label::after { ... }`:
    - Styles the '+' icon that indicates a collapsed FAQ answer.

17. `.accord input[type="radio"] { ... }`:
    - Styles the radio inputs used to control the FAQ answers.

18. `.accord .content { ... }`:
    - Styles the content of the FAQ answers, including background, padding, and max-height (for collapsible effect).

19. `.faq .email-signup { ... }`:
    - Styles the email signup form within the FAQ section.

20. `.footer { ... }`:
    - Styles the footer section, including padding, border-top, and text color.

21. `.footer .col { ... }`:
    - Styles the columns in the footer, setting flex properties, margin, and font size.

22. `.cpyr8 { ... }`:
    - Styles the copyright text in the footer, setting font size and margins.

23. Media queries (`.media for small screen`) adjust various styles for screens with a maximum width of 600px, making your page responsive for smaller devices.

This CSS file plays a crucial role in defining the visual layout and appearance of your Netflix landing page, making it both functional and visually appealing.

