## Add a Button

Now we will add a button in the page that will allow us too go directly get the Norm documentation.

For this you will create a function in index.js that will be called when the page is loaded.

for this you will use a function called [QuerrySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) that will allow you to select an element in the page.

```js

url = document.location.toString();

function addNormButton() {
    // Check if the page is the main page
    // If it is not the main page, we don't do anything
    // If it is the main page, we add a button somewhere in the page (recommend: in the div with the  id "sidebar")
}
```

this function will create a button with method [createElement](https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement) and add it to the page with [appendChild](https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild)

Redirection to the norm page will be done with [window.location.href](https://developer.mozilla.org/en-US/docs/Web/API/Window/location)

url = https://intra.epitech.eu/file/Public/technical-documentations/C/epitech_c_coding_style.pdf 

```js
button = document.createElement("button");
button.innerHTML = "Coding Style";
button.onclick = function() {
    // When the button is clicked, we go to the norm page using window.location.href 
}
```