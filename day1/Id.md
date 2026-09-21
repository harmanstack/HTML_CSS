# Id
- is used to specify a unique id for an Html element.
- can't have more then one element with same id in an HTML document.
- is used to point to a specific style declaration in a style sheet.
- also used by JS to access and manipulate.
- id name also case sensitive.
- must contain at least one character, can't start with number, must't contain whitespaces.

### Syntax

```html
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```

### dif b/w CLASS and ID
- class can be used by multiple elements, while an id must only be used by one element with in a page.

### HTML book marks with id and links
- to allow  readers to jump to speific parts of webpage.
- usefull if page is very long.


### use of id attribute in javaScript

- To perform certain tasks for specific element.
- JS can access element with specific class name with `getElementsById()` method.

```html
<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>
```
