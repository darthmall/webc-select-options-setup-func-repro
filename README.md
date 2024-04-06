# WebC &lt;select&gt; Options Setup Function Repro

Attempting to reproduce an issue using a function in `webc:setup` to generate an array used as options for a `<select>` element.

## Running

```
$ npm install
$ npx @11ty/eleventy
```

Contents of `_site/index.html` should look like

```html
<!-- Top level component -->

<select name="motivation">
    <option value>Please select</option>
    <option value="1">1</option>
    <option value="2">2</option>
    <option value="3">3</option>
    <option value="4">4</option>
</select>
```
