
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