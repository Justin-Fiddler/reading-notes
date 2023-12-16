# Dynamic web pages with JavaScript

## Notes

## What is JavaScript?

JavaScript adds an *interactive* element to websites. 

> Known as the scripting language for Web pages.[^1]

>Do not confuse JavaScript with the Java programming language — JavaScript is not "Interpreted Java". Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantics, and use. [^1]

JavaScript documentation of core language features:

- [The JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [The JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

>We can distinguish 3 major parts of what we usually refer to as "JavaScript".
>
>1. **The language itself.** This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.
>2. **The DOM API** - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.
>3. **The server API** *(or just API)* provided by Node.js or one of the other server-side systems. [^2]

When applying JavaScript to HTML, it preferred to **include** an external file within the HTML similar to CSS. Another option is to **embed** JavaScript directly in a line in the HTML.

 - A simple example of embedded JavaScript is the **alert** function. This creates a pop-up in the browser with the text.

    > -  examples/js/alert.html
    >
    >`<script language="javascript">
    >alert("Hello World");
    ></script>` [^2]

## Ways to Use Javascript

- **Embed**
    - Similar to inline CSS
    - `<script>code</script>`
    - A simple example of JavaScript is the **alert** function. This creates a pop-up in the browser with the text.

    > -  examples/js/alert.html
    >
    >`<script language="javascript">
    >alert("Hello World");
    ></script>` [^2]

- **Include**
    - An external `app.js` file that should be linked in the `<head>` section with a `<script>` tag using the `app.js` attribute.
    - Example: `<script src="app.js></script>`

### **Variables (this week)**
- **let** (*can* change)
    - `declaration: let myAge = '38'`
    - `declaration:     myAge = '39'`
- **const** (will *never* change)
    - Declaration: `const myName = 'Justin'`



### **Data Types (this week)**
- Strings: text with single (') before and after
- Numbers: any number but without quotes
- Boolean: true for false

### ***~Note!~***
- to 'comment out' on javascript, use // to start your notes

## Conditions

### **if, else, and else if**

- **if Example:** 
    - `const usersName = prompt("What is your name?");`
    - `if (usersName =="Jay"){`
    `alert("Hiya Teach");`
}
- **else**
    - `else {alert("Glad to have you here");}`
- **else if**
    - `const usersName = prompt("What is your name?");`
    - `if (usersName =="Jay"){alert("Hiya Teach");}else if (unserName == "Joe"){alert("Yo Joe!!!");}else {alert("Glad to have you here!);}`

## References

1. [*"JavaScript"*](https://developer.mozilla.org/en-US/docs/Web/JavaScript) developer.mozilla.org

2. [*"Introduction to JavaScript - basic output"*](https://code-maven.com/introduction-to-javascript) code-maven.com

3. [*"JavaScript input with prompt and confirm"*](https://code-maven.com/javascript-input-with-prompt-and-confirm) code-maven.com

4. [*"JavaScript Variables"*](https://www.w3schools.com/js/js_variables.asp) w3schools.com

### Additional References

1. [*"How Computers Work"*](https://youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-&si=1xUR4IBN3ISb5MJX) code.org

## Answers

1. a container for storing information
2. creates a container or "variable" to store information
3. the (=) is an assignment operator. It assigns the value to the variable.
4. User input