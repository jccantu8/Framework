Exercise from [the Odin Project](theodinproject.com/courses/html5-and-css3/lessons/design-your-own-grid-based-framework?ref=lnav) where the task was to create a framework and use
it to recreate a page on the web.

The framework is based on a 12 column grid system and includes basic functionality,
such as:

-Margins (tiny, small, medium, big, and huge)
-Padding (tiny, small, medium, big, and huge)
-Horizontal list
-Default button
-Image that scales to the parent container
-Responsive media queries
-Simple reset
-Flex options

The grid works as follows. First, create a container class followed by a row
class in a similar vein to Bootstrap. Next, fill up the row with elements
that contain column sizes from 1-12, making sure they sum to 12 in total.
There is an option to automatically fill up the rest of row with whatever
space is remaining by using **col-auto**, however this only works in Chrome.

The responsive media queries are currently limited to widths of 768 and 1024
pixels. In order to use this, add **responsive** to all elements in a 
container that you wish to be responsive. Next, add **respond-768**, 
**respond-1024** and/or **respond-bigger-than-1024** to the elements you wish
to show at at these widths. See examples in the sample page, odinpage.html.

To test the framework, a clone of the [Odin Project's main page](https://www.theodinproject.com/) was made. Here
are two comparisons.

![Comparison 1](/images/comparison1.png?raw=true)

![Comparison 2](/images/comparison2.png?raw=true)