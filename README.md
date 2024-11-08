# Combining CSS Selectors
# Overview
This project demonstrates the use of CSS selectors to style various elements on a basic "To Do List" HTML page. The CSS file (style.css) includes different types of CSS selectors to apply styling to headings, paragraphs, lists, and specific classes.

# Files
index.html - The HTML file that structures the To Do List.
style.css - The CSS file that contains the styling rules.
# HTML Structure
The HTML file includes the following elements:

**Headings:** <h1> and <h2> elements are used for the main title and subheading.
**Div Container (.box):** Contains a paragraph and an unordered list with items that represent tasks for the day.
**Paragraphs:** Different paragraphs with specific classes to allow targeted styling.
**List Items:** Some list items are marked as "done" using a done class.
# CSS Selectors and Styling
Here is an overview of the CSS selectors used in style.css:

Type Selector (h1, h2)

Selects all h1 and  h2 elements and styles them with color: blueviolet;.
Child Selector (.box > p)

Targets only the direct <p> child of the .box div, applying color: firebrick;.
Descendant Selector (.box li)

Selects all <li> elements within .box and applies color: blue;.
Class Selector (li.done)

Targets all <li> elements with the done class, applying color: seagreen;.
Specific Class in a Specific Context (ul p.done)

Targets <p> elements with the done class inside an unordered list <ul>, setting font-size: 0.5rem;.
