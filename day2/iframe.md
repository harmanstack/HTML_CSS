# iframe
- is used to display a webpage within a webpage.
- `<iframe>`
- inline frame is used to embed another doc with in current doc.

```html
<iframe src="url" title="description"></iframe>
```
> **Note:** always inculde title attribute .This is used by screen readers to read out what the content of the iframe is.

### Height and width
- attribute to specify the size of the iframe.
- by default in pixels

```html
<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
```
- we can also use style attribute and use css height and width properties.

```html
<iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"></iframe>
```

### Border 
- by default, it has a border around it.
- we can also change style of border.

```html
<iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"></iframe>

<iframe src="demo_iframe.htm" style="border:2px solid red;" title="Iframe Example"></iframe>
```

### i as frame- Target for a link
- can be used as the target frame for a link.
- `target attribute of a link must refer to the name attribute of the iframe.

> **Note:** <mark>iframe as target is pending</mark>