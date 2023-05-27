## About the project

* It is a basic Html andd Css project.

## Tools used

* HTML
* CSS

## Learning

* Variable declarations begin with two dashes (-) and are given a name and a value.
    * syntax - --variable-name: value;
* To use a variable, put the variable name in parentheses with var in front of them.
    * var(--variable-name).
* var() - This function is used to insert the value of a CSS variable.
    * syntax - var(--name, value)
    * name - The variable name (must start with two dashes).
    * value -  The fallback value (used if the variable is not found).
* :root selector - matches the document's root element.
    * syntax - :root { css declarations; }   
    * :root - variables are often declared in the :root selector. putting your variables there will make them usable everywhere.
* linear-gradient - To create a linear gradient you must define at least two color stops.You can also set a starting point and a direction (or an angle) along with the gradient effect.
    * syntax - background-image: linear-gradient(direction, color-stop1, color-stop2, ...);
* repeating-linear-gradient - This will make the four colors of your gradient repeat until it gets to the bottom of the element.
* radial-gradient - A radial gradient is defined by its center.To create a radial gradient you must also define at least two color stops.
    * syntax -background-image: radial-gradient(shape size at position, start-color, ..., last-color);
* @media rule -  A media query can be used to change styles based on certain conditions.
    * max-width: 1000px;
    * Styles added in here will take effect when the document size is 1000px wide or less.

## Production Link

https://city-skyline.vercel.app/