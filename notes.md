# Advanced CSS and Sass: Flexbox, Grid, Animations and More!

The most advanced and modern CSS course on the internet: master flexbox, CSS Grid, responsive design, and so much more.

## How CSS Actually Works?

### The Three Pillars

The three pillars to writing great HTML and CSS, as well as building great websites:

- Responsive web design
- Maintainable and scalable code
- Web performance

#### Responsive Web Design

- Fluid layouts
- Responsive images
- Correct units
- Desktop-first vs mobile-first

#### Maintainable and Scalable Code

- Clean code
- Easy-to-understand
- Growth
- Reusable
- CSS architecture
- How to organize files
- How to name classes
- How to structure HTML

#### Web Performance

- Less HTTP requests
- Less code
- Compress code
- Use a CSS preprocessor
- Less images
- Compress images

### What Happens to CSS When We Load Up a Webpage

1. Load HTML
2. Parses HTML
3. Browser builds the Document Object Model (DOM)
4. Loads CSS
5. Parses CSS\*
6. Browser builds CSS Object Model (CSSOM)
7. Rendered tree built
8. Website rendered using the visual formatting model
9. Final rendered website

### How CSS is Parsed?

#### The Cascade (The "C" in CSS)

- The process of combining different stylesheets and resolving conflicts between different CSS rules and declarations, when more than one rule applies to a certain element.

#### Importance

1. User !important declarations
2. Author !important declarations
3. Author declarations
4. User declarations
5. Default browser declarations

#### Specificity

1. Inline styles
2. ID's
3. Classes, pseudo-classes, attribute
4. Elements, pseudo-elements

#### Source Order

1. The last declaration in the code will override all other declarations and will be applied.

#### Overview

- CSS declaration marked with !important have the highest priority
- But, only use !important as a last resource. It's better to use correct specificities - more maintainable code!
- Inline styles will always have priority over styles in external stylesheets
- A selector that contains 1 ID is more specific than one with 1000 classes
- A selector that contains 1 class is more specific than one with 1000 elements
- The universal selector \* has no specificity value (0, 0, 0, 0)
- Rely more on specificity than on the order of selectors
- But, rely on order when using 3rd=party stylesheets - always put your author stylesheet last
