
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
<summary>Day-04 (HTML List, Image & Iframe)</summary>
   
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