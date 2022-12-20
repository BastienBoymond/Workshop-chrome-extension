# Getting Started

Now that you have installed the software, you can start using it. This section will guide you through the first steps.

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

Now that you have done that you will have to add a function that warn you went your not subscribed to a important projet/module


The objective of this function is to check if you are subscribed to a important projet/module and if you are not, display a message

For this you will use a function called [QuerrySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) and [QuerrySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll) that will allow you to select modules and projects in the page.
after that you will check how many time you have to subscribe to a important projet/module and if you don't have such a time, you will display a message


(Important Projet/Module are the ones that are in your current semester)
```js
...

function getSemester(link) {
    // We get the semester of the module/project
    // We return the semester
}

function checkSubcribe() {
    // Check if the page is the main page
    // If it is not the main page, we don't do anything
    // If it is the main page, we get all the modules and projects
    // We get every link for get semester of the module/project using /// a function called getSemester
    // if the semester is the same as the current semester, we check if we are subcribed to the module/project
    // If you are not suscribed to a important projet/module, we display a message
}

checkSubcribe();
```

Now that you have append this information don't forget to add css it's important to make the page look good

## 👏 Congrats

You have done your first modification of DOM to add a new feature to intra.epitech.eu

## Summary

What you have learned:

* How to use the DOM
* How to use the console
* How to modify the DOM
* How to use QuerrySelector
* How to use QuerrySelectorAll
* How to use a function and declare in Js

## Next Part

[Add a Chart of your grades](../3_Add_a_chart_of_your_grades/README.md)

