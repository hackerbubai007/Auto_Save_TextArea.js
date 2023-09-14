# Auto_Save_TextArea.js
###  JavaScript

Create a JavaScript file and include the following code:

```
const textarea = document.getElementById("myTextarea");

function saveToLocalStorage() {
    localStorage.setItem("savedText", textarea.value);
}

if (localStorage.getItem("savedText")) {
    textarea.value = localStorage.getItem("savedText");
}
textarea.addEventListener("input", saveToLocalStorage);

```

###
Explanation

The HTML code creates a textarea element with an ID of "myTextarea". The CSS code styles the textarea element. The JavaScript code adds an event listener to the textarea element that saves the textarea's value to local storage every time the user types something. The JavaScript code also loads the saved value from local storage and sets the textarea's value to the saved value when the page loads.
