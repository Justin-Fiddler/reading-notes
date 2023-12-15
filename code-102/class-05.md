# Design Web Pages with CSS

## Notes

### What is CSS

CSS or "Cascading Style Sheets" is used to manipulate HTML from it's default styling.

    - Example: 
    
    `Selector {
        property: value;
    }`

### Good Practice

- Keep HTML and CSS in seperate files.

### How to start

- In your working repository and alongside your **index.html** file, create a **syle.css** file.
- `<link>` the two files by adding `<link rel="stylesheet" href="style.css">` in the `<head>` section below the `<title>` element in the HTML file.
  - This will link the HTML and CSS files properly.

### Applying CSS

#### Selectors

- When using css, the selector identifies the location in the HTML code where the style will be applied. This allows the style to be applied specifically or broadly.
- options are a path, id, and class

    - path: `<nav> <ul> <li>`
    - Unique id: 
        - **HTML** - `img id="hero img"`
        - **CSS** - `#hero-img`
    - Class 
        - `.class-name {
            property: value;
        }`

#### Property and Value

- The property can be color, size, font, etc...
- The value is what you want to change the property to.
- Examples:
`header {
    bakground-color: red;
    font-size: 6em;
}`
- Note that the colon seperates the property and value, while the semi-colon seperates sets of properties and values
- To apply the above styles that would be written in the style.css file, insert `style="bakground-color: red; font-size: 6em;"` as an attribute to the appropriate element in the HTML. In this case, it would be inserted one space after the "header" in the opening tag.
- Example:
`<header style="background-color: red;
    font-size: 6em;>Heading Number One Text</header>`

## Answers

1. CSS is a style language used to alter or manipuate the appearance of HTML's standard structure.

2. Three Ways to Insert CSS into a project:
    1. External CSS
    - Acheived by adding a reference to a style sheet in the `<head>` section of the HTML page or pages. The style sheet must be saved in a .css extension and is housed in the working repository with the HTML file.
    2. Internal CSS
    - This refers to a style sheet being added into the HTML file instead of an external CSS file.
    3. Inline CSS 
    - Used to apply desired style to a single element.

3. `p {
    color: red;
}`
