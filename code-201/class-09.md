># Read-Class 09

## HTML Forms

1. Why are forms so important in web development?

* Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

* Before starting to code, it's always better to step back and take the time to think about your form.
* Keep it simple and stay focused: ask only for the data you absolutely need.
* From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users.

3. List 5 form elements and explain their importance.

<!-- 
* <form> - When you want to collect information that visitors provide. For example, you may want to collect specific data from visitors, such as name, email address, and password.
* <label> - Provides a usability improvement for mouse users i.e, if a user clicks on the text within the <label> element, it toggles the control.
* <input> - Creates interactive controls for web-based forms in order to accept data from the user;
* <textarea> - Defines a multi-line text input control. The <textarea> element is often used in a form, to collect user inputs like comments or reviews.
* <button> - Creates the button which is used to trigger the client side script when the user clicks that button.  
-->

## Learn JS

1. How would you describe events to a non-technical friend?

* Events are things that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

* The listener listens out for the event happening, and the handler is the code that is run in response to it happening. So you need event handlers and event listners. 

3. Describe the event object. Why is the target within the event object useful?

* Event object keeps tracks of various events that occur on the page, such as the user moving the mouse or clicking on the link, and allows you (the webmaster) to react to them.
It's useful for the target to be within the event object to identify which element an event originated from.

4. What is the difference between event bubbling and event capturing?

* Event capturing means propagation of event is done from ancestor elements to child element in the DOM while event bubbling means propagation is done from child element to ancestor elements in the DOM.  They are literal opposites. 

## Thing I would like to know more about.