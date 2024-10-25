HTML (Hypertext Markup Language) is the standard language used to create and structure web pages. It's composed of elements, tags, and attributes that define the layout and content of a webpage. Here’s a basic overview of HTML syntax:
Basic Structure

An HTML document has a standard structure that looks like this:

html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph of text.</p>
</body>
</html>

Key Elements

    DOCTYPE Declaration
        <!DOCTYPE html>: Declares that the document is an HTML5 document.

    <html> Tag
        Contains all HTML elements.
        Includes the lang attribute to specify the language (e.g., lang="en" for English).

    <head> Tag
        Contains meta-information about the document (e.g., title, character encoding, etc.).
        It doesn’t display content but gives info to browsers or search engines.

    <title> Tag
        Defines the title of the webpage, which is displayed in the browser tab.

    <meta> Tag
        Provides metadata about the document (e.g., charset defines the character encoding).

    <body> Tag
        Contains the content visible on the webpage like text, images, links, etc.

Common HTML Tags

    Headings
        Ranges from <h1> (largest) to <h6> (smallest).

    html

<h1>Main Heading</h1>
<h2>Sub Heading</h2>

Paragraph

    Defines a block of text.

html

<p>This is a paragraph of text.</p>

Links

    <a> tag creates a hyperlink. Use the href attribute to specify the URL.

html

<a href="https://www.example.com">Visit Example</a>

Images

    <img> tag displays an image. Use src to define the image URL and alt for alternative text.

html

<img src="image.jpg" alt="Description of Image">

Lists

    Ordered List <ol> and Unordered List <ul>, with list items <li>.

html

<ul>
    <li>First item</li>
    <li>Second item</li>
</ul>

Forms

    Used to collect user input.

html

    <form action="/submit" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>

Attributes

Attributes provide additional information about HTML elements. They are always included within the opening tag.

    Example: In an image tag <img src="image.jpg" alt="Description">, src and alt are attributes.
        src specifies the file path.
        alt provides alternative text for accessibility.

HTML Comments

You can include comments in your code that won’t appear on the page:

html

<!-- This is a comment -->

Nesting

HTML elements can be nested inside other elements. Make sure to properly close each tag in the reverse order they are opened.

html

<p>This is a <strong>bold</strong> word in a sentence.</p>
