# button
- lets user interact with a web.
- can submit froms.
- run JS.
- trigger dif action.

### Syntax
- `<button>` element define a clickable button.
- by itself, button nothing untill u add an action to it.

```html
<button>click on me</button>
```

### style button
```html
<button class="mytestbtn">Green Button</button>
```
### Disabled a button
- `disabled attribute to make a button unclickable.
- > **Note:** can't be clicked and usually appear faded.

```html
<button disabled>Disabled Button</button>
```

### how to java

```html
<button onclick="alert('Hello!')">Click Me</button>
```

## Types of button
- type attribute define what a button does when clicked.

**types**
1. `button` -> noramal clickable button <mark>by default</mark>
2. `submit` -> Submit a form.
3. `reset` -> resets all form fields.

```html
<button type="button">Normal Button</button>
<button type="submit">Submit</button>
<button type="reset">Reset</button>
```

> **Note:** often use inside the forms

```html
<form action="/action_page.php">
  First name: <input type="text" name="fname">
  <button type="submit">Submit</button>
  <button type="reset">Reset Form</button>
</form>
```

**Note:** yoy should always specify the type.  

**Note:** browsers may behave differently if the type is omitted