# HTML INTRODUCTION

## What is HTML

HTML stands for Hyper Text Markup Language. It is used to design web pages using a markup language. 
TML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages. 
A markup language is used to define the text document within tag which defines the structure of web pages.

* The main role of HTML is content and structure of the web page. 


## What is HTML5

HTML5 is the latest version of Hypertext Markup Language, the code that describes web pages. 
It's actually three kinds of code: HTML, which provides the structure; Cascading Style Sheets (CSS), which take care of presentation; and JavaScript, which makes things happen.

HTML5 is the latest evolution of the standard that defines HTML. The term represents two different concepts. 
It is a new version of the language HTML, with new elements, attributes, and behaviors, and a larger set of technologies that allows the building of more diverse and powerful Web sites and applications. 

    
## What is CSS

CSS stands for Cascading Style Sheets. CSS describes how HTML elements are to be displayed on screen, paper, or in other media. 
CSS saves a lot of work. It can control the layout of multiple web pages all at once. External stylesheets are stored in CSS files.

* CSS is the language we use to style an HTML document. CSS describes how HTML elements should be displayed.
    
    
### CSS has different formats - Inline and External CSS

### What is Inline CSS

Inline CSS is used to apply a unique style to a single HTML element. 
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

The example below shows how to change the text color and the left margin of a paragraph:

* < style="color:blue;margin-left:20px;">This is a paragraph.</*p>

The style attribute can contain any CSS property. The property must be specified using the camelCase (i.e., backgroundColor instead of background-color).

The style attribute can also contain multiple CSS properties. The properties must be separated by semicolons.



### What is External CSS

An external style sheet is ideal when the style is applied to many pages. With an external style sheet, you can change the look of an entire website by changing one file.

Each page must link to the style sheet using the <link> tag. The <link> tag goes inside the head section:

* <link rel="stylesheet" type="text/css" href="mystyle.css">

The href attribute specifies the path to the external style sheet. This example links to a style sheet from a file called "mystyle.css", which is stored in the same folder as the page. 
You can also provide a full URL to link to an external style sheet located on another server.

An external style sheet can be written in any text editor. The file should not contain any HTML tags. The style sheet file must be saved with a .css extension.

An external style sheet can also be linked to an HTML document using an import statement. This is done by adding an import statement to the style element.
       
          
<style>
@import url("mystyle.css");
</style>
        
* The @import statement must be at the top of the file, not inside any selectors.

The example below shows how to change the text color and the left margin of a paragraph using an external style sheet:


* <p>This is a paragraph.</p>

The example below shows how to change the text color and the left margin of a paragraph using an external style sheet:

p {

    color: blue;

    margin-left: 20px;

    }


### What is HTML Boilerplate

HTML5 Boilerplate is a professional front-end template for building fast, robust, and adaptable web apps or sites. 
This project is the product of many years of iterative development and combined community knowledge. 
It does not impose a specific development philosophy or framework, so you're free to architect your code in the way that you want.
    
    
### What is HTML DOCTYPE

The <!DOCTYPE html> declaration is the doctype declaration. It represents the document type, and helps browsers to display web pages correctly. 
* It must only appear once, at the top of the page (before any HTML tags).
    

### What is HTML Head

The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag. 
Metadata is data about the HTML document. Metadata is not displayed.

* Metadata typically define the document title, character set, styles, scripts, and other meta information.
    

### What is HTML Meta Tag

The <meta> tag provides metadata about the HTML document. Metadata will not be displayed on the page, but will be machine parsable. 
Meta elements are typically used to specify page description, keywords, author of the document, last modified, and other metadata.

The metadata can be used by browsers (how to display content or reload page), search engines (keywords), or other web services.

- Metadata is always passed as name/value pairs.

        <meta charset="UTF-8"> - Declares the character set of the document.

        <meta name="description" content="Free Web tutorials"> - Provides a description of the document. 
        This description will be used in the search results.

        <meta name="keywords" content="HTML, CSS, XML, JavaScript"> - Provides keywords for search engines.

        <meta name="author" content="John Doe"> - Provides the name of the author of the document.

        <meta http-equiv="refresh" content="30"> - Redirects to another page after 30 seconds.

        <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Provides the browser with information on how to control the page's dimensions and scaling.

        <meta http-equiv="X-UA-Compatible" content="ie=edge"> - Provides the browser with instructions on how to control the page's compatibility mode.

        <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Provides the browser with information on how to control the page's dimensions and scaling.

        <meta http-equiv="X-UA-Compatible" content="ie=edge"> - Provides the browser with instructions on how to control the page's compatibility mode.

        <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Provides the browser with information on how to control the page's dimensions and scaling.

        <meta http-equiv="X-UA-Compatible" content="ie=edge"> - Provides the browser with instructions on how to control the page's compatibility mode.

        <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Provides the browser with information on how to control the page's dimensions and scaling.

       

    ### What is HTML Body

    The "body" element contains all the contents of an HTML document, such as text, hyperlinks, images, tables, lists, etc.

    * Note: There should be only one "body" element in an HTML document.

    The "body" element is required in all HTML documents, and is the element that contains the content of the page.

    The "body" element is an example of a block-level element. A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

    Other common block-level elements are 
    <p></p> <div></div>

    The "body" element is the content of the document.

        

    
