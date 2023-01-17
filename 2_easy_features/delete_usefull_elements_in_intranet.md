## First Modification

The first thing you will do is to modify the main page of intra.epitech.eu. 

<img src="https://imgur.com/Q6mCIng.png">

On the main page you always have a susie Section that was not used by Epitech. We deleted it and replaced it with a another section

for doing this you will create a function in index.js that will be called when the page is loaded.

for this you will use a function called [QuerrySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) that will allow you to select an element in the page.


```js
url = document.location.toString();

function deleteSusieSection() {
    // Check if the page is the main page
    // If it is not the main page, we don't do anything
    // If it is the main page, we delete the susie section
}

deleteSusieSection();
```

## 👏 Congrats

You have done your first modification of DOM 

