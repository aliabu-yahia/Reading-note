#RESPONSIVE WEB DESIGN and FLOATS
----------------------
## RESPONSIVE WEB DESIGN

Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones)

 Responsive web design is broken down into **three main components**, including flexible layouts, media queries, and flexible media

1- Flexible layouts

Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Reason being, the viewport height and width continually change from device to device. Website layouts need to adapt to this change and fixed values have too many constraints, we can used Ethans formula

2- Media Queries

Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example.

- Initializing Media Queries:
There are a couple different ways to use media queries, using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document. Generally speaking it is recommend to use the @media rule inside of an existing style sheet to avoid any additional HTTP requests.

- Logical Operators in Media Queries
Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including and, not, and only.

- Media Features in Media Queries
Knowing the media query syntax and how logical operators work is a great introduction to media queries but the true work comes with media features. Media features identify what attributes or properties will be targeted within the media query expression.

3- Flexible Media

As viewports begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.

-------------------------

## FLOATS
Clear has four valid values:

code         | It work
--------     |----------
clear: both  |  clears floats coming from either direction
clear: right |  used to only clear the float from right direction
clear: left  |  used to only clear the float from left direction
clear: none  | is the default (unnecessary unless)

# The different between the float and Absolutely positioned:

Floated elements remain a part of the flow of the web page. This is distinctly different than page elements that use absolute positioning and the Absolutely positioned page elements will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.

# Problems with Floats:

1- Pushdown

2- Double Margin Bug

3- The 3px Jog

4- Bottom Margin Bug


