## DOM
- when webpage is loaded, the browser creates dom of the page
- for dynamic changes or manipulation
- dir ->document -> methods property
- log  print

WINDOW OBJECT
- represents an open window in a browser.Its browser object not js and is automatically created by browser
- its a global object with lots of properties and methods

`

console.log(window);
window.console.log("kismat");
window.alert("hi window");
console.log(window.document);
console.dir(window.document);

`
---

```

console.dir(document.body);
console.dir(document.head);
console.log(document.body);
console.dir(document.body.childNodes[1]);

console.log(document.body.style.background="green");

console.log(document.body.childNodes[3].innerText="abcd")

```
- console.dir(document.body) to get nodes


### DOM MANIPULATION

slelecting with id
```
document.getElementById("myid")

```
selecting with class
``
document.getElementsByClassName("myClass")

``

selecting with tag
`
document.getElementsByTagName("h1")

`
