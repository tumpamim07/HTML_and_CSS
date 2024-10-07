
<div align="center">
<h1>HTML AND CSS Documentation</h1>
</div>
<details>
<summary>Day 01 (html Tags & Attribute)</summary>

-  
    ### 1. **Tags and Attributes**
    
    HTML tags define the structure of the webpage. Attributes provide additional information about elements.
    
    ### Types of Tags:
    
    - **Container Tag**: A tag that has both an opening and closing part.
        - Example:
        In this example, the `<p>` tag is a container tag with an opening tag `<p>` and a closing tag `</p>`.
            
            ```html
            <p>Content goes here</p>
            
            ```
            
    - **Empty Tag**: A tag that doesn’t require a closing tag.
        - Example:
        The `<hr>` tag is an empty tag that creates a horizontal line.
            
            ```html
            <hr>
            
            ```
            
    
    ### Tag Syntax:
    
    - **Opening Tag**: The starting part of an element. It contains the tag name enclosed in angle brackets. Example: `<h1>`.
    - **Closing Tag**: The ending part of an element. It is similar to the opening tag but includes a forward slash. Example: `</h1>`.
    - **Element**: The entire structure including the opening tag, content, and closing tag.
        - Example: `<h1>HTML Day 01</h1>`. This is an element consisting of the `<h1>` opening tag, content, and `</h1>` closing tag.
    
    ### Why Do We Use Attributes?
    
    Attributes provide additional information about an element, such as how it should behave or appear. They are written inside the opening tag. For example:
    
    ```html
    <h3 align="center">Day 01</h3>
    
    ```
    
    Here, the `align` attribute centers the heading text.
    
    ---
    
    ### 2. **Inside the `<head>` Tag**
    
    The `<head>` tag contains metadata and resources that are important for the browser but not directly displayed on the webpage. Let’s go over the different elements in the head.
    
    ### Metadata Tags:
    
    - **`<meta charset="UTF-8">`**: Defines the character set for the document as UTF-8, which supports multiple languages and characters.
        - Code:
            
            ```html
            <meta charset="UTF-8">
            
            ```
            
    - **`<meta http-equiv="X-UA-Compatible" content="ID=edge">`**: Ensures compatibility with the latest version of Internet Explorer.
        - Code:
            
            ```html
            <meta http-equiv="X-UA-Compatible" content="ID=edge">
            
            ```
            
    - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Sets the viewport to match the device’s width and ensures the content is scaled properly on different screens.
        - Code:
            
            ```html
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            
            ```
            
    - **`<meta name="description" content="html">`**: Provides a brief description of the webpage, which is used by search engines for ranking.
        - Code:
            
            ```html
            <meta name="description" content="html">
            
            ```
            
    - **`<meta name="keywords" content="html, HTML">`**: Contains keywords that describe the content of the webpage, helping search engines index the page.
        - Code:
            
            ```html
            <meta name="keywords" content="html, HTML">
            
            ```
            
    - **`<meta name="author" content="Tumpa Moni Mim">`**: Specifies the author of the webpage.
        - Code:
            
            ```html
            <meta name="author" content="Tumpa Moni Mim">
            
            ```
            
    
    ### Title Tag:
    
    The `<title>` tag defines the title of the webpage, which is displayed in the browser tab.
    
    - Code:
        
        ```html
        <title>Tumpa Moni Mim</title>
        
        ```
        
    
    ### Link Tag (Optional):
    
    If you want to link an external resource such as a CSS file, you use the `<link>` tag. This wasn’t included in your code, but an example would look like:
    
    - Code:
        
        ```html
        <link rel="stylesheet" href="styles.css">
        
        ```
        
    
    ### Style Tag (Optional):
    
    The `<style>` tag allows you to write internal CSS styles. Here’s an example:
    
    - Code:
        
        ```html
        <style>
            h1 {
                color: blue;
            }
        </style>
        
        ```
        
    
    ---
    
    ### 3. **Headings, Paragraphs, Align Attribute, and Horizontal Rule**
    
    ### Headings:
    
    There are six levels of headings in HTML, from `<h1>` (the largest) to `<h6>` (the smallest). Your code includes all of them:
    
    - Code:
        
        ```html
        <h1>HTML day 01</h1>
        <h2>HTML day 01</h2>
        <h3>HTML day 01</h3>
        <h4>HTML day 01</h4>
        <h5>HTML day 01</h5>
        <h6>HTML day 01</h6>
        
        ```
        
    
    ### Paragraph:
    
    Paragraphs in HTML are created using the `<p>` tag, which defines a block of text.
    
    - Code:
        
        ```html
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
        
        ```
        
    
    ### Align Attribute:
    
    In your example, the `align` attribute is used in the `<h3>` tag to center the text. The `align` attribute has been deprecated in HTML5, and it's recommended to use CSS for alignment, but here’s how it works in your code:
    
    - Code:
        
        ```html
        <h3 align="center">Day 01</h3>
        
        ```
        
    
    ### Horizontal Rule (`<hr>`):
    
    The `<hr>` tag creates a horizontal line to visually separate content. It is an empty tag, so it doesn’t require a closing tag.
    
    - Code:
        
        ```html
        <hr>
        
        ```
        
    
    ---
    
    ### Full Example of Code:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ID=edge">
        <meta name="description" content="html">
        <meta name="keywords" content="html, HTML">
        <meta name="author" content="Tumpa Moni Mim">
        <title>Tumpa Moni Mim</title>
    </head>
    <body>
    
        <h3 align="center">Day 01 <br>
            Basic Structure of HTML</h3>
        <hr>
    
        <!-- Headings -->
        <h1>HTML day 01</h1>
        <h2>HTML day 01</h2>
        <h3>HTML day 01</h3>
        <h4>HTML day 01</h4>
        <h5>HTML day 01</h5>
        <h6>HTML day 01</h6>
    
        <!-- Paragraph -->
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae, sequi iste quae error perferendis impedit eos...</p>
    
        <hr>
    
    </body>
    </html>
    ```
    
    ### Output of Code:
    
    ![1](https://i.imgur.com/imjkpuM.png)

</details>

<details>
<summary>Day 02 (Text Formatting Tags & Styling html Elements)</summary>

- 
    ### 1. **Styling HTML Elements**
    
    In this section, here are both internal CSS in the `<style>` tag and inline styles in the `<body>` and `<h1>` tags.
    
    ### Example: Body Styling
    
    ```html
    <body style="color: white;">
    ```
    
    ### **Property**:
    
    - The **property** in CSS refers to an aspect or characteristic of the element that you want to style or control. It describes **what** you want to change, such as the color, font size, width, or margin of an HTML element.
    
    ### **Value**:
    
    - The **value** in CSS specifies **how** you want to change the property. It defines the actual setting for the property, like the specific color, size, or spacing. Values are specific to the property they are assigned to, and different properties can accept different types of values.
    - **Property**: `color`
    - **Value**: `white`
    - **Explanation**: This inline CSS is setting the default text color for the entire page to white. Inline styling applies only to the specific element it is defined on.
    
    ### Example: Styling in `<style>` tag
    
    ```html
    h1 {
      color: rgb(255, 255, 255);
      text-align: center;
    }
    ```
    
    - **Property**: `color`
    - **Value**: `rgb(255, 255, 255)`
    - **Explanation**: This defines the color of the `<h1>` text using the RGB color code for white.
    - **Property**: `text-align`
    - **Value**: `center`
    - **Explanation**: Aligns the text to the center of the page.
    
    ---
    
    ### 2. **Text Formatting Tags**
    
    ### a) **Bold and Strong**
    
    ```html
    <b>This is a bold Text</b> <br>
    <strong>This is strong Text </strong><br>
    ```
    
    - **`<b>`**: Displays the text in bold. It is primarily used for visual styling, without implying importance.
    - **`<strong>`**: Also displays text in bold, but this tag has semantic meaning, indicating that the text is of strong importance.
    
    ### b) **Italic and Emphasized Text**
    
    ```html
    <i>This is a italic text</i> <br />
    <em>This is an emphasize text</em> <br />
    ```
    
    - **`<i>`**: Italicizes the text. It’s mainly used for styling purposes without conveying emphasis.
    - **`<em>`**: Italicizes the text and adds emphasis to it, implying that the text is important.
    
    ### c) **Underline**
    
    ```html
    <u>This is an italic text</u> <br />
    ```
    
    - **`<u>`**: Underlines the text. It's used to emphasize or draw attention to a specific part of the text.
    
    ### d) **Superscript and Subscript**
    
    ```html
    (a+b) <sup>2</sup>=a<sup>2</sup>+2ab+b <sup>2</sup> <br>
    H<sub>2</sub>O <br>
    ```
    
    - **`<sup>`**: Superscript text. It raises the text slightly above the normal text level, useful for powers or footnotes (e.g., a²).
    - **`<sub>`**: Subscript text. It lowers the text below the normal text line, often used for chemical formulas (e.g., H₂O).
    
    ### e) **Preformatted Text**
    
    ```html
    <pre>
        This is a
          life changing documentation
        Read,learn, enjoy
          ofcourse share with others
    </pre>
    
    ```
    
    - **`<pre>`**: Preformatted text. The text inside this tag maintains all spaces and line breaks, displaying it exactly as written in the code.
    
    ### f) **Strike-through Text**
    
    ```html
    <strike>This is a strike text</strike><br>
    
    ```
    
    - **`<strike>`**: Draws a line through the text, indicating that it's no longer valid or has been "struck out."
    
    ### g) **Deleted Text**
    
    ```html
    <del>This is a deleted text</del> <br />
    ```
    
    - **`<del>`**: Displays text with a line through it, marking it as deleted or no longer relevant.
    
    ### h) **Abbreviation**
    
    ```html
    <abbr title="google is a search engine">Google</abbr> <br />
    
    ```
    
    - **`<abbr>`**: Defines an abbreviation or acronym. When the user hovers over the text (Google), the full meaning or explanation appears (e.g., "google is a search engine").
    
    ### i) **Address**
    
    ```html
    <address>561, ABC road, Dhaka-1216, Bangladesh</address><br>
    
    ```
    
    - **`<address>`**: Used to display contact information or address. It's typically styled in italics and may include email, physical address, or any contact details.
    
    ### j) **Blockquote**
    
    ```html
    <blockquote>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed varius</p>
        <footer>John Doe</footer>
    </blockquote>
    
    ```
    
    - **`<blockquote>`**: Defines a section quoted from another source. Browsers typically indent this section.
    - **`<footer>`**: Represents the source of the quotation (e.g., John Doe) at the end of the blockquote.
    
    ---
    
    ### 3. **Combining Tags**
    
    You can combine tags inside one another to apply multiple formatting styles.
    
    ### Example: Bold and Italic Combined
    
    ```html
    <b>bold. <i> italic and bold</i></b> <br />
    
    ```
    
    - **Explanation**: This text combines both the `<b>` and `<i>` tags, making "bold." bold and "italic and bold" both italicized and bold.
    
    ### 4. **Line Breaks**
    
    In between most of the examples, you have included the `<br>` tag, which adds a line break between different text elements.
    
    ### Example:
    
    ```html
    <br>
    ```
    
    - **`<br>`**: Adds a break between lines of text.
    
    ---
    
    ### Full Comment of Code:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="chrome">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Styling HTML Elements</title>
        <style>
            /* Set background color of the entire page */
            body {
              background-color: #323032; /* Property: background-color, Value: #323032 (dark grey) */
            }
    
            /* Style for the h1 header */
            h1 {
              color: rgb(255, 255, 255); /* Property: color, Value: rgb(255, 255, 255) for white */
              text-align: center; /* Property: text-align, Value: center (aligns text in the middle of the page) */
            }
          </style>
    </head>
    <body style="color: white;"> <!-- Inline styling, color property set to white for the body text -->
        <h1 style="color: white;">Bangladesh</h1> <!-- Inline styling for h1 header, color set to white -->
    
        <!-- Bold and strong tags are quite similar -->
        <b>This is a bold Text</b> <br> <!-- Bold text using <b> tag -->
        <strong>This is strong Text </strong><br> <!-- Strong importance, also makes text bold -->
    
        <!-- Italic and emphasize tags are quite similar -->
        <i>This is an italic text</i> <br /> <!-- Italic text using <i> tag -->
        <em>This is an emphasize text</em> <br /> <!-- Emphasize text, also makes it italicized -->
    
        <!-- Underline text -->
        <u>This is an underline text</u> <br /> <!-- Underlines the text using <u> tag -->
    
        <!-- Tags can be nested inside each other -->
        <b>bold. <i> italic and bold</i></b> <br /> <!-- Combines bold and italic styles -->
    
        <!-- Strike-through text -->
        <strike>This is a strike text</strike><br> <!-- Adds a strike-through line over the text -->
    
        <!-- Superscript example -->
        (a+b) <sup>2</sup>=a<sup>2</sup>+2ab+b <sup>2</sup> <br> <!-- Superscript for mathematical power -->
    
        <!-- Subscript example -->
        H<sub>2</sub>O <br> <!-- Subscript for chemical formulas like H2O -->
    
        <!-- Highlight important text -->
        <mark>Important task should be highlighted</mark> <br /> <!-- Highlights text with background color -->
    
        <!-- Deleted text -->
        <del>This is a deleted text</del> <br /> <!-- Displays text with a line through it, indicating deletion -->
    
        <!-- Preformatted text, maintains spaces and line breaks -->
        <pre>
            This is a
              life-changing documentation
            Read, learn, enjoy
              of course, share with others
        </pre> <!-- Preformatted text preserves the original formatting -->
    
        <!-- Abbreviation with a tooltip -->
        <abbr title="Google is a search engine">Google</abbr> <br> <!-- Abbreviation with a full explanation on hover -->
    
        <!-- Address block -->
        <address>561, ABC road, Dhaka-1216, Bangladesh</address><br> <!-- Used for contact information or physical address -->
    
        <!-- Blockquote, typically indented -->
        <blockquote>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed varius</p> <!-- Quoted text -->
            <footer>John Doe</footer> <!-- Source of the quote -->
        </blockquote>
    
    </body>
    </html>
    ```
    
    ### Output of Code: 
    ![1](https://i.imgur.com/N92Y1z3.png)
</details>

<details>
    <summary>Day 03 (html Entity, Font style, Symbol & Emojis) </summary>

- 
    ### Description:
    
    1. **Bangla Writing:**
        
        ```html
        <h4>শুভ রাত্রি</h4>
        
        ```
        
        - This line displays the text "শুভ রাত্রি" (meaning "Good Night" in Bengali) inside an `<h4>` heading tag, written using the **Avro keyboard** for typing Bengali.
    2. **Entities:**
        - Entities are used to display special characters in HTML that have reserved meanings. For example, `&lt;` is used to display `<` and `&gt;` to display `>`.
        
        ```html
        <p>Hello &nbsp; &nbsp; &nbsp; Bangladesh</p>
        &lt; hello &gt;<p>
        &ltcc;Hi&gtcc;<p>
        &DoubleVerticalBar; Bye Bye &DoubleVerticalBar;
        <footer>&copy; Tumpa Moni Mim</footer>
        
        ```
        
        - `&nbsp;`: Adds non-breaking spaces between "Hello" and "Bangladesh".
        - `&lt;` and `&gt;`: Displays the angle brackets `<` and `>` around the word "hello".
        - `&copy;`: Displays the copyright symbol © followed by "Tumpa Moni Mim".
        - `&DoubleVerticalBar;`: Displays the double vertical bar `‖`, used here in the phrase "Bye Bye".
    3. **Symbols and Emoji:**
        
        ```html
        &#9749;  <!-- Displays a coffee cup emoji ☕ -->
        &#11093; <!-- Displays a heavy large circle emoji ⭕ -->
        &#127803; <!-- Displays a sunflower emoji 🌻 -->
        
        ```
        
        - `&#9749;`: Displays the ☕ (coffee cup) emoji.
        - `&#11093;`: Displays the ⭕ (heavy large circle) emoji.
        - `&#127803;`: Displays the 🌻 (sunflower) emoji.
    4. **Font Styling:**
        
        ```html
        <p style="background-color: rgb(50, 49, 49); color: white; font-size: 28px; font-family: monospace;">Font Style</p>
        
        ```
        
        - This paragraph uses inline styling to apply specific font and background styles:
            - `background-color: rgb(50, 49, 49)`: Sets the background color to a dark shade.
            - `color: white`: Changes the text color to white.
            - `font-size: 28px`: Makes the font size 28 pixels.
            - `font-family: monospace`: Sets the font family to monospace, a fixed-width font where each character takes up the same amount of space.
    
    ---
    
    ### Entity Explanation:
    
    Entities are used in HTML to represent special characters that have a specific meaning in the markup language, preventing them from being interpreted as part of the code. Here are some of the entities used in the code:
    
    - ****: Represents a non-breaking space, useful for adding extra spaces between text without collapsing.
    - **©**: Represents the copyright symbol `©`.
    - **<**: Represents the less-than symbol `<`.
    - **>**: Represents the greater-than symbol `>`.
    - **∥**: Represents the double vertical bar symbol `‖`, used as a separator.
    
    ### Symbols & Emoji:
    
    HTML allows you to represent symbols and emoji using numeric character references, such as `&#9749;` for the ☕ (coffee cup) emoji. These are typically displayed as visual symbols across different platforms.
    
    ### Font Styling:
    
    Font styling controls the visual appearance of text. In the given code:
    
    - Background color (`background-color`) defines the background shade of the text.
    - Text color (`color`) defines the color of the text itself.
    - Font size (`font-size`) determines how large the text appears.
    - Font family (`font-family`) sets the style of the text, with "monospace" providing equal space for each character, useful for readability in code or aligned text.
    
    **Sources for adding symbol, icons and emoji**
    
    - Unicode character website: [https://unicode-table.com/en/](https://unicode-table.com/en/)
    - W3School emoji link: [https://www.w3schools.com/charsets/ref_emoji.asp](https://www.w3schools.com/charsets/ref_emoji.asp)
    - iconfinder icon link: [https://www.iconfinder.com/](https://www.iconfinder.com/)
    - Pick image from [unsplash](https://unsplash.com/)
    - Choose color from
        - [colorhunt](https://colorhunt.co/)
        - [imagecolorpicker](https://imagecolorpicker.com/)
        - [htmlcolorcodes](https://htmlcolorcodes.com/)
    
    ### Code Snippet:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
    
        <!-- Bangla writing -->
        <h4>শুভ রাত্রি</h4>
    
        <!-- entity -->
        <p>Hello &nbsp; &nbsp; &nbsp; Bangladesh</p>
        &lt; hello &gt;<p>
        &ltcc;Hi&gtcc;<p>
        &DoubleVerticalBar; Bye Bye &DoubleVerticalBar;
        <footer>&copy; Tumpa Moni Mim</footer>
    
        <!-- symbol and emoji -->
    
        &#9749;
        &#11093;
        &#127803;
    
        <!-- font styling -->
    
        <p style="background-color: rgb(50, 49, 49); color: white; font-size: 28px; font-family: monospace;">Font Style</p>
    </body>
    </html>
    
    ``` 
    ### Output of Code: 
    ![1](https://i.imgur.com/h1ElZcO.png)
</details>
<details>
<summary>Day 04 (HTML List, Image & Iframe)</summary>
   
- 
    ### **1. LISTS in HTML**
    
    HTML supports two main types of lists: Ordered and Unordered lists.
    
    ### **Ordered List (`<ol>`)**
    
    - **Description**: An ordered list is used to display items in a specific order. Each item in the list is numbered by default, but we can change the numbering style using attributes.
    - **Attributes**:
        - **start**: This attribute specifies the number (or letter) the list should start from. By default, ordered lists start at 1, but you can change it to any number or letter.
        - **type**: This attribute changes the numbering style of the list. It can be:
            - `1` for regular numbers (default).
            - `a` for lowercase letters.
            - `A` for uppercase letters.
            - `i` for lowercase Roman numerals.
            - `I` for uppercase Roman numerals.
    - **Example**:
        
        ```html
        <!--Regular Ordered List-->
        <h2>Courses List</h2>
        <ol>
        	<li>Operating System</li>
        	<li>Software Engineering</li>
          <li>Graphics Design</li>
        </ol>
        
        <!--Ordered List Starting at 4-->
        <h2>Additional Courses List</h2>
        <ol start="4">
          <li>Theory of Computing</li>
          <li>AI</li>
          <li>Web3 Programming</li>
        </ol>
        
        <!--Lowercase Letters-->
        <h2>a Courses</h2>
        <ol type="a">
        	<li>Sociology</li>
          <li>Psychology</li>
        </ol>>
        
        <!--Uppercase Letters-->
        <h2>A Courses</h2>
        <ol type="A">
        	<li>Physic</li>
        	<li>Chemistry</li>
        </ol>
        
        <h2>Roman Numerals</h2>
        <ol type="I">
          <li>Country</li>
          <li>City</li>
        </ol>
        
        ```
        
        In these examples:
        
        - The first list is a simple numbered list starting at 1.
        - The second list starts numbering at 4 instead of 1.
        - The third list uses lowercase letters (`a, b, c...`) instead of numbers.
        - The fourth list uses uppercase letters ( `A, B, C...` ).
        - The last list uses  Roman numerals (`I, II, III...`).
    
    ### **Unordered List (`<ul>`)**
    
    - **Description**: An unordered list is used when the order of items doesn’t matter. Instead of numbers, it uses bullets or other symbols to display each list item.
    - **Attributes**:
        - **type**: This attribute defines the bullet style for the list. It can be:
            - `disc` for solid bullet points (default).
            - `circle` for hollow circle bullets.
            - `square` for square bullets.
    - **Example**:
        
        ```html
        <!--Regular Unordered List-->
        <h2>Fruit</h2>
        <ul>
        	<li>Mango</li>
        	<li>Guava</li>
        </ul>
        
        <!--Circle Bullets-->
        <h2>Color</h2>
        <ul type="circle">
        	<li>Red</li>
        	<li>Purple</li>
        </ul>
        
        <!--Square Bullets-->
        <h2>Flower</h2>
        <ul type="square">
        	<li>Lavender</li>
        	<li>Tulip</li>
        </ul>
        
        ```
        
        In these examples:
        
        - The first list uses the default solid bullet.
        - The second list uses hollow circle bullets.
        - The third list uses square-shaped bullets.
    
    ### **Nested List**

    A **nested list** is a list within another list, and it is represented in HTML using `<ul>` (unordered list) or `<ol>` (ordered list) tags. In this case, you used an unordered list `<ul>`. Each item in the list is marked by a bullet point.

    - **Outer List**:
    - The outer list has two main categories:
        1. **Frontend Development**: Focuses on the development of the user interface (UI).
        2. **Backend Development**: Handles the server-side, databases, and application logic.
    - **Inner Lists**:
    - **Frontend Development**:
        - Contains three technologies:
            1. **HTML**: The language used to structure the content on a webpage.
            2. **CSS**: The styling language to design and layout web pages.
            3. **JavaScript**: A programming language for adding interactivity.
    - **Backend Development**:
        - Contains two technologies for server-side development:
            1. **Node.js**: A JavaScript runtime that allows server-side scripting.
            2. **Express.js**: A web framework for Node.js to build web applications.
        - Another nested list is inside **Backend Development** for **Databases**, containing:
            1. **MySQL**: A relational database management system.
            2. **MongoDB**: A NoSQL database system for handling large amounts of unstructured data.

    ### **Definition List**

    A **definition list** is a list of terms and their corresponding definitions. It is represented in HTML using `<dl>` (definition list), `<dt>` (definition term), and `<dd>` (definition description) tags.

    - **Terms and Descriptions**:
    - **HTML**:
        - **Term**: HyperText Markup Language.
        - **Description**: It is the standard language used to create and structure web pages.
    - **CSS**:
        - **Term**: Cascading Style Sheets.
        - **Description**: It is used to add styles like colors, fonts, and layout to HTML elements.
    - **JavaScript**:
        - **Term**: A programming language.
        - **Description**: It allows you to create dynamic, interactive effects such as animations, form validations, and real-time updates on web pages.
    ---
    
    ### **2. IMAGE Tag (`<img>`)**
    
    The `<img>` tag is used to insert an image into your HTML document. It is a self-closing tag, which means it doesn't need a closing tag like `<img></img>`.
    
    - **Attributes**:
        - **src**: Specifies the source of the image, either from your local files (e.g., `cat.jpg`) or from a web URL (e.g., `https://example.com/image.jpg`).
        - **alt**: Provides alternative text that describes the image if it can't be displayed (useful for accessibility).
        - **height** and **width**: Control the size of the image in pixels.
        - **border**: Adds a border around the image. You can specify the width of the border in pixels.
        - **title**: Displays a tooltip text when you hover over the image.
        - **align**: Specifies the alignment of the image (e.g., `left`, `right`, `center`).
        - **vspace**: Adds vertical spacing around the image (above and below).
        - **hspace**: Adds horizontal spacing around the image (left and right).
    - **Example**:
        
        ```html
        <h2>Image with Border, Spacing, and Title</h2>
         <img src="cat.jpg" alt="Cat" height="300px" width="400px" border="20px" title="Tumpa" align="left" hspace="20px" vspace="20px" >
        
        ```
        
        **Explanation**:
        
        - `src="cat.jpg"`: Loads an image named `cat.jpg` from the same folder.
        - `alt="Cat"`: Displays this text if the image cannot be loaded.
        - `height="300"` and `width="400"`: Sets the image size to 300x400 pixels.
        - `border="20"`: Adds a 20-pixel wide border around the image.
        - `title="Tumpa"`: Displays "Tumpa" when you hover over the image.
        - `align="left"`: Aligns the image to the left side of the content.
        - `hspace="20"` and `vspace="20"`: Adds 20px of space around the image horizontally and vertically.
    
    ---
    
    ### **3. IFRAME (`<iframe>`)**
    
    An iframe is used to embed other HTML documents or web content within your current webpage. It's like showing a mini browser window inside your page.
    
    - **Attributes**:
        - **src**: Specifies the URL of the page or content to display inside the iframe.
        - **height** and **width**: Set the height and width of the iframe in pixels.
        - **frameborder**: Defines whether or not the iframe should have a border (`1` for yes, `0` for no).
        - **allowfullscreen**: Allows the iframe to display content in full-screen mode (commonly used for videos).
        - **referrerpolicy**: Specifies how much information about the current page is sent to the embedded content.
    
    ### **Embedding a YouTube Video**
    
    You can use an iframe to embed a YouTube video by specifying the video URL.
    
    - **Example**:
        
        ```html
        <h2>Embedded YouTube Video</h2>
        <iframe width="400" height="300" src="https://www.youtube.com/embed/zsYMgmb2oCM?si=_bkWRcEtnom1lMef" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
        </iframe>
        
        ```
        
        **Explanation**:
        
        - `src="<https://www.youtube.com/embed/zsYMgmb2oCM?si=_bkWRcEtnom1lMef>"`: The link to the YouTube video you want to embed.
        - `allowfullscreen`: Allows the user to view the video in full-screen mode.
        - The other attributes control the size and behavior of the iframe.
    
    ### **Embedding a Website**
    
    You can also embed a webpage in an iframe.
    
    - **Example**:
        
        ```html
        <h2>Embedded Prothom Alo Website</h2>
        <iframe src="<https://www.prothomalo.com/>" frameborder="0" height="300" width="400">
        </iframe>
        
        ```
        
        **Explanation**:
        
        - `src="<https://www.prothomalo.com/>"`: Embeds the homepage of the Prothom Alo website.
        - The `frameborder="0"` removes the border around the iframe.
        - `height="300"` and `width="400"` control the size of the iframe.
    
    ---
    
    ### **Summary**
    
    - **Lists**: HTML supports ordered (`<ol>`) and unordered (`<ul>`) lists. Ordered lists are numbered, while unordered lists use bullets.
    - **Image Tag (`<img>`)**: This tag embeds images in your webpage. You can control the image size, add borders, and position it using attributes like `src`, `alt`, `height`, `width`, etc.
    - **Iframe (`<iframe>`)**: Iframes are used to embed external content like websites or videos into your webpage. You can adjust the size and appearance using attributes like `src`, `height`, `width`, and `frameborder`.

    ### Output of Code: 
    ![1](https://i.imgur.com/Qjgar8a.png)
    ![3](https://i.imgur.com/MEnzw0N.png)
    ![2](https://i.imgur.com/0rnO2AW.png)

</details>

<details>
    <summary>Day 05 (HTML Debugging, List, Anchor Tag, Div, Table, Form)</summary>
    
-   ## **Debugging**
    
    
    - Inspect Element: Within the browser developer tools, the "Inspect Element" feature allows you to examine and modify the HTML structure in real-time. You can navigate through the document tree, view CSS styles, and experiment with changes to identify and fix layout or formatting issues.
    - Use Comments: Insert comments (`<!-- ... -->`) within your HTML code to temporarily remove or isolate sections of code that might be causing issues. This helps you narrow down the problematic area and identify the source of the problem.
    - After writing your html code you can check the validity on this website [https://validator.w3.org/](https://validator.w3.org/)
    
    ## **Lists in HTML with Attributes**
    
    Lists in HTML are used to group related items together. HTML provides various types of lists to represent different kinds of information: ordered lists, unordered lists, and definition lists. Each type of list has attributes that can modify its behavior or appearance. Here’s a detailed explanation of each type with relevant attributes:
    
    ### **Ordered List (`<ol>`)**
    
    An ordered list is created to list programming subjects. There are two `<ol>` tags:
    
    - The first list starts with items numbered 1, 2, and 3.
    - The second list starts at number 4, containing links (both internal and external).
    
    **Key Code Snippet for Ordered List:**
    
    ```html
    <h1>Subject List</h1>
    <ol>
        <li>C</li>
        <li>C++</li>
        <li>OOP</li>
    </ol>
    
    ```
    
    ### **Unordered List (`<ul>`)**
    
    The unordered list is created using the `<ul>` tag, with each subject represented as an item in the list (`<li>`). The list contains three subjects:
    
    - PHP
    - Java
    - Web3
    
    An unordered list is used because there is no specific ranking or order of importance among the items.
    
    **Code Snippet:**
    
    ```html
    <ul>
        <li>PHP</li>
        <li>Java</li>
        <li>Web3</li>
    </ul>
    
    ```
    
    - The `<ul>` element creates the list, and the `<li>` elements represent the individual items (subjects) in the list.
    - Unordered lists typically display with bullet points.
    
    ---
    
    ### **Hyperlinks**
    
    Links are a fundamental aspect of web navigation, enabling users to move from one webpage to another or to different sections within a page. HTML uses anchor tags (`<a>`) to create hyperlinks. Here’s an in-depth look at links and navigation:
    
    ### **Attributes Used in Anchor Tags:**
    
    1. **`href`**:
        - **Description:** Specifies the URL or file path that the link points to. It is required for all anchor tags.
        - **Example:**
            
            ```html
            <a href="list.html">Internal Hyperlink</a>
            
            ```
            
    2. **`target`**:
        - **Description:** Specifies where to open the linked document. The common values are:
            - `_blank`: Opens the link in a new tab or window.
            - `_self`: Opens the link in the same tab or window (default behavior).
            - `_parent`: Opens the link in the parent frame.
            - `_top`: Opens the link in the full body of the window.
        - **Example:**
            
            ```html
            <a href="<https://github.com/tumpamim07>" target="_blank">External Hyperlink</a>
            
            ```
            
    3. **`title`** (Optional):
        - **Description:** Provides additional information about the link, often displayed as a tooltip when the user hovers over the link.
        - **Example:**
            
            ```html
            <a href="list.html" title="View the list of subjects">Title of Hyperlink</a>
            
            ```
            
    4. **`download`** (Optional):
        - **Description:** When added, the link will prompt the user to download the file instead of navigating to it. The value of this attribute can define the default file name.
        - **Example:**
            
            ```html
            <a href="html_tutorial.pdf">Download PDF</a>
            ```
            
    5. **`type`** (Optional):
        - **Description:** Specifies the media type of the linked document. This is helpful when linking to files other than HTML, such as images or documents.
        - **Example:**
            
            ```html
            <a href="image.png" type="image/png">Image Link</a>
            
            ```
            
    
    ### **Full Example of Anchor Tag with All Attributes:**
    
    ```html
    <ol start="4">
          <li>
            <a href="list.html" target="_blank">Internal Hyperlink</a> (<a
              href="/accessible_table.html"
              >Table</a
            >
            <a href="/directory/contact.html">Contact</a>
            <a href="../Day-01 (HTML Tags & Attribute)/index.html"
              >Other Directory</a
            >) <br />
          </li>
    
          <li>
            <a href="https://github.com/tumpamim07" target="_blank"
              >External Hyperlink</a
            >
          </li>
          <li>
            <a href="list.html" title="View the list of subjects"
              >Title of Hyperlink</a
            >
          </li>
          <li><a href="html_tutorial.pdf">Download PDF</a></li>
          <li><a href="table.png" type="image/png">Image Link</a></li>
        </ol>
    ```
    
    ### Output of the Code
    ![anchot tag](https://i.imgur.com/HdkGvLG.png)
    
    ### **Summary of Attributes:**
    
    - **`href`**: Specifies the URL or path of the linked document.
    - **`target`**: Defines where to open the link (same window, new tab, etc.).
    - **`title`**: Adds a tooltip that appears when hovering over the link.
    - **`download`**: Prompts a download instead of navigating.
    - **`type`**: Defines the media type of the linked file.
    
    These attributes allow you to customize how the link behaves and provides extra information for the user and browser.
    
    ### **`<div>` Elements with Inline Styling**
    
    Three `<div>` elements are used to create sections, each with a different background color, height, and width. Inline CSS is used for the following properties:
    
    - `background-color`: Sets the background color for each div.
    - `height`: Specifies the height of each div (100px).
    - `width`: Makes each div fill the entire width of the page (`100%`).
    
    **Key Code Snippet for `<div>` Elements:**
    
    ```html
    <div id="div1" style="background-color: rgb(248, 121, 16); height: 100px; width: 100%;">
        <p>Inside div 1</p>
    </div>
    
    <div id="div2" style="background-color: rgb(140, 72, 247); height: 100px; width: 100%;">
        <p>Inside div 2</p>
    </div>
    
    <div id="div3" style="background-color: rgb(242, 116, 194); height: 100px; width: 100%;">
        <p>Inside div 3</p>
    </div>
    
    ```
    
    ### Output of the Code
    ![index](https://i.imgur.com/XqLjVbW.png)
    
    ---
    
    ### Table
    
    ### **`<table>` Tag:**
    
    The `<table>` tag defines an HTML table. In this case, it contains student details, and it's styled using the `style` defined inside the `<head>` tag.
    
    **Code Snippet:**
    
    ```html
    <table>
        <caption>Student Details</caption>
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th>GPA</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Urmi</td>
                <td>3.98</td>
            </tr>
            <tr>
                <td>02</td>
                <td>Nila</td>
                <td>3.99</td>
            </tr>
            <tr>
                <td>03</td>
                <td>Nira</td>
                <td>3.74</td>
            </tr>
        </tbody>
    </table>
    
    ```
    
    ### **`<caption>` Tag:**
    
    The `<caption>` tag adds a title to the table. It is used to describe the content of the table, making it more accessible and readable. In this case, the caption is *"Student Details"*.
    
    **Code Snippet:**
    
    ```html
    <caption>Student Details</caption>
    
    ```
    
    ### **`<thead>` Tag:**
    
    The `<thead>` tag is used to group the header content of the table. It contains the column headers, which provide a label for each column.
    
    **Code Snippet:**
    
    ```html
    <thead>
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>GPA</th>
        </tr>
    </thead>
    
    ```
    
    ### **`<tr>` Tag (Inside `<thead>`):**
    
    The `<tr>` tag defines a row in the table. In this case, it creates a single row for the column headers (ID, Name, GPA).
    
    **Code Snippet:**
    
    ```html
    <tr>
        <th>ID</th>
        <th>Name</th>
        <th>GPA</th>
    </tr>
    
    ```
    
    ### **`<th>` Tag:**
    
    The `<th>` tag defines a header cell in the table. It is typically bold and centered by default. In this case, the `<th>` tags are used for the three column headers: ID, Name, and GPA.
    
    **Code Snippet:**
    
    ```html
    <th>ID</th>
    <th>Name</th>
    <th>GPA</th>
    
    ```
    
    ### **`<tbody>` Tag:**
    
    The `<tbody>` tag groups the body content of the table, i.e., the actual data (rows) under the headers. Each row contains the student data.
    
    **Code Snippet:**
    
    ```html
    <tbody>
        <tr>
            <td>1</td>
            <td>Urmi</td>
            <td>3.98</td>
        </tr>
        <tr>
            <td>02</td>
            <td>Nila</td>
            <td>3.99</td>
        </tr>
        <tr>
            <td>03</td>
            <td>Nira</td>
            <td>3.74</td>
        </tr>
    </tbody>
    
    ```
    
    ### **`<tr>` Tag (Inside `<tbody>`):**
    
    Each `<tr>` tag inside the `<tbody>` tag represents a row of data for the students. Each row corresponds to one student's details, containing three cells: ID, Name, and GPA.
    
    **Code Snippet:**
    
    ```html
    <tr>
        <td>1</td>
        <td>Urmi</td>
        <td>3.98</td>
    </tr>
    
    ```
    
    ### **`<td>` Tag:**
    
    The `<td>` tag defines a standard data cell in a table. It is used inside the `<tr>` tag to contain individual pieces of data. In this case, the data includes the student IDs, names, and GPAs.
    
    **Code Snippet:**
    
    ```html
    <td>1</td>
    <td>Urmi</td>
    <td>3.98</td>
    
    ```
    
    ### Summary:
    
    - **`<table>`**: Defines the table structure.
    - **`<caption>`**: Adds a title to the table.
    - **`<thead>`**: Contains the table headers (`<th>` for each column).
    - **`<tbody>`**: Contains the actual data rows (`<td>` for each cell).
    - **`<tr>`**: Creates rows in the table.
    - **`<td>` and `<th>`**: Define individual cells, with `<th>` used for headers and `<td>` for data.
    
    ### **CSS Styling Explanation (Applied to the Table Elements):**
    
    - **Table Style:**
        - `border: 2px solid black;`: Adds a black border around the table and cells.
        - `border-spacing: 15px;`: Adds 15px spacing between table cells.
        - `height` and `width`: Set the table's dimensions.
    - **`th, td` Style:**
        - `padding: 15px;`: Adds padding inside the table cells to make the content more readable.
        - `border: 2px solid black;`: Each cell has a 2px black border.
    - **`tr` Style:**
        - `text-align: center;`: Centers the text inside each row.
    
    ---
    
    ### **Complete Code:**
    
    Here’s the complete body of the table along with all the key tags described above:
    
    ```html
    <body>
        <!-- table -->
        <table>
            <caption>Student Details</caption>
            <thead>
                <tr>
                    <th>ID</th>
                    <th>Name</th>
                    <th>GPA</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>Urmi</td>
                    <td>3.98</td>
                </tr>
    
                <tr>
                    <td>02</td>
                    <td>Nila</td>
                    <td>3.99</td>
                </tr>
    
                <tr>
                    <td>03</td>
                    <td>Nira</td>
                    <td>3.74</td>
                </tr>
            </tbody>
        </table>
    </body>
    
    ```
    
    ### Output of the Code
    ![table](https://i.imgur.com/3eqhM0u.png)
    
    ---
    
    ### `colspan` and `rowspan` in HTML Tables
    
    ### 1. **`colspan`** (Column Span)
    
    The `colspan` attribute allows a cell to span across multiple columns.
    
    ### Example:
    
    Let's look at a table with the `colspan` attribute:
    
    ```html
    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th colspan="2">Phone</th> <!-- spans across 2 columns -->
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>001</td>
                <td>Urmi</td>
                <td>014</td>
                <td>017</td>
            </tr>
            <tr>
                <td>002</td>
                <td>Niya</td>
                <td>013</td>
                <td>017</td>
            </tr>
        </tbody>
    </table>
    
    ```
    
    - The table header `Phone` spans across two columns because of `colspan="2"`.
    - This means that instead of having separate headers for each phone number, you have one `Phone` header that covers two data columns.
    - The rows beneath it (`Urmi` and `Niya`) have two separate columns for phone numbers.
    
    ---
    
    ### 2. **`rowspan`** (Row Span)
    
    The `rowspan` attribute allows a cell to span across multiple rows.
    
    ### Example:
    
    Now, let's look at an example with `rowspan`:
    
    ```html
    <table>
        <thead>
            <tr>
                <th>ID</th>
                <th>Name</th>
                <th colspan="2">Phone</th> <!-- spans across 2 columns -->
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>001</td>
                <td>Urmi</td>
                <td>014</td>
                <td rowspan="3">017</td> <!-- spans across 3 rows -->
            </tr>
            <tr>
                <td>002</td>
                <td>Niya</td>
                <td>013</td>
            </tr>
            <tr>
                <td>003</td>
                <td>Rubi</td>
                <td>014</td>
            </tr>
        </tbody>
    </table>
    
    ```
    
    - The cell containing the value `017` in the third column is using `rowspan="3"`, meaning it spans across 3 rows.
    - So, instead of having the `017` value appear in each row individually, it appears only once and stretches across all three rows.
    
    ---
    
    ### Key Differences:
    
    - **`colspan`** is used when you want a cell to span multiple columns (horizontal stretching).
    - **`rowspan`** is used when you want a cell to span multiple rows (vertical stretching).
    
    ### Example Visualization:
    
    If you visualize the table structure, the first table with `colspan` will look like this:
    
    For `rowspan`, the table looks like this:
    
    In this second table, `017` spans vertically across all three rows.
    
    ### Conclusion:
    
    - **`colspan`** is used to combine multiple columns under one cell.
    - **`rowspan`** is used to combine multiple rows under one cell.
    
    ### Output of the Code
    ![rowspan colspan](https://i.imgur.com/Qx9jor3.png)
    
    ---
    
    ### Accessible HTML Table
    
    Accessibility in web design ensures that websites are usable by people of all abilities and disabilities. An accessible table provides clear structure and semantics so screen readers and other assistive technologies can easily interpret the data.
    
    ### Key Components for Accessibility:
    
1. **`<caption>` Element**:
    The `<caption>` element provides a description or title for the table. It helps screen readers understand the table's purpose.
        
    ```html
        <caption>Students Info</caption>
        
    ```
        
    - This caption, "Students Info", gives context to what the table represents.

2. **`<colgroup>` and `<col>`**:
    The `<colgroup>` and `<col>` elements allow you to apply styles or properties to specific columns. This enhances readability and helps assistive technologies identify column structures.
        
    ```html
        <colgroup>
            <col span="3" style="background-color: burlywood;" />
        </colgroup>
        
    ```
        
    - Here, the background color `burlywood` is applied to all three columns to help visually distinguish them. It improves clarity for users with visual impairments by providing a subtle visual cue.
3. **`<th>` with `scope` Attribute**:
    The `scope` attribute is used inside the `<th>` (table header) elements to explicitly define which cells the header refers to (columns or rows).
        
    ```html
        <thead>
            <tr>
                <th scope="col">ID</th>
                <th scope="col">Name</th>
                <th scope="col">GPA</th>
            </tr>
        </thead>
        
    ```
        
    - `scope="col"` tells assistive technologies that these headers apply to the columns. This is useful for visually impaired users using screen readers, allowing them to understand which header corresponds to which data in the columns.
4. **Row Headers with `scope="row"`**:
    The `<th>` tag is also used in the body of the table to identify row headers. These act as labels for the rows, and the `scope="row"` attribute ensures that screen readers associate the data cells in the row with this header.
        
    ```html
        <tr>
            <th scope="row">010</th>
            <td>Urmi</td>
            <td>3.99</td>
        </tr>
        
    ```
        
    - `scope="row"` tells screen readers that this header applies to the row it is in, so users can easily follow the data.
    
    ### Explanation of Accessibility Features:
    
    1. **`<caption>`**: Provides context about the table for all users, particularly useful for screen readers.
    2. **`scope="col"`**: Defines column headers, so screen readers know these headers apply to the columns.
    3. **`scope="row"`**: Defines row headers, so assistive technologies can connect the row data with the appropriate header.
    4. **`<colgroup>` and `<col>`**: Enhances readability by applying styles to entire columns.
    
    ### Benefits of Accessibility Features:
    
    - **Improved Usability**: By using proper headings and scopes, it ensures that all users, including those with disabilities, can navigate the table effectively.
    - **Screen Reader Support**: These features provide clear navigation paths for screen readers, helping users identify relationships between headers and data cells.
    - **Visual Distinction**: Applying styles like background colors can help users with visual impairments or color blindness to distinguish table sections more easily.
    
    ### Complete Code Example with Accessibility Features:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Accessible Table</title>
    </head>
    <body>
        <header>
            <h1>HTML Table</h1>
        </header>
        <main>
            <table>
                <caption>Students Info</caption> <!-- Table caption for description -->
                <colgroup>
                    <col span="3" style="background-color: burlywood;" /> <!-- Styling columns -->
                </colgroup>
                <thead>
                    <tr>
                        <th scope="col">ID</th> <!-- Column header with scope="col" -->
                        <th scope="col">Name</th>
                        <th scope="col">GPA</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th scope="row">010</th> <!-- Row header with scope="row" -->
                        <td>Urmi</td>
                        <td>3.99</td>
                    </tr>
    
                    <tr>
                        <td scope="row">011</td>
                        <td>Tonny</td>
                        <td>3.55</td>
                    </tr>
    
                    <tr>
                        <td scope="row">010</td>
                        <td>Laizu</td>
                        <td>3.65</td>
                    </tr>
                </tbody>
            </table>
        </main>
    </body>
    </html>
    ```
    
    ### Output of the Code
    ![accessible_table](https://i.imgur.com/iCfeoPw.png)
    
    ---
    
    ### **Form Basics**
    
    Forms are essential for collecting user input on web pages. HTML provides a variety of elements to create forms and handle user input effectively. Here’s a detailed explanation of the form elements, input types, and form attributes:
    
    ### 1. **Text Input Field**
    
    ```html
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    ```
    
    - **`<input type="text">`**: A single-line text box for inputting text.
    - **`name`**: Identifies the input field for data submission.
    - **`id`**: Used for the label to reference the input field.
    
    ---
    
    ### 2. **Password Input Field**
    
    ```html
    <label for="password">Password:</label>
    <input type="password" id="password" name="password">
    
    ```
    
    - **`<input type="password">`**: Masks the input with dots or asterisks, typically used for password entry.
    
    ---
    
    ### 3. **Email Input Field**
    
    ```html
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    ```
    
    - **`<input type="email">`**: Ensures the input is in the format of an email (e.g., [name@example.com](mailto:name@example.com)).
    
    ---
    
    ### 4. **Date Input Field**
    
    ```html
    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob">
    
    ```
    
    - **`<input type="date">`**: Provides a date picker interface for selecting a date.
    
    ---
    
    ### 5. **Radio Buttons**
    
    ```html
    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label>
    
    ```
    
    - **`<input type="radio">`**: Allows users to select one option from a group. All radio buttons with the same `name` are grouped together.
    
    ---
    
    ### 6. **Checkboxes**
    
    ```html
    <label>Choose your hobbies:</label>
    <input type="checkbox" id="reading" name="hobby" value="reading">
    <label for="reading">Reading</label>
    <input type="checkbox" id="traveling" name="hobby" value="traveling">
    <label for="traveling">Traveling</label>
    
    ```
    
    - **`<input type="checkbox">`**: Lets users select multiple options.
    
    ---
    
    ### 7. **Dropdown (Select Menu)**
    
    ```html
    <label for="country">Country:</label>
    <select id="country" name="country">
      <option value="us">USA</option>
      <option value="uk">UK</option>
      <option value="canada">Canada</option>
    </select>
    
    ```
    
    - **`<select>`**: Defines a dropdown list.
    - **`<option>`**: Defines the options inside the dropdown.
    
    ---
    
    ### 8. **Text Area**
    
    ```html
    <label for="comments">Comments:</label>
    <textarea id="comments" name="comments" rows="4" cols="50"></textarea>
    
    ```
    
    - **`<textarea>`**: Used for multi-line text input, such as comments or descriptions.
    
    ---
    
    ### 9. **File Input**
    
    ```html
    <label for="profile">Upload your profile picture:</label>
    <input type="file" id="profile" name="profile">
    
    ```
    
    - **`<input type="file">`**: Allows users to upload files (e.g., images, documents).
    
    ---
    
    ### 10. **Submit Button**
    
    ```html
    <input type="submit" value="Submit">
    
    ```
    
    - **`<input type="submit">`**: Submits the form data to the server.
    
    ---
    
    ### 11. **Reset Button**
    
    ```html
    <input type="reset" value="Reset">
    
    ```
    
    - **`<input type="reset">`**: Resets all form fields to their default values.
    
    ---
    
    ### 12. **Button**
    
    ```html
    <button type="button">Click Me</button>
    
    ```
    
    - **`<button>`**: Defines a clickable button, often used for JavaScript events or for submitting forms.
    
    ---
    
    ### **Example**
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form Example</title>
    </head>
    <body>
        <form action="submit.php" method="post">
            <!-- Text Input -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br><br>
    
            <!-- Email Input -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br><br>
    
            <!-- Date Input -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob">
            <br><br>
    
            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <br><br>
    
            <!-- Checkbox -->
            <label>Choose your hobbies:</label>
            <input type="checkbox" id="reading" name="hobby" value="reading">
            <label for="reading">Reading</label>
            <input type="checkbox" id="traveling" name="hobby" value="traveling">
            <label for="traveling">Traveling</label>
            <br><br>
    
            <!-- Dropdown -->
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="us">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
            </select>
            <br><br>
    
            <!-- Text Area -->
            <label for="comments">Comments:</label>
            <textarea id="comments" name="comments" rows="4" cols="50"></textarea>
            <br><br>
    
            <!-- File Upload -->
            <label for="profile">Upload your profile picture:</label>
            <input type="file" id="profile" name="profile">
            <br><br>
    
            <!-- Password Input -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password">
            <br><br>
    
            <!-- Submit Button -->
            <input type="submit" value="Submit">
    
            <!-- Reset Button -->
            <input type="reset" value="Reset">
        </form>
    </body>
    </html>
    ```
    
    **Common Input Types**:
    
    - `text`: Single-line text input.
    - `password`: Password input (masked characters).
    - `email`: Email address input.
    - `number`: Numeric input.
    - `date`: Date input.
    - `checkbox`: Checkbox input
    - `radio`: Radio button input.
    - `submit`: Submit button.
    - `reset`: Reset button.
    
    ---
    
    ### **Form Attributes**
    
    HTML form attributes define various behaviors and characteristics of a form element. Let's go through some of the most important form attributes with examples:
    
    ---
    
    ### 1. **`action` Attribute**
    
    - Specifies the URL where the form data will be sent upon submission.
    
    **Example:**
    
    ```html
    <form action="/submit_form.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - In this example, when the form is submitted, the data will be sent to `/submit_form.php`.
    
    ---
    
    ### 2. **`method` Attribute**
    
    - Defines how the form data should be submitted. The two common methods are:
        - **`GET`**: Data is appended to the URL.
        - **`POST`**: Data is sent as part of the HTTP request body (recommended for sensitive data).
    
    **Example:**
    
    ```html
    <form action="/submit_form.php" method="post">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - This form will use the **`POST`** method, which is better for security since the data is not visible in the URL.
    
    ---
    
    ### 3. **`enctype` Attribute**
    
    - Used when the form includes file uploads. It specifies how the form data should be encoded. The common value is **`multipart/form-data`**, which is necessary for file uploads.
    
    **Example:**
    
    ```html
    <form action="/upload.php" method="post" enctype="multipart/form-data">
        <label for="file">Choose a file:</label>
        <input type="file" id="file" name="file">
        <input type="submit" value="Upload">
    </form>
    
    ```
    
    - This form will allow users to upload a file.
    
    ---
    
    ### 4. **`target` Attribute**
    
    - Specifies where to display the response after the form is submitted.
        - **`_self`**: Default, loads in the same tab.
        - **`_blank`**: Opens in a new tab.
        - **`_parent`**: Loads in the parent frame.
        - **`_top`**: Loads in the full body of the window.
    
    **Example:**
    
    ```html
    <form action="/submit_form.php" target="_blank">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - The form response will be opened in a **new tab** (`_blank`).
    
    ---
    
    ### 5. **`autocomplete` Attribute**
    
    - Controls whether a form should automatically complete input fields based on the user's past inputs.
        - **`on`**: Enables autocomplete (default).
        - **`off`**: Disables autocomplete.
    
    **Example:**
    
    ```html
    <form action="/submit_form.php" autocomplete="off">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - The form's autocomplete is turned off, so the browser won't suggest previously entered values.
    
    ---
    
    ### 6. **`novalidate` Attribute**
    
    - Disables the HTML5 form validation that occurs when the form is submitted.
    
    **Example:**
    
    ```html
    <form action="/submit_form.php" novalidate>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - No form validation will be performed when this form is submitted, even if the input types (like email) require specific formats.
    
    ---
    
    ### 7. **`name` Attribute**
    
    - The `name` attribute defines the name of the form. This is helpful when the form is accessed via JavaScript.
    
    **Example:**
    
    ```html
    <form name="registrationForm" action="/submit_form.php">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username">
        <input type="submit" value="Register">
    </form>
    
    ```
    
    - In JavaScript, you can reference this form using `document.forms["registrationForm"]`.
    
    ---
    
    ### 8. **`accept-charset` Attribute**
    
    - Specifies the character encodings accepted by the server for form data submission.
    
    **Example:**
    
    ```html
    <form action="/submit_form.php" accept-charset="UTF-8">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>
    
    ```
    
    - This form will ensure that the data is encoded in **UTF-8** before sending it to the server.
    
    ---
    
    ### Complete Form Example Using All Attributes:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form Attributes Example</title>
    </head>
    <body>
        <h2>Register</h2>
        <form action="/submit_form.php" method="post" enctype="multipart/form-data" target="_blank" autocomplete="on" accept-charset="UTF-8" name="registrationForm">
            <!-- Text Input -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br><br>
    
            <!-- Email Input -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br><br>
    
            <!-- File Upload -->
            <label for="file">Upload your profile picture:</label>
            <input type="file" id="file" name="file">
            <br><br>
    
            <!-- Submit Button -->
            <input type="submit" value="Submit">
        </form>
    </body>
    </html>
    
    ```
    
    ### Explanation:
    
    - **`action="/submit_form.php"`**: Sends form data to this server-side script.
    - **`method="post"`**: Data will be sent using the POST method.
    - **`enctype="multipart/form-data"`**: Supports file uploads.
    - **`target="_blank"`**: Opens the form result in a new tab.
    - **`autocomplete="on"`**: Enables autocomplete for the form fields.
    - **`accept-charset="UTF-8"`**: Ensures that the data is encoded in UTF-8.
    - **`name="registrationForm"`**: Sets the form name for JavaScript interaction.
    
    ---
    
    ### Registration Form:
    
    This HTML code represents a **Registration Form** with various input fields such as text boxes, email input, file uploads, radio buttons, checkboxes, a dropdown menu, a text area, and password inputs. 
    
    ---
    
    ### 1. **Form Tag**
    
    ```html
    <form action="">
    
    ```
    
    - The `<form>` element wraps all the input fields. The `action=""` attribute defines where to send form data when submitted. In this case, it’s empty, meaning no URL is specified.
    
    ---
    
    ### 2. **Username (Text Input)**
    
    ```html
    <div>
        <label for="fullname">Username: </label>
        <input type="text" name="username" id="username" required readonly>
    </div>
    
    ```
    
    - **`<label>`**: Associated with the input field via the `for` attribute to describe the purpose of the input.
    - **`<input type="text">`**: Used to collect the username. It has two additional attributes:
        - `required`: Ensures that the field must be filled before submitting.
        - `readonly`: Makes the field non-editable by the user.
    
    ---
    
    ### 3. **Full Name (Text Input)**
    
    ```html
    <div>
        <label for="fullname">Full Name: </label>
        <input type="text" name="fullname" id="fullname" required>
    </div>
    
    ```
    
    - **`<input type="text">`**: Standard text input to collect the full name. The `required` attribute ensures that it must be filled.
    
    ---
    
    ### 4. **Email (Email Input)**
    
    ```html
    <div>
        <label for="email">Email: </label>
        <input type="email" name="email" id="email">
    </div>
    
    ```
    
    - **`<input type="email">`**: Input field for collecting email addresses. It ensures the user inputs a properly formatted email address.
    
    ---
    
    ### 5. **Date of Birth (Date Input)**
    
    ```html
    <div>
        <label for="dob">Date of Birth: </label>
        <input type="date" name="dob" id="dob">
    </div>
    
    ```
    
    - **`<input type="date">`**: Collects a date from the user using a date picker.
    
    ---
    
    ### 6. **Photo Upload (File Input)**
    
    ```html
    <div>
        <label for="photo">Choose Your Photo: </label>
        <input type="file" name="photo" id="photo">
    </div>
    
    ```
    
    - **`<input type="file">`**: Allows the user to upload a file, typically used for uploading images.
    
    ---
    
    ### 7. **Gender (Radio Buttons)**
    
    ```html
    <div>
        <label for="gender">Gender: </label>
        <input type="radio" name="gender" id="gender" value="male">Male
        <input type="radio" name="gender" id="gender" value="female">Female
    </div>
    
    ```
    
    - **`<input type="radio">`**: Lets the user select one option from the given choices (male or female). Both radio buttons share the same `name` attribute (`gender`), so only one can be selected at a time.
    
    ---
    
    ### 8. **Religion (Checkboxes)**
    
    ```html
    <div>
        <label for="religion">Religion: </label>
        <input checked type="checkbox" name="c1" id="muslim" value="muslim">Muslim
        <input type="checkbox" name="c1" id="hindu" value="hindu">Hindu
    </div>
    
    ```
    
    - **`<input type="checkbox">`**: Allows the user to select one or more options. The `checked` attribute makes the "Muslim" checkbox preselected.
    
    ---
    
    ### 9. **Department (Dropdown)**
    
    ```html
    <div>
        <label for="department">Department: </label>
        <select name="department" id="department">
            <option value="CSE">CSE</option>
            <option selected value="EEE">EEE</option>
            <option value="LLB">LLB</option>
        </select>
    </div>
    
    ```
    
    - **`<select>`**: Defines a dropdown menu, and the `<option>` tags inside define the options.
    - **`selected`**: The option with `value="EEE"` is preselected when the form loads.
    
    ---
    
    ### 10. **Message (Text Area)**
    
    ```html
    <div>
        <label for="message">Message</label>
        <textarea cols="20" rows="10" name="message" id="message"></textarea>
    </div>
    
    ```
    
    - **`<textarea>`**: Creates a multi-line text input. The `cols` and `rows` attributes define the size of the text box.
    
    ---
    
    ### 11. **Password (Password Input)**
    
    ```html
    <div>
        <label for="password">Password: </label>
        <input type="password" name="password" id="password">
    </div>
    
    ```
    
    - **`<input type="password">`**: Used to collect passwords. The input characters will be masked (hidden) for security.
    
    ---
    
    ### 12. **Submit and Reset Buttons**
    
    ```html
    <div>
        <input type="submit" value="Register">
        <input type="reset" value="Clear" disabled>
    </div>
    
    ```
    
    - **`<input type="submit">`**: Button to submit the form.
    - **`<input type="reset">`**: Button to reset (clear) all form fields, but it is disabled with the `disabled` attribute, so it cannot be clicked.
    
    ---
    
    ### Complete Code Breakdown:
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form</title>
    </head>
    <body>
        <h2>Registration Form</h2>
        <form action="">
            <div>
                <label for="fullname">Username: </label>
                <input type="text" name="username" id="username" required readonly>
            </div>
            <br>
            <div>
                <label for="fullname">Full Name: </label>
                <input type="text" name="fullname" id="fullname" required>
            </div>
            <br>
            <div>
                <label for="email">Email: </label>
                <input type="email" name="email" id="email">
            </div>
            <br>
            <div>
                <label for="dob">Date of Birth: </label>
                <input type="date" name="dob" id="dob">
            </div>
            <br>
            <div>
                <label for="photo">Choose Your Photo: </label>
                <input type="file" name="photo" id="photo">
            </div>
            <br>
            <div>
                <label for="gender">Gender: </label>
                <input type="radio" name="gender" id="gender" value="male">Male
                <input type="radio" name="gender" id="gender" value="female">Female
            </div>
            <br>
            <div>
                <label for="religion">Religion: </label>
                <input checked type="checkbox" name="c1" id="muslim" value="muslim">Muslim
                <input type="checkbox" name="c1" id="hindu" value="hindu">Hindu
            </div>
            <br>
            <div>
                <label for="department">Department: </label>
                <select name="department" id="department">
                    <option value="CSE">CSE</option>
                    <option selected value="EEE">EEE</option>
                    <option value="LLB">LLB</option>
                </select>
            </div>
            <br>
            <div>
                <label for="message">Message</label>
                <textarea cols="20" rows="10" name="message" id="message"></textarea>
            </div>
            <br>
            <div>
                <label for="password">Password: </label>
                <input type="password" name="password" id="password">
            </div>
            <br>
            <div>
                <input type="submit" value="Register">
                <input type="reset" value="Clear" disabled>
            </div>
        </form>
    </body>
    </html>
    
    ```
    ### Output of the Code
    ![form](https://i.imgur.com/8W56nSQ.png)

    ---
    
    This form covers a wide range of HTML input types (text, email, password, file, radio, checkbox, select, textarea). Each field uses relevant attributes (`required`, `readonly`, `checked`, etc.) to enhance functionality and user experience. The `submit` and `reset` buttons complete the form, though the reset button is disabled in this case.

</details>