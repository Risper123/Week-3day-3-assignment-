Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)
Create an HTML file with at least three different types of elements (e.g., <h1>, <p>, <div>).
Style these elements using:
Element Selector: Change the font size of all headings.
Class Selector: Apply a background color to specific sections.
ID Selector: Add a border to an element with a unique ID.
Part 2: Inline, Internal, and External CSS (30 Points)
Use inline CSS to style one element (e.g., change the text color).
Add internal CSS in the <style> tag within the <head> section to style at least three elements.
Create a separate external CSS file and link it to your HTML. Use it to:
Change the background color of the webpage.
Style links with hover effects.
Part 3: Basic Styling Properties (50 Points)
Apply the following styles:

Colors: Set text and background colors for different elements.
Font Styles: Change the font family, size, and weight of text.
Text Alignment: Center-align, left-align, or justify text in paragraphs.
Spacing: Add padding and margin to elements for proper spacing.
Create a simple card component using these styles:

A heading for the card title.
A paragraph with some description.
Add padding inside the card and a margin around it.
Use a light background color and a subtle border.
# Week-3day-3-assignment-
My assignment for week 3day 3 

Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)

HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Basics Example</title>
    <style>
        /* Internal CSS */
        h1 {
            font-size: 36px;
        }

        .section {
            background-color: lightblue;
        }

        #uniqueElement {
            border: 2px solid black;
        }
    </style>
</head>
<body>

    <h1>Main Heading</h1>
    <p>This is a paragraph with some text content.</p>

    <div class="section">
        <p>This is a section with a background color applied using a class selector.</p>
    </div>

    <div id="uniqueElement">
        <p>This element has a unique ID and a border applied.</p>
    </div>

</body>
</html>


Part 2: Inline, Internal, and External CSS (30 Points)

HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <style>
        /* Internal CSS */
        body {
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }

        h1 {
            font-size: 36px;
            color: darkblue;
        }

        p {
            font-size: 18px;
            color: gray;
            line-height: 1.6;
        }

        a {
            color: blue;
        }

        a:hover {
            color: red;
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1>Main Heading</h1>
    <p>This is a paragraph styled with internal CSS.</p>
    <a href="#">This is a link with hover effect.</a>

</body>
</html>


External CSS (styles.css):

/* External CSS File */
body {
    background-color: #ffffff;
    font-family: 'Verdana', sans-serif;
}

h1 {
    font-size: 32px;
    color: navy;
}

p {
    font-size: 16px;
    color: black;
    line-height: 1.5;
}

a {
    color: green;
}

a:hover {
    color: purple;
    text-decoration: none;
}


Part 3: Basic Styling Properties (50 Points)

HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Card Component</title>
    <style>
        /* Internal CSS */
        body {
            background-color: #f8f9fa;
            font-family: 'Helvetica', sans-serif;
        }

        .card {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
        }

        .card h2 {
            font-size: 24px;
            color: darkblue;
        }

        .card p {
            font-size: 16px;
            color: #555;
        }

        .card a {
            color: blue;
        }

        .card a:hover {
            color: darkred;
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="card">
        <h2>Card Title</h2>
        <p>This is a description inside the card component.</p>
        <a href="#">Learn More</a>
    </div>

</body>
</html>
