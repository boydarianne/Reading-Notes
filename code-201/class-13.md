<strong><u>Local Storage and How To Use It On Websites</u><strong>

1. Why would a developer use local storage for a web application?
(https://blog.logrocket.com/localstorage-javascript-complete-guide/#:~:text=localStorage%20is%20a%20property%20that,browser%20or%20restarts%20the%20computer.)

localStorage is a property that allows JavaScript sites and apps to save key-value pairs in a web browser with no expiration date. This means the data stored persists even after the user closes the browser or restarts the computer.

2. What information should not be stored in local storage?
(https://www.horangi.com/blog/misuse-of-local-storage#:~:text=Given%20the%20potential%20vectors%20where,stored%20in%20the%20local%20storage.)

Personally Identifiable Information (PII), authentication tokens, user locations and API keys, etc

3. Local storage can store what type of data? How would you convert it to that type before storing?
(https://www.freecodecamp.org/news/how-web-storage-works/#:~:text=Any%20item%20that%20you%20store,otherwise%20you%20lose%20their%20structure.&text=In%20the%20example%20above%2C%20we,into%20a%20string%20using%20JSON.)

Any item that you store in localStorage will be stored as a string. This means that you need to convert other data types such as arrays or objects to strings

Convert the array into a string using JSON. stringify() method.