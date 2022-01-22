# HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing. <br>

## The `<form>` Element
The HTML `<form>` element is used to create an HTML form for user input. <br>
The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc. <br>

## The `<label>` Element
The `<label>` tag defines a label for many form elements. <br>
The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element. <br>
The `<label>` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox. <br>

**NOTE: The `for` attribute of the `<label>` tag should be equal to the `id` attribute of the `<input>` element to bind them together.** 
<br>

## The `<input>` Element
The HTML `<input>` element is the most used form element.

An `<input>` element can be displayed in many ways, depending on the type attribute. <br> <br>
**Here are some Examples:**
| Type	| Description |
| ----- | ----------- |
|`<input type="text">` |	Displays a single-line text input field |
| `<input type="radio">` |	Displays a radio button (for selecting one of many choices) |
| `<input type="checkbox">` |	Displays a checkbox (for selecting zero or more of many choices) |
| `<input type="submit">` | Displays a submit button (for submitting the form) |
  
## The Name Attribute for `<input>`
Notice that each input field must have a `name` attribute to be submitted. <br>
If the name attribute is omitted, the value of the input field will not be sent at all.
  
## Example
  
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html Forms</title>
</head>
<body>
    <h1>HTML FORMS</h1>
    <form>
        <label for="username">Username : </label>
        <input type="text" id="username" name="username"> <br> <br>

        <label for="password">Password : </label>
        <input type="password" id="password" name="password"> <br> <br>

        <label for="email">Email : </label>
        <input type="email" id="email" name="email"> <br> <br>

        <input type="submit" value="Submit">

    </form>
</body>
</html>
```

## Output
This is how the above HTML code will be displayed in a browser: <br>
![HTML_Form](https://github.com/Anujakumari/HTML_and_CSS/blob/master/img/HTML_Form.png)

