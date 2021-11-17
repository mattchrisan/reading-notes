# What is CSS?

CSS is basically how you make your webpage look pretty.  It's also how you arrange different things on the page such as your header, navbar, images, paragraphs, footer, etc.  

# How to use CSS

You want to start out by adding CSS into the head of your html to link them.  <link rel="stylesheet" href="styles.css">
Save your HTML and CSS files and reload the page in a web browser. The level one heading at the top of the document should now be red. If that happens, congratulations — you have successfully applied some CSS to an HTML document.

# Styling HTML elements

By making our heading red we have already demonstrated that we can target and style an HTML element. We do this by targeting an element selector — this is a selector that directly matches an HTML element name. To target all paragraphs in a document you would use the selector p.  You can target multiple selectors at once, by separating the selectors with a comma.

# Changing the default behavior of elements

This can be done by choosing the HTML element that you want to change, and using a CSS rule to change the way it looks.  

Ex: li {
  list-style-type: none;
}

# Adding a class

A way to select a subset of the elements without changing the others.

Ex: 
<ul>
  <li>Item one</li>
  <li class="special">Item two</li>
  <li>Item <em>three</em></li>
</ul>
In your CSS you can target the class of special by creating a selector that starts with a full stop character. Add the following to your CSS file:
Ex: 
.special {
  color: orange;
  font-weight: bold;
}






