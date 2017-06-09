Colmar Academy
==============

Capstone Project *Colmar Academy*, of the *Freelance Website Development* course from **Codecademy**.

#### GitHub Pages

https://andreloezer.github.io/colmar-academy/

Description
-----------

A Landing page from a website of a web development school, containing:

- *Jumbotron* inviting to know the school
- General *Information* about the school and activities
- Featured *Courses*
- *Thesis* from students

About the Project
-----------------

To facilitate experimenting with some of the styling options it was used CSS Variables for the `font-family`, `color`, `background-color` and the main container. They couldn't be used to define the maximum and minimum widths of the media queries since the vanila CSS3 doesn't support variables in the selectors. To achiev this it would be necessary using some pluggin or addon in the CSS, which is beyond the goal here.

### **Typography**

To have access to a vast amount of font families and ensure that the choosen one works across the numerable devices is was used a link to the *Google Fonts* database. The specifics stylings like `font-size`, `line-height`, `font-style` were set to give the necessary enphasis on each element, keeping in touch with the design and flow of the page.

#### Font Family:

- **Headings**:     *Montserrat* The Inviting aestetics fits well for the headers, drawing atention from the reader
- **Main text**:    *Roboto* Simple, yet enjoyable, does a good job for the main text
- **Course boxes**: *Raleway* Clean and direct for a more professional approach
- **Quotes**:       *El Messiri* Eccentricity gives a destac from the main content, fitting for a quote

### **Color**

The color pallet was chosen based on the *Saffron Umbrella* pallet from the **Adobe Color CC** website.

#### Pallet:

- **Bright**:    `#FAFAFA` Very bright shade of gray, almost white, used as background for some sections
- **Header**:    `#EAEAEA` Bright shade of gray, applied in the header, it creates a contrast with the sections (in special the ones with a *Bright* background) as the page is scrolled down
- **Medium**:    `#7695AB` Medium brightness and medium saturation blue, used as background for some sections in contrast with the with *Bright*, also used as transitions effects in the boxes
- **Featured**:  `#FFA213` Orange with medium brightness and high saturation used only in highlighted places like the logo, some links and transitions effects
- **Dark**:      `#191919` Very dark gray intended as the color for the text, but also used as the outside of the main container and in transitions effects on the boxes in the *Courses* section

### **Overhaul Design**

As the development was going, some minors aspects of the positioning and details were changed for a more unique design. Although differing from the provided specs, none of the changes affected the objective of the page. The changes are in the positioning of some boxes, asides and borders.

#### Transitions

Various elements of the page have transitions, all of then are on both `:hover` and `:focus`. The elements with transitions are:

- Links
- Navigation bars
- Button
- Boxes (boxes from the aside have the same transitions)

On the *header* the *SVG* icons were inserted inside the HTML as tags `<svg>` allowing transitions on their color.


#### Sizing:

The size of the font in the root element (html) is set to 16 pixels and the lenght units of all elements are expressed in `rem`s, excepet the borders.

#### Thesis

The video was set to loop, be muted and autoplay, because its content suggest to be mere ilustrative.
 
#### Container

The *container* was added mid-project and its width is to 1280 pixels (a very common screen size for computer monitors). The `background-color` of th outside part  is **Dark** (`#191919`) it aims to ensure a contrast with whatever section the user is reading. To prevent that the content of the *header* gets too close to the screen border when it's size is close or little above the width of the *container*, the laterals paddings of the *header* were set to only disappear in widths above 1328 pixels, wich equals to the container width plus padding from both sides (1280 + 1.5 x 16 x 2).

#### Mobile

The *mobile* design is achieved with the use of media queries, for screen widths equals or bellow 900 pixels it will render the page in the *mobile* version. To ensure a better positioning and sizing on the smallest screens there is a media query set to 400 pixels or bellow.
