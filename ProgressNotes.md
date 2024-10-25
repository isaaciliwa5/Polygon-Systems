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

<h3>Differences between Tags, Elements and Attributes:</h1>
1. HTML Tags

    Definition: Tags are the building blocks of HTML, used to create elements. They are enclosed within angle brackets (< >).
    Types: Most tags come in pairs—a start tag and an end tag. The start tag is <tagname>, and the end tag is </tagname>.
        Example:

        html

        <p>Some text here</p>

    Self-closing Tags: Some tags are self-closing, meaning they do not have an end tag (e.g., <img /> for images, <br /> for line breaks).

2. HTML Elements

    Definition: Elements are the complete structure created by the tags and the content within them. An HTML element typically consists of a start tag, content, and an end tag.
    Example:

    html

    <h1>This is an HTML Element</h1>

        Here:
            <h1> is the start tag.
            This is an HTML Element is the content.
            </h1> is the end tag.
    Self-closing Elements: Some elements, like <img> and <br>, do not have any content, so they don’t require a closing tag.

3. HTML Attributes

    Definition: Attributes provide additional information about an HTML element. They are included within the opening tag and consist of a name and a value (written as name="value").
    Purpose: Attributes modify or add information to elements, such as setting URLs, IDs, classes, styling, etc.
    Common Attributes:
        href in <a> tags for specifying the link URL.
        src in <img> tags for specifying the image source.
        alt in <img> tags for alternative text (for accessibility).
        id or class for unique or grouped styling with CSS.
    Example:

    html

    <a href="https://www.example.com" target="_blank">Visit Example</a>

        In this example:
            href is an attribute that specifies the URL the link points to.
            target="_blank" is another attribute that opens the link in a new tab.

Putting It All Together

In the following example, you can see tags, elements, and attributes working together:

html

<p id="intro">Welcome to <a href="https://example.com" target="_blank">my website</a>!</p>

    Tags: <p>, </p>, <a>, </a>
    Elements: <p>...</p> and <a>...</a>
    Attributes: id="intro" and href="https://example.com", target="_blank"

Now we start Polygon Systems' dummy website with fun.
Enjoy!

