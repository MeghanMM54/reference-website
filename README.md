# reference-website

1. Naming convention for all filenames, paths and folders example:

Naming conventions for all filenames should be lowercase with no spaces, dashes instead. The folder naming convention should be similar. For paths: folders, assets, and files should be inside the root folders so they can be easily linked inside any html files.

2. Best practices for commit messages

The best practices for commit messages is to use at least three words, starting with a verb in the imperative. Use proper spelling and grammar, but no final period. It is helpful to imagine the sentence starting with "this commit will..."

3. What is HTML?

HTML is short for "hypertext markup language", and is a collection of tags used to format and describe the content on websites.

4. Proper syntax for HTML tags

HTML uses angle brackets to indicate marked-up text. To start an element, an open tag is used, written as the tag name surrounded by two angle brackets, such as: <p>. The close tag is similar, but has a forward slash before the tag name, such as </p>. The open and close tag as well as any text between them (called the element content), is colectively called an element.

5. Explain or demonstrate commonly used html tags/elements:

headings: h1-h6
   <h1></h1> through <h6><h6> are used as elements that indicate the text headings (basically mini titles). By default, they make their element content bigger. h1 is the largest and can only be used once in the document, and h2 thru h6 become progressively smaller and can be used multiple times.

p
   <p></p> is the tag used to define a paragraph. It is block-level element (as opposed to inline) and always begins a new line with automatically applied margins.

lists: ul, ol, dl
   <ul></ul> is the tag for unordered lists (bullets), <ol></ol> is the tag for ordered lists (numbered), and <dl></dl> is the tag for decription lists. Inside ul and ol tags is <li></li> (list item), and inside the dl tag is <dt></dt> (term/name) and <dd></dd> (description of term). Description lists can only contain one <dt>, but multiple <dd>.

a
   The <a></a> tags are used to indicate a link, and apply the link style to the element content. Most often used with the attribute href="", written in the opening tag as <a href="">. Inside the quotation marks, is the link adress; this is where clicking on the link will take you.

img
   To add an image to a webpage, <img src="" alt=""> is used. This element has no closing tag. In the quotations after the attribute scr, is the link to the image location; in those after alt, is the alternative content (text) that will be used for screenreaders or if the image fails to display.

figure (img & figcaption)
   The <figure></figure> element can be used to turn an image or other type of content into a self-contained figure. A caption can be used by inserting the <figcaption></figcaption> elememt as a child of (inside of) this element.

q
   <q></q> is used to mark a quote imbedded in another element, for example:

   <p>Paragraph<q>famous quote</q>more paragraph</p>

blockquote
   The <blockquote></blockquote> element is used to mark a stand alone quote, not imbedded in another element.

cite
   The element <cite></cite>, can be used to mark up the source of the quote. For example, the title of the book or person who said it. The atrribute of the same name is for citing a source link, and can be applied to <q> and <blockquote> as <q cite=""> and <blockquote cite="">.

em
   This element adds emphasis.

strong
   This element adds a heavy emphasis, indicates the content's importance or urgency.

b
   The <b></b> element indicates a keyword.

i
   <i></i> is used to format a title, technical term, or another language. 

small
   This element makes text smaller than the default size.


6. Explain block Elements and also explain the list of block elements and why they are used from below:

html
   Block element in HTML are elements that take up an entire line, or block, and aren't placed inline beside other elements (unless configured in a CSS stylesheet).

head
   The head element contains meta information, the title, and links. It is not displayed on the webpage.

body
   The body element contains all the content on the website. Is is used below the head.

header
   The header holds the introductory content, and can be placed at the top of the page inside body, or inside another element such as section.

nav
   The nav, or navigation, is a section element that holds and defines a set of links that users can use to navigate the document and get to other documents.

main
   This element appears once per page, and indicates the main content. It can only be used once per page.

section
   The section element contains a related set of content. Each section usually has its own heading.

article
   An article is a self contained composition on a page, and is meant to be distributed independently or reuseable. It could be a social media post, interactive widget, product card, etc.

div
   <div></div> is a generic block element that groups elements together.

aside
   Often diplayed as a sidebar on websites, the aside element is used to display unrealated or indirectely related content to the main content, such as advertisements.

footer
   The footer, found inside the body, is used to end a webpage. It is often reused on many pages of a website, and may conatin links, copyright info, terms or service, and company information.

span
   <span></span> is generic inline element used often to markup a part of text without seperating it.

small
   The small tag is an inline markup element, which slightly shrinks content. It is often used te denote copyright.

7. Explain why accessibility is important and also explain the accessibility properties like:

Accessibility helps to make websites more usable for people with disabilities, and in the case of aria labels and alt texts for images, if the intended element fails to load. Landmark roles help to define specific sections on a site, such as banner and main, and help people using screenreaders to more easily navigate a page. Aria labels are used to provide descriptions that can be read by screen readers. Finally, alt texts for images are used to describe photos for those who cannot see them, or to decribe the photo if does not load properly.
   
8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)

CSS is a way to format HTML code, and can be implemented by adding this line into the head of the HTML document, usually before the title.
<link rel="stylesheet" href="style.css">

9. What is the difference between CSS ruleset, property and value (write explanation and an example code)

A piece of CSS code is a ruleset, and is comprised of a selector (calls upon a piece of html code), and the declaration (the property and its value.)
A property goes bellow and is an asset of a selector. A value is what comes after the property. In this example, 
   h2 {
      background-color: blue
      }
'h2' is the selector, 'background-color' is the property, and 'blue' is the value.

10. Why do we use border-box property in CSS?

We use border-box because it helps make content more easily scaleable, and is very useful in responsive design.

11. Explain different type of ways we can add spacing to an element

One way to add spacing to an element is padding, which adds space around the outside. Another way is to use border, which frames the element. Margin can also be used, and is a transparent layer on the outside of elements.

12. What is the main difference between margin and padding?

Padding is inside the element, and is usually visible, while margin is outside and pushes other elements futher away while being invisible.

13. What are different types of display properties?

There are four types of display property: block, inline, inline-block, and none. Each determines how the element interacts with others beside it.

14. Write a brief explanation of flexbox property

Flexbox prperty controls how elements sit on a page, and is used for a one-dimentional layout system. Applying it creates a flex-container that affects the element it is applied to and its children. Using this property, elements (items) can have their orders changed, be moved to different areas of the box, and appear in collumns or rows.

15. What are different types of flexbox properties and what is the major difference between them?

The flex-box properties are flex-direction (changes row to column), wrap (lets items more to other lines) and no-wrap (forces items onto one line). They change how items appear in a flex-box, but flex-direction changes the direction and orientation, while wrap & no-wrap change the wrapping style.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property



17. Write a code example on how you will use a flexbox property on a parent element with sub properties.

