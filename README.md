# Udacity Personal Portfolio Mock-up
A mock-up portfolio page to recreate as practice for building my own responsive portfolio site.  Working on this project should showcase my current abilities using front-end tools to develop and style a web page.

## Project Overview

The completed portfolio page mock-up will be evaluated using a project specification (rubric), which can be found [here](https://review.udacity.com/#!/rubrics/45/view).

This mock-up utilizes a pre-conceived page design which I will follow for the page's initial structure and styling.  This design can be downloaded [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a136147_design-mockup-portfolio/design-mockup-portfolio.pdf)

## Developer Notes

- The header container with the Udacity logo is left-aligned.  The name of the portfolio owner and their subtitle are right-aligned.

- The header is separated from main content area (a section) by a thick grey horizontal rule (#7dd97ad).

- On either side of this horizontal rule, there is an even amount of margin (take actual measures of pixel spacing throughout).

- A large image is utilized in the body of the portfolio.  My aim is to follow the rubric and make this image responsive as it is the main content (think placeholder) for the **_mock-up_** portfolio.

- The next section is a collection of featured work utilizing images.  Consider how this section would be made responsive - e.g., the content should be stacked for narrower viewport widths.

**_UPDATE_**

The main requirements for the portfolio mock-up were completed on Monday, May 14, 2018.  There remain some outstanding concerns with effectively using CSS to achieve a modern and responsive layout using Flexbox.

## Questions I'd like to address:
- Why do divs inside containers require the enclosing container to be set with a fixed width before you can center nested elements?  How does this influence decision-making about responsive CSS.

- For the common flexbox pattern, _layout shifter_, I was unable to get the styling rule "justify-content" to work as specified by the MDN article on [this topic](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container).  Understanding _why_ my CSS sheet prevented functionality of this rule will require follow-up research.

- The media query used to alter the "Featured Work" section of my layout only after exceeding a viewport width of 1043px was a major compromise of my planned design. After finding that, at smaller viewport widths, applying the style-rule "float: left;" created problems with the images in this section overlapping at the breakpoint, I was forced to settle with a design where a larger than favorable margin is created between the first two images in the row.  Alternate ways to handle how to work with appropriately wrapping content in a flex container will have to be explored further.
