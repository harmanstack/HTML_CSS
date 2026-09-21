# Div
- used as a container for other elements.
- by default a block level element.
- no req attribute but class, id and style are comman.
- often used to group section of a  web page.

```html
Lorem Ipsum <div>I am a div</div> dolor sit amet.

<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 9 million inhabitants.</p>
</div>

```

#### span
- Inline container used to markup a part of text or doc.
- no req attribure but class, id, style are comman.
can be used to stype a part of text.

```html

<p>My mother has <span style="color:blue;font-weight:bold;">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold;">dark green</span> eyes.</p>

```

## float
- positionsing and formatting content and allows elements to be horizontal, rather than vertically.

## inline-block
- will no longer add a line break, display side by side.
```css
<style>
div {
  width: 30%;
  display: inline-block;
}
</style>
```

## flex
- Flexbox layout module used to design flexible responsive layout structure without using float or positioning.
- Put all the <div> elements inside one main <div>, and give the main <div> display: flex. This will make the inner <div> elements arrange themselves using Flexbox.

```html
<div class="container">

    <div>Box 1</div>
    <div>Box 2</div>
    <div>Box 3</div>

</div>
```

```css
.container {
    display: flex;
}
```

> **Note:** <mark>grid is pending after complete html then we moves towards grid.</mark>