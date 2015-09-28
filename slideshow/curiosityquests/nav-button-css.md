## Navigation Button Styles

We can make our links look really funky by giving them the appearance of solid buttons rather than plain links.

    .main-navigation a {
        background-color: #00FF00;
        border-color: #00DD00;
        font-weight: bold;
        display: inline-block;
        padding: 5px 10px;
    }

    .main-navigation a:hover {
        background-color: #00DD00;
        color: #FFFFFF;
    }

Note:

The CSS rule we created in the first block of code says "apply these styles to all `a` elements inside a `.main-navigation` element."

By doing this, we are targeting only the links inside the nav, rather than targeting all the links on the page.

Links also have some special extra options, which apply to their different states. These are called "pseudo-elements" and their names are `link`, `visited`, `hover`, and `active`.

We've only added styles for the `hover` state, but you can have a play with the others too.