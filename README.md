##
# Exercise 2: JS + CSS Clock
Clock made with vanilla JavaScript

Judith Ricketts, Artist, Lecturer and Software engineer - [Contact](https://lovespictures.com/)  
Commit Date: 26th October 2021

## Guide

The HTML file has 3 `div` elements which correspond with the second, minute, and
    hour hand on a clock

```html
<!-- ...previous elements -->
    <div class="hand hour-hand"></div>
    <div class="hand min-hand"></div>
    <div class="hand second-hand"></div>
<!-- next elements... -->
```

The necessary JavaScript code shouldn't be too crazy;
    we'll create references to these elements and dynamically
    update certain CSS properties to change their positions so they reflect the
    current time. Easy peasy.

<!-- 

guide  https://github.com/nitishdayal/JavaScript30

**Steps:**

- **CSS**:

    1. The hands are all laying flat; we need them to be vertical. Rotate all of the
        hands by 90 degrees so that they are upright by giving the `.hand` class a
        `transform` rule with the value `rotate(90deg)`.


- **JavaScript**:

    1. Declare & define variables for each clock hand and reference the corresponding _HTML
        element_.
 



-->
