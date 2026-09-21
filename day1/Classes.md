# Classes

- `class` attribute is used to specify a class to an HTML element.
- elements can share a same class.
- often used to point a class name in style sheet.
- can be also be used by js to access and manipulate element with specific class name.
> **Note:** class name is case sensitive.

### Systax for class

```html
<!DOCTYPE html>
<html>
<head>
<style>
.note {
  font-size: 120%;
  color: red;
}
</style>
</head>
<body>

<h1>My <span class="note">Important</span> Heading</h1>
<p>This is some <span class="note">important</span> text.</p>

</body>
</html>
```

### Mutliple classes
- element can belong to more than one class.

```html
<h2 class="city main">London</h2>
<h2 class="city">Paris</h2>
<h2 class="city">Tokyo</h2>
```

### diff elements can share the same class.
- dif elements can point to the same class name.

```html
<h2 class="city">Paris</h2>
<p class="city">Paris is the capital of France</p>

```

### use of class attribute in javaScript

- To perform certain tasks for specific element.
- JS can access element with specific class name with `getElementsByClassName()` method.

```html
<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script>
```