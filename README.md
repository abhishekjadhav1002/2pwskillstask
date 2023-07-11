In this example, we start by creating an input box (<input>) and a submit button (<button>). When the user types something into the input box and clicks the submit button, the addItem() JavaScript function is called.

Inside the addItem() function, we first obtain references to the input box and the list (<ul>) element where the entered text will be added. We create a new list item (<li>) element, set its text content to the value entered in the input box, and append it to the list element using appendChild(). Finally, we clear the input box by setting its value to an empty string.

You can save this code in an HTML file and open it in a web browser. Then, whenever you enter text in the input box and click submit, the entered text will be added as a new item in the list below the input box.
