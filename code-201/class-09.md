
<u>HTML Forms:</u>

1. Why are forms so important in web development?
It is said to be one of the main point of interaction between the user and the web app. It allows for users to enter data that can then be sent for processing or update an interface.
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
You only want to ask for information that you actually need to avoid running off users with too many task and unnecessary information.
3. List 5 form elements and explain their importance.
form, label, input, textarea,and button
form- an element that contains forms and defines a form in an HTML document.
label- defines the  key of the form for example if we want to prompt the user to enter their name then the label "name" will do that.
input- a single line text field that can take information such as a name or strcitly email addresses.
textarea- is a multi line text field.

<u>Learn JS</u>

1. How would you describe events to a non-technical friend?
Events are signals that are produced when a user does something within a website. One example would be when the user clicks a link within the website, this would be considered an event.
2. When using the addEventListener() method, what 2 arguments will you need to provide?
The string "click" to listen to the click event and a function to call when the click or event happens.
3. Describe the event object. Why is the target within the event object useful?
Event object is seen within a parameter and "it is automatically passed to event handlers to provide extra features and information." (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_objects)
The target property of the event object is always a reference to the element the event occurred upon. Example would be trying to set the background color on a button but not the entire page.
4. What is the difference between event bubbling and event capturing?
Event capturing means propagation of event is done from ancestor elements to child element in the DOM while event bubbling means propagation is done from child element to ancestor elements in the DOM. (https://www.geeksforgeeks.org/what-is-event-bubbling-and-event-capturing-in-javascript/#:~:text=Event%20capturing%20means%20propagation%20of,occurs%20followed%20by%20event%20bubbling.)