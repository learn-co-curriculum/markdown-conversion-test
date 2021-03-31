# markdown-conversion-test

## Second Header

### Images

Remote image:

<img src="https://curriculum-content.s3.amazonaws.com/flag-icon-gray-hover.png" />

Local image:

<img src="./image.JPG" />

## Code Snippets

<h1>This should render as a big header, not </h1>

Code snippets `should` render as code, including HTML elements like `<p>`, `<body>`, `<html>`, etc..

> Block quotes should render as a group
> On multiple lines
> Here


Also, stand along less than or greater than symbols should display correct: `Class > Module`, `Module < Class`, `C -> M`

```rb
array << 'ruby shovel syntax should render correctly on this line'
```

```sh
git clone git@github.com:<this-contentt-should-appear>/<even-though-these-are-wrapped-like-html>
```

_This should be italicized_. **This should be bolded**. In a code snippet, `_this_`, `*this*`, `**this**`, and `__this__` should not be stylized. Same with the code snippet below:

```js
this.innerText = "this should render as code"

this.__proto__ //should render as two underscores before and after proto, not italicized
// also _this_ should not be italicized, either
let test = "**this too**"
```

```
This is an unlabelled code snippet
```

```html
<h1>Some HTML code</h1>
```

