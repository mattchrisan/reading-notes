# What is Javascript?

JavaScript is a programming language that allows you to implement complex things on web pages. Every time a web page does more than just sit there and display static information for you to look at—displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, or more—you can bet that JavaScript is probably involved.  

The core client-side JavaScript language consists of some common programming features that allow you to do things like:
Store useful values inside variables. In the above example for instance, we ask for a new name to be entered then store that name in a variable called name.
Operations on pieces of text (known as "strings" in programming). In the above example we take the string "Player 1: " and join it to the name variable to create the complete text label, e.g. ''Player 1: Chris".
Running code in response to certain events occurring on a web page. We used a click event in our example above to detect when the button is clicked and then run the code that updates the text label.
And much more!

What is even more exciting however is the functionality built on top of the client-side JavaScript language. So-called Application Programming Interfaces (APIs) provide you with extra superpowers to use in your JavaScript code.

APIs are ready-made sets of code building blocks that allow a developer to implement programs that would otherwise be hard or impossible to implement. They do the same thing for programming that ready-made furniture kits do for home building — it is much easier to take ready-cut panels and screw them together to make a bookshelf than it is to work out the design yourself, go and find the correct wood, cut all the panels to the right size and shape, find the correct-sized screws, and then put them together to make a bookshelf.

# The 2 main categories are Browser APIs amd Third party APIs.
Browser APIs are built into your web browser, and are able to expose data from the surrounding computer environment, or do useful complex things. For example:

# The DOM 
(Document Object Model) API allows you to manipulate HTML and CSS, creating, removing and changing HTML, dynamically applying new styles to your page, etc. Every time you see a popup window appear on a page, or some new content displayed (as we saw above in our simple demo) for example, that's the DOM in action.
The Geolocation API retrieves geographical information. This is how Google Maps is able to find your location and plot it on a map.
The Canvas and WebGL APIs allow you to create animated 2D and 3D graphics. People are doing some amazing things using these web technologies —see Chrome Experiments and webglsamples.
Audio and Video APIs like HTMLMediaElement and WebRTC allow you to do really interesting things with multimedia, such as play audio and video right in a web page, or grab video from your web camera and display it on someone else's computer (try our simple Snapshot demo to get the idea).
Third party APIs are not built into the browser by default, and you generally have to grab their code and information from somewhere on the Web. For example:

The Twitter API allows you to do things like displaying your latest tweets on your website.
The Google Maps API and OpenStreetMap API allows you to embed custom maps into your website, and other such functionality.

# Embed or include
You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file. In most cases the latter is recommended, but for our first examples, in order to make the whole thing work in a single file, we'll embed the JavaScript code inside some HTML.

In order to do that we add the <script> opening and </script> closing tags. Between the two we write our JavaScript code.
Input Output - The most simple one is by using the alert function: 
alert- This will show a pop-up in the browser with the text.


