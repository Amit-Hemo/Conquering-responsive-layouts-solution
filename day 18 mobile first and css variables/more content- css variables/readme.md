# Css Variables

## What are css variable for?

- it's saving us time to change a repeated value in the css file by only changing one line. we can put these repeated values into css variables with good naming and use that everywhere we want.

- we can consider these variables as global variables we know from coding but the value is a css value (what is after the : in every property).

## Decalring css variables

- in the top of the css file, creating all the variables inside :root , example :

```css
:root {
  --primary-clr: #456;
}
```

**note: the -- before the name is required, it let's the browser know it's a custom property and not a normal one.**

## Using the variables we created

- in the place we want, let's say the body, we add:

```css
body {
  color: var(--primary-clr);
}
```

## Overwriting variables
* when we want on special cases inside our css to change the value of the varible we can just redeclare them like we did in the root.
* it is the most useful in media queries because we just need to change the variable we want and it will change everywhere.
