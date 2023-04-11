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
   landmark roles
   aria labels
   image alternative texts

   
8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
9. What is the difference between CSS ruleset, property and value (write explanation and an example code)
10. Why do we use border-box property in CSS?
11. Explain different type of ways we can add spacing to an element
12. What is the main difference between margin and padding?
13. What are different types of display properties?
14. Write a brief explanation of flexbox property
15. What are different types of flexbox properties and what is the major difference between them?
16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
