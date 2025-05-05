# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Styled Page</title>
    <!-- Link to Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <!-- Link to external CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 id="main-title">Welcome to My Styled Page</h1>
    </header>

    <section class="intro-section">
        <p class="intro">This is an introductory paragraph. We’re using external CSS to style this page with colors, fonts, margins, paddings, and borders.</p>
    </section>

    <section class="box-section">
        <div class="box">
            <p class="content">This is a styled content box with padding, margin, and a border.</p>
        </div>
    </section>

    <section class="button-section">
        <button class="action-button">Click Me</button>
    </section>

    <footer>
        <p class="footer-text">© 2025 My Styled Page</p>
    </footer>
</body>
</html>

/* General styles */
body {
    font-family: 'Roboto', sans-serif;
    background-color: #f8f9fa;
    margin: 0;
    padding: 0;
    color: #333;
}

/* Header title (ID selector) */
#main-title {
    color: #2c3e50;
    text-align: center;
    margin: 40px 0 20px;
    font-size: 2.5em;
}

/* Intro section (class selector) */
.intro-section .intro {
    font-size: 1.2em;
    line-height: 1.6;
    margin: 20px auto;
    max-width: 600px;
    text-align: center;
    color: #555;
}

/* Content box */
.box {
    background-color: #ffffff;
    padding: 20px;
    margin: 20px auto;
    border: 2px solid #bdc3c7;
    border-radius: 8px;
    max-width: 600px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Button with hover effect */
.action-button {
    background-color: #3498db;
    color: #fff;
    padding: 12px 24px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    display: block;
    margin: 20px auto;
    font-size: 1em;
    transition: background-color 0.3s ease;
}

.action-button:hover {
    background-color: #2980b9;
}

/* Footer text */
.footer-text {
    text-align: center;
    padding: 20px;
    font-size: 0.9em;
    color: #888;
}
