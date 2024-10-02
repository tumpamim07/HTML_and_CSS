
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