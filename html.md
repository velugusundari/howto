# HTML
 
HTML is the standard markup language for creating web pages
* HTML standas for hyper text markup language
* HTML elements are represented by tags
* HTML tags label pieces of content such as "heading", "paragraph", "table", and so on

### HTML Documents
    All HTML documents must start with a document type declaration: <!DOCTYPE html>.
    The HTML document itself begins with <html and ends with </html>.
    The visible part of the HTML document is between <body> and </body>.

### HTML Headings
    HTML headings are defined with the <h1> to <h6> tags.
    <h1> defines the most important heading. <h6> defines the least important heading: 

#### EXAMPLE
    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <h3>This is heading 3</h3>
   
### HTML Paragraphs
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
   
### HTML Links
    HTML links are defined with the <a> tag:
#### Example
    <a href="https://www.w3schools.com">This is a link</a>
## HTML Attributes

#### href Attribute
    HTML links are defined with the <a> tag. The link address is specified in the href attribute:
#### Example
     <a href="https://www.w3schools.com">This is a link</a>
     The src Attribute

#### Image Attribute
      HTML images are defined with the <img> tag.
      The filename of the image source is specified in the src attribute:
#### Example
      <img src="img_girl.jpg">

#### The alt Attribute
      The alt attribute specifies an alternative text to be used, when an image cannot be displayed.
#### Example
      <img src="img_girl.jpg" alt="Girl with a jacket">
## HTML Styles

    The HTML style attribute has the following syntax:
    <tagname style="property:value;">

#### HTML Text Color
The color property defines the text color for an HTML element:
#### Example
     <h1 style="color:blue;">This is a heading</h1>
     <p style="color:red;">This is a paragraph.</p>
     
#### HTML Fonts
The font-family property defines the font to be used for an HTML element:
#### Example
     <h1 style="font-family:verdana;">This is a heading</h1>
     <p style="font-family:courier;">This is a paragraph.</p>
     
#### HTML Text Size
The font-size property defines the text size for an HTML element:
#### Example
      <h1 style="font-size:300%;">This is a heading</h1>
      <p style="font-size:160%;">This is a paragraph.</p>

## HTML Colors

In HTML, a color can be specified by using a color name:
#### Color Values
      In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, 
      and HSLA values:
      
## HTML Tables
    An HTML table is defined with the <table> tag.

    Each table row is defined with the <tr> tag. A table header is defined with the <th> tag. 
    By default, table headings arebold and centered. A table data/cell is defined with the <td> tag.
#### Example
      <table style="width:100%">
      <tr>
         <th>Firstname</th>
         <th>Lastname</th> 
         <th>Age</th>
     </tr>
     <tr>
         <td>Jill</td>
         <td>Smith</td> 
         <td>50</td>
     </tr>
     <tr>
         <td>Eve</td>
         <td>Jackson</td> 
         <td>94</td>
     </tr>
     </table>
     
#### HTML Table - Adding a Border
      If you do not specify a border for the table, it will be displayed without borders.
      A border is set using the CSS border property:
#### Example
      table, th, td {
        border: 1px solid black;
      }
