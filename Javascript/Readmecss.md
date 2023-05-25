animation property we can apply this for images, texts, svg 

animation: animation-name speed iteration-count direction;

animation-name: It represents the name of an animation (built-in or custom (using keyframes)).

speed: It is used to slow down and speed up the animation. For example, “2s” (for two seconds).

iteration-count: It denotes how many times you want your animation to continue.

direction: It specifies how an animation will play, such as forward, backward, or alternately.


What is hover effect

:hover {
  /* ... */
}


javascript

allows you to do interactivity with user events
<script> - should be inside header tag
Browser-based Client-Side (user computer) programming language of the web
JavaScript is a dynamic computer programming language
It is an interpreted (translated) programming language with object-oriented capabilities
JavaScript is officially maintained by ECMA (European Computer Manufacturers Association) as ECMAScript
JavaScript Translator  embedded in browser engine
JavaScript Translator is responsible for translating the JavaScript code for the web browser.


A high-level programming language that is interpreted by another program at runtime rather than compiled by the computer's processor
The simple difference between scripting language and programming language is: Scripting languages do not require the compilation step and are rather interpreted
C program needs to be compiled before running whereas normally, a scripting language like JavaScript or PHP need not be compiled

What is a script?
A script is nothing but sets of instructions
Series of commands

What can you do with JavaScript?
Full-fledged Enterprise Web Application
Full-blown Mobile Apps
Real-time Networking Apps (Chats, Audio/Video Streaming Services)
Games

JavaScript is used in billions of Web pages/web apps to add interactivity, validate forms and much more:
JavaScript gives HTML designers a programming tool
JavaScript can react to events(mouse click, hover (rollover, rollout), focus, blur)
JavaScript can be used to validate data (Client-side validation)
JavaScript can manipulate HTML content and CSS styles
Dynamic drop-down menus, HTML contents at run time/on the fly
Displaying live/current/dynamic date and time (clocks)
Displaying pop-up windows and dialog boxes (an alert, confirm and prompt dialog box)
Change the website's behavior and make it more dynamic with advanced web designs
Perform and control transitions and animations

Browser Detection - Detecting the browser used by a visitor
Cookies - Storing information on the visitor's computer
Control Browsers - Opening pages in customized windows
Validate Forms - Validating inputs to fields before submitting a form


JavaScript in HTML
The HTML <script>.....</script> tag is used to embed/insert/implement a JavaScript programs/code into any part of an HTML document/page
The <script>.....</script> element can be placed in the <head> or <body> section of an HTML document

So the best practice is to place/add the <script>.....</script> at the bottom/end of body tag/section ie. just before the closing </body> tag

Inside the HEAD section
Inside the BODY section
External JavaScript .js file (separation of concern)

function : basic building block of JavaScript.Function allow us to encapsulate a block of code and reuse it multiple times.

function <function-name>(arg1, arg2, arg3,...   )
{
    //write function code here
};

function greet() {
    alert("Hello World!");
}

creating variable in javascript
var x=1;

onsubmit
The onsubmit event is an event that occurs when you try to submit a form

getElementById 
The getElementById() method of the Document interface returns an Element object representing the element whose id property matches the specified string. Since element IDs are required to be unique if specified, they're a useful way to get access to a specific element quickly.





















