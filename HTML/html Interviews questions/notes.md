<!-- ! What is HTML -->
 <!-- ? 1. Html Stand for Hypertext Markup Language. 
      ? 2. It is used to design web-pages using a markup language
      ? 3. it is combination of Hypertext and Markup Language 
        Hypertext : It define the link between  web pages
        Markup Language: it define text document with in  the tag which define the structure of web pages.
      ? 4. HTML is used to structure the webpsite and therefore used for web devlopment-->

<!-- ! What is HTML BoilerPlate -->
<!--? HTML boilerplate refers to a basic template or starting point for writing an HTML document. It contains the essential structure and elements  to create a functional HTML page.
<!-- It contain three tag( html ,head and body )html contain (head and body tag),head contain(meta and tittle tag), body contain(all content of web page)
? <!DOCTYPE html>: Defines the document as an HTML5 document.
     1. html lang="en">:  The root element of the page, with language attribute specifying the language.
     2. meta charset="UTF-8": Sets the character encoding to UTF-8 (which supports most characters).
     3. meta name="viewport" content="width=device-width, initial-scale=1.0">: Ensures that the page is responsive on different devices by setting the viewport width to the device's  width.
     4. meta http-equiv="X-UA-Compatible" content="IE=edge" : Ensures compatibility with Internet Explorer's latest rendering engine.
     5. title : Sets the title of the page, displayed in the browser tab. 
-->
<!-- ! What are the various markup languages available? -->
<!--?HTML: Hypertext Markup Language
KML: Key whole Markup Language
MathML: Mathematical Markup Language
SGML: Standard Generalized Markup Language
XHTML: eXtensible Hypertext Markup Language
XML: eXtensible Markup Language 
 -->

<!--! What are HTML elements and tags? -->
<!--? HTML Tags:
Tags are the building blocks of HTML.
They are used to define how content should be structured or displayed on a web page.
Tags are enclosed within angle brackets (< and >).
Most tags come in pairs: an opening tag (<p>) and a closing tag (</p>). 
Some tags, such as <img> and <br>, are self-closing.
<!--? there are to type of tags in html 
    1. pair/ container tag:
    2. unpair/ non-container tag:
-->
<!--? HTML Elements:
An element refers to the entire structure that includes the opening tag, content (if any), and the closing tag.
An element represents the content and the behavior or structure it defines.

                <p>This is a paragraph.</p>
<!-- ?In this case, the entire <p>...</p> structure, along with the text inside it, is considered an HTML element.
 -->

 <!--! What are the various heading tags and their importance? 
<!--? There are 6 levels of headings defined by HTML. These six heading elements are H1, H2, H3, H4, H5, and H6; with H1 being at the highest level and H6 at the least. 

Importance of Heading:

<!--? 1. Search Engines use headings for indexing the structure and content of the webpage.
<!--? 2. Headings are used for highlighting important topics. 
<!--? 3. They provide valuable information and tell us about the structure of the document. 

--> 
<!--! How to redirect to a particular section of a page using HTML? -->
<!--? One can use the anchor tag to redirect to a particular section on the same page. You need to add “id attribute” to the section that you want to show and use the same id in href attribute with “#” in the anchor tag. 
                <a href="#home_section">home</a>

                    <section id="home_section">
                        Information About Page
                    </section>
-->