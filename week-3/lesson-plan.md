# Week 3 Lesson Plan CSS

Just like there are two big concepts in HTML (nesting and attributes), there are three big concepts in CSS. Once you understand these concepts, the rest is just reading documentation for the implementation details.

The concepts for CSS are:

* rules
* selectors
* precedence

We will start with rules, then selectors. And finally precedence.


1. style tags embedded in HEAD, styling by tag. color, background, padding, margin
2. external style sheets, styling by id
3. styling by class, CSS Dinner, accessing by ID in JS
4. positioning elements with absolute position
5. Building a mini web page with CSS.

Forum topic: find an interesting CSS style property and share it.
JavaScript topic: accessing elements by ID.

CSS Topics: typographic styles, box-model padding and margin, absolute positioning, CSS selectors

## Teaching plans

### Day 1

* Show color, background-color, font-family, font-size on body
* Show how to override this on tag names
* Show how to override this on id
* Show how to change the style of lists
* Review JS: setting style using id and the style attribute with camelCase.

Assignment: Create a file called typography.html. Create a file called style.css. (Include two lists.)

### Day 2

* Show how to combine tags in selectors: lists in header, lists in footer, lists in aside
* p tags in different parts of the page

### Day 3

Layouts

Show how to use the box model to...

* create a div box with width and height
* add padding and margin and border
* layout with float and clear.
  * Fluid layout lots of boxes in a row
  * Layout with static main and aside
* add background image
  * background-size: cover, contain, repeat
* Review HTML lists
* Review HTML tables?
* review tables with padding, border, margin on TD tags?

### Day 4

Show how to use relative and absolute positioning to...

* position boxes around the screen
* create a hero element

### Day 5

Create a table, compare it with a ul

Set image width and height proportionally.

or

Create a hero element

* review
* add a gradient to the background image for contrast.
* style a table

## Project

Update your last website.

Create two branches: `html` and `css`

Do your work on the `css` branch.

1. Add a style sheet to your projects.
2. Add padding or margin to your images
3. Nest your content in article tags, then add padding or margin to your article tags.
4. Work on a hero element.

### Hero element

* Create a div on the first page with id `hero`
* style the hero with a background image and height and width
* IMPORTANT: add {position: relative} to the hero.
* Add h1 or h2 children to the hero div.
* use position: absolute and the top, and left properties to set the position of the header text.
* Add a button and position it in the hero, as well.
* Style the text, and adjust the image to make the words and call to action button pop out.