
# Wireframe and Design

Wireframing is a practice which allows you to map out the design and hierarchy of a website you are designing.  You can hand draw the layout you want or use digital sketching tools.  You also want to think about the different platforms you are designing said page for such as a normal computer versus a mobile phone etc.  There are several different ways to start that look like this: Sketch > Wireframe > Visual > Code.  Another trick is to draft, don’t draw and sketch, don’t illustrate.

# Mozilla HTML Basics

HTML (Hypertext Markup Language) is the code that is used to structure a web page and its content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way.  

The main parts of an element are as follows:

1. The opening tag: This consists of the name of the element wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect.
2. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends.  
3. The content: This is the content of the element.
The element: The opening tag, the closing tag, and the content together comprise the element. 

Attributes contain extra information about the element that you don't want to appear in the actual content.
An attribute should always have the following:

1. A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
2. The attribute name followed by an equal sign.
3. The attribute value wrapped by opening and closing quotation marks.

Nesting elements
You can put elements inside other elements too — this is called nesting.

Here's what the basic structure of html looks like:

<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.
  
You can also add different things like images, web links, lists, and more.

- [<===Back](README.md)


