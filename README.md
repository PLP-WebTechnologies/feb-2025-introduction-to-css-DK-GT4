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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <!-- Link to External CSS File -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Stylish Page</h1>
    </header>

    <section class="intro">
        <p>This is an introductory section where we talk about how to style a webpage with CSS.</p>
        <img src="https://via.placeholder.com/300" alt="Sample Image">
    </section>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>
/* Apply a custom font to the entire page */
body {
    font-family: 'Arial', sans-serif;  /* Using a sans-serif font */
    background-color: #f4f4f4;        /* Light gray background */
    color: #333;                      /* Dark text color for readability */
    margin: 0;
    padding: 0;
}

/* Style the header */
header {
    background-color: #4CAF50;         /* Green background for header */
    color: white;                      /* White text color */
    padding: 20px;
    text-align: center;                 /* Center the text */
}

/* Style the paragraph inside the .intro class */
.intro p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 20px;
}

/* Style the image */
img {
    width: 100%;                       /* Make the image responsive */
    max-width: 300px;                  /* Maximum width of 300px */
    display: block;
    margin: 0 auto;                    /* Center the image horizontally */
    border: 5px solid #ddd;            /* Light gray border around the image */
    padding: 10px;                     /* Padding inside the image border */
}

/* Style the footer */
footer {
    background-color: #333;            /* Dark background for footer */
    color: white;                      /* White text in the footer */
    text-align: center;
    padding: 10px;
    margin-top: 30px;
}

Happy Coding! 💻✨
