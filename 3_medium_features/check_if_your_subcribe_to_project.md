# Check if you are subscribed to a important projet/module


The objective of this function is to check if you are subscribed to a important projet/module and if you are not, display a message

For this you will use a function called [QuerrySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) and [QuerrySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll) that will allow you to select modules and projects in the page.
after that you will check how many time you have to subscribe to a important projet/module and if you don't have such a time, you will display a message using [innerHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML) or [insertAdjacentHTML](https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML) that will allow you to add html in the page

<img src="../imgs/important_module_project.png">

### Here you got list of projects and modules you just have to check if you are subscribed to them and if the project/module was "important"

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

## 👏 Congrats

You have take information from the page and display modification in the page
