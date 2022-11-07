# Introduction to CSS
`CSS` stands for Cascading Style Sheet. It is used for website layout in design and used alongside HTML. CSS is a styling language.
# Concepts
- CSS type or Methods
- CSS Selectors
- Box Model
# Types of CSS Styling
# Inline CSS
Here you add your CSS styling in the opening tag of your HTML Elements as a style attribute, the added style is arranged in the manner shown in the example below.
- e.g <h1 style="color: red;">Hello World</h1>
# Internal CSS Styling
You add your CSS using `<style>` tag within your `html` file but inside of the `head element` just right after the `title tag`, this is done in order for the browser to load all styling into memory before creating the DOM.
- e.g <style>...</style>
# External CSS Styling
An external file is used to define the styling in this method for any HTML page, 
This method of styling can be used by more than one HTML page, To use an external style sheet, add a link to it in the `<head>` section of each HTML page.
- e.g <link rel="stylesheet" href="">
# CSS Selectors
- Universal CSS Selectors: Selects every Element in the HTML file
- CSS Element Selector: Also known as a `type selector`. This selector tries to match the HTML elements having the same name.
- CSS ID Selector: Helps the developer to match the ID created by the developer to its styling content.
- CSS Class Selector: Is one of the most helpful selectors of all the selectors.
- CSS Class Attribute Selector: Styles content according to the attribute and the attribute value mentioned in the square brackets.
# CSS syntax
Declaration Block: Can contai one or more declarations seperated by a semicolon.
- color: blue;
- text-align: justify;
Each declaration contains a property name and avalue, separated by a colon
- Property: A Property is a type of attribute of an HTML element. It could be color, border etc.
- Value: Values are assigned to CSS properties. In the above example, the value "blue" is assigned to the color property.

