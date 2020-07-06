# Just-Hamburger-Menu
This snippet will create a hamburger menu under an invisible checkbox input.
Once clicked the hamburger will change to a closed icon X with a transition
effect.  Clicking the closed icon will transition it back to the hamburger menu icon.

Notes: css variables have been used to make customizing easier.  The are found
in the :root element.  (The distance between the hamburger icon lines need
to be entered as bot a positive number and the cooresponding negative number).

To add to your project:
1. Add the snippet of html between the <nav> tags to your own html file.
2. Check for duplicate class and id names.
    This css snippet uses:
        id:
            icon-area-anchor
        classes:
            checkbox
            hamburger-icon-area
            hamburger-icon
3. Check css properties this snippet expects in body element.
    :root { variable names to choose icon size }
    body {margin: 0, padding:0; box-sizing: border-box}
4. The css variables used here should be added to your :root element.
5. The rest of the css rules should be added to your own css.

