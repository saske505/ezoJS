#Introduction
![](http://i.imgur.com/keu4q1C.png)
# What is ezoJS?
ezoJS is a JavaScript framework that build websites in a single JS file, which means that you no longer need to include, css or html files. The only thing needed is a default empty html template **(index.html)** and a **script.js** file.
*Note:  an ezo.js or ezo.min.js file must be along the scripts*

##How it works
ezo is mainly an element selector that selects elements by ID using `e$` or `ezo` variable. ezo also contains other variables listed in the API that helps you to build websites faster and easier with ezoJS. ezoJS comes with models that helps in  ezoJS development.

## Example
This is an example of how a ezoJS script look like:
```javascript
e$("doc").addHeading("1","title");
e$("title").setText("EzoJS Demo");
```
