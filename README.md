# CSS Architecture Starter

Use this small page for Module 2 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample content with repeated patterns.
- `styles.css`: CSS scaffold with layer sections and starter comments.

## Practice goal

Build a maintainable CSS system:

- layer order
- custom properties
- base styles
- layout/composition
- components
- utilities
- states
- print styles

Keep notes about what changed and why.

Closing Notes: 

The layer order that was determined for the CSS was reset, base, layout, components, utilities, and overrides. Some of the token decisions that I made to this site were creating custom properties for color, typography, spacing, shape, and focus. After organizing this code, the one place that it actually was easier to maintain was the components section, as it prevented having to code for each individual item (For button, as an example, I did not have to code for each button because I created the .button class)

AI Disclosure

    AI was used in this practice, but I also typed some code by hand since the AI messed up on parts like the layout and the forms (some examples being that I had to recenter the form at the bottom and also I had to fix the site header as it was still showing up vertically like the initial CSS that came with the assignment.
