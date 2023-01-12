# Setup Chrome Extension

## 🎯 Objectives

Make your chrome extension launchable

* Initialize your extension
* Add it to chrome
* Try it

## 📝 Setup manifest.json

manifest.json is the main file of your extension. It contains all the information about your extension.

```sh
mkdir EpiStats
cd EpiStats
touch manifest.json
```

Add this in manifest.json


```json
{
    "manifest_version": 3
}
```


Now we it's your time to add the rest of the information about your extension add in manifest.json:

* The [name](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/name) of the extension
* The [version](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/version) of the extension
* The [description](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/description) of the extension
* The [author](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/author) of the extension
* The [icon](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/icons) of the extension
* The [action](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/action) of the extension (the action is the page that will be opened when you click on the extension icon)
* The [content_scripts](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/content_scripts) of the extension (the content_scripts is the page that will be injected in the current page when you click on the extension icon)

## 📝 Setup action

The action is the page that will be opened when you click on the extension icon.

```sh
mkdir popup
touch popup/index.html
touch popup/index.js
touch popup/index.css
```
Link the html file into the manifest.json

## 📝 Setup content_scripts

The content_scripts is the page that will be injected in the current page when you click on the extension icon.

```sh
touch index.js
```
Link the js and the Chart.min.js file into the manifest.json

## 🏃 Try it

Now to try it you will 
go in the index.js and write

```
document.body.innertHtml = "Hello world";
```

After this you will load the extension for this

* Go in Chrome
* Click on Extentions
* Manage Extentions
* Activate Developer mode
* Load unpacked and choose your extension

After this go on this [intranet](https://intra.epitech.eu/) and 


## 👏 Congrats

If you go a blank page with write "Hello world" it's good you have setup your first extension

## Summary

What you have learned:

* Initialize a basic chrome extension
* Run a chrome extension
* Try if it works

## Additional resources

* [Manifest documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json#:~:text=Using%20manifest.,scripts%2C%20and%20browser%20actions)

## Next steps

* Now you can go to the next step doing a easy feature
