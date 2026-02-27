An example of a codeblock for an After Effects expression:

```jsx title="example" linenums="1" hl_lines="3-5"
dropdown = effect("Dropdown Menu Control")("Menu").value;
dropDownItems = {
    1: "First String",
    2: "Second String",
    3: "Third String"
};
dropDownItems[dropdown];
```