# CSS 
stands for cascading style sheets. Sets the look and fuel of the website.

## Level 1 (CSS Basics)

1) Basic Syntax :- Selector, property and value } Declaration

h1{
    font-size: 30px;
}

2) Color Property :- The CSS color property defines the text color or foreground color in an HTML element. 

3) Including Styles :- 
i) Inline Styling 
ii) Internal Styling 
iii) External Styling -> Using another css file.

4) HTML Refresher (Tags and Attributes) and DOM(Document of Object Model) is a tree structure of html elements.

5) Comments :- Used to add notes in HTML or CSS code
// Single Line Comment
/* */ Multi Line Comment

6) MDN Documentation :- Official resource for CSS3 latest updates.

7) Browser Tools :- 

    CSS Specific Tools -> Styles Panel, Box Model
    Source Tab -> Have the file that are shown on the browser.
    Network Tab -> Used for request and response
    or networking concepts.
    Performanace Tab -> used to measure the performanace of the webpage or website.

8) Selectors :- 
i) Element Selector (h1, p, h2, etc).
ii) Universal Selector (*) -> Apply to all elements.
iii) Id Selector (#first).
iV) Class Selector (.second).
v) Group Selector (h1, h2, h3).
vi) Descendant Selector (div > p).

## Level 2 (Color System and Background)

9) Background-color :- Sets the background color of an html element.

10) Color System :- 

Color Theory -> Red, Green and Blue are the foundational colors.
Color Picker -> picks any color or copy any color.
RGB Color Model -> Have three channels and value (0-255) -> rgb(r, g, b).
Hex Color Model -> Have hexadecimal value #402ae9.
Alpha Channel -> Used fot transparency levels rgb(100,101,102,0.5);

11) Absolute Units :- Pixels (px) are fixed-size units, representing a dot on a computer screen.
A pixel is the smallest unit of a digital image or display, often referred to as a "picture element." It represents a single point in a graphic and is the basic building block of digital images. Multiple pixels combine to form the images you see on screens, such as TVs, tablets, and computer monitors.

12) Height and Width Property :- height: 40px, width: 40px;
Can also use max-height, min-height, max-width and min-width.

13) Background Image Property :-  Usage: Adds an image as a background to elements.
 • Syntax: Defined using background-image: 
url('path/to/image’);.
 • Repetition: Control image repetition using 
background-repeat.
 • Positioning: Adjust image position using background
position.
 • Size Control: Manipulate image size using 
background-size.
 • Background-Attachment: Sets whether the 
background image scrolls with the element or 
remains fixed.
 • Shorthand (color, image, repeat, attachment, 
position)

14) Visibility Property :- Controls the visibility of elements without changing the layout.

## Level 3 (Text Properties) 

15) Text-Align Property :- Controls the horizontal alignment of text within an element.

16) Text-Decoration Property :- Modifies the apperance of inline text. (none, underline, overline, line-through). Also has variety of style and color.

17) Text-Transform Property :- Controls the capitalization of text.(uppercase, lowercase, none, etc).

18) Line-Height :- Adjusts the amount of space above and below inline elements. Useful for controlling vertical spacing between lines of text.

19) Font Property :- font-size, font-weight(100-900), font-style(Useful for highlighting),

20) Font Family -> Defines which font should be used for text within an element(Fallback Mechanism).

21) Icons using Fonts :- Use font awesome website for fonts.

## Level 4 (Box Model)

22) What is Box Model :- Central concept in CSS that outlines the design and layout of elements on the web page.
Have four main components -> margin, padding, border, content.

23) Padding Property :- The space b/w the border and the actual content. Shorthand -> padding: 10px 20px 30px 40px;

24) Margin Property :- Sets the space around elements, separating them from others. Shorthand -> margin: 10px 20px 30px 40px;
can be auto for central alignment.

25) Border Property :-  Creates an outline around HTML elements.
border: 2px solid black;

Border-radius -> Used to create rounded corners for elements. border-radius: 10px 20px;

Box-sizing -> border-box or content-box, in border-box, border is counted into content itself.

## Level 5 (Display and Position)

26) Display Property :- 
Block Elements -> Take up all horizontal space(div, h1, p)
Inline Elements -> Just as wide as the content in the element(span, a, strong)

display: block; // Change the type of element to block element.
display: inline; // Change the type of element to inline element.
display: inline-block; // Change the type of element to inline element but we can also set the height and width of element.
display: none; // Remove the element from the page.

27) Responsive Website :- 
 1. Adapts layout for different screen sizes
 2. Flexible layouts
 3. Optimizes images and assets
 4. Enhances user experience on mobile and desktop

28) Relative Units :- 
 1. Percentage -> set the dimensions of element in percentage with respect to the parent element.
 2. em -> set the font-size of text in em with respect to the parent element.
 3. rem -> set the font-size of text in rem with respect to the root element.
 4. vw/vh ->  • Viewport Relative Units: Units based on viewport's width (vw) or height (vh) for 
responsive design.
 • Responsive Layouts: Essential for creating adaptive layouts; e.g., height: 100vh for 
full-screen sections.
 • Element Sizing: Useful for defining heights and widths that scale with the 
viewport.

29) Position Property :- 
 • Static (default) : Elements follow the normal document flow. (top, right, 
bottom, left, z-index would not work)
 • Relative: Element's position adjusted from its normal position.
 • Absolute: Positions element relative to the nearest positioned ancestor.
 • Fixed: Element positioned relative to the viewport, does not move on scroll.

Z-index -> Integer Values: Accepts integer values, including negative numbers.
 • Higher Values: An element with a higher z-index value appears 
above others.

30) Semantic Tags :- 
Semantic Tags
 ● Meaningful: Describe content.
 ● SEO: Good for search engines.
 ● Accessibility: Useful for screen 
readers.
 ● Examples: <header>, <footer>, 
<article>, <section>, <nav>.

Non-Semantic Tags
 ● Generic: No specific meaning.
 ● For Styling: Used for layout.
 ● No SEO: Not SEO-friendly.
 ● Examples: <div>, <span>, <i>, 
<b>.

## Level 6 (Flex Box, Grid and Media Queries)

31) Float Property :- 
• Element Alignment: Allows elements to be aligned to the left or right 
within their containing element. 
• Values: Can take values like "left", "right", or "none" to determine the 
floating direction. 
• Old Layout Technique: Less commonly used with the advent of Flexbox.

32) What is FlexBox? :-
Flexbox is a one-dimensional layout method for arranging items in rows or columns. 
Items flex (expand) to fill additional space or shrink to fit into smaller spaces.

















