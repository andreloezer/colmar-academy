Colmar Academy
==============

Capstone Project *Colmar Academy* submitted to the *Freelance Website Development* course from **Codecademy**.

#### GitHub Pages

https://andreloezer.github.io/colmar-academy/

Description
-----------

A Landing page for a web development school's website, containing the sections:

- *Jumbotron* inviting to know about the school
- General *Information* about the school and its activities
- Featured *Courses*
- *Thesis* projects by students

About the Project
-----------------

CSS Variables were used in order to facilitate experimenting with styles for `font-family`, `color`, `background color` and the main *container*. Variables were not used to define the maximum and minimum widths for media queries since vanilla CSS3 doesn't support variables in the selectors. In order to use such variables it would be necessary to use CSS plugins or addons, which was beyond the goal of this exercise.

### **Typography**

*Google Fonts* were used due to the abundance of font families available. The fonts link points to *Google Fonts* CDN, to ensure the choosen font works across various devices. Specific styles like `font-size`, `line-height`, `font-style` give adequate emphasis to key elements, contributing with the design and flow of the page.

#### Font Family:

- **Headings**:     *Montserrat* - The inviting aesthetics is a good fit for headings, drawing the reader's attention
- **Main text**:    *Roboto* - Simple, yet enjoyable. Good fit for the main text
- **Course boxes**: *Raleway* - Clean and direct. Has a professional approach
- **Quotes**:       *El Messiri* - Its eccentricity is ideal for quotes, differentiating them from the main text

### **Color**

The color pallet was inspired on the *Saffron Umbrella* pallet from the **Adobe Color CC** website.

#### Pallet:

- **Bright**:    `#FAFAFA` Very bright shade of gray, almost white, used as background for some sections
- **Header**:    `#EAEAEA` Bright shade of gray, applied in the header. It creates a contrast with the sections (specially the ones with a *Bright* background) as the page is scrolled down
- **Medium**:    `#7695AB` Blue with medium brightness and medium saturation. Used as background for some sections in contrast with the with *Bright*. Also used in transitions effects in the boxes
- **Featured**:  `#FFA213` Orange with medium brightness and high saturation. Used only in highlighted places like the logo, some links and transitions effects
- **Dark**:      `#191919` Very dark gray intended primiraly as the color for the text. Also used as the outside of the main container and in transitions effects on the boxes in the *Courses* section

### **Overhall Design**

During development, some minors aspects of the positioning and details such as borders were changed for a more unique design. Although slightly different from the provided specs, these changes improve the visualization of the page.

#### Transitions

Various elements of the page have transitions on both `:hover` and `:focus`. These elements are:

- Links
- Navigation bars
- Button
- Boxes (boxes from the aside have the same transitions)

The *SVG* icon of the Logo from the *header* were inserted inside the HTML as an `<svg>` tag, allowing for color transitions.
On mobile version all the *header* icons inside nav are placed by `<img>` tags, transitions here caused issues with Chrome and Firefox.

#### Sizing:

The `font-size` in the root element is 16 pixels and lenght units are expressed in `rem`s, except borders and media queries.

#### Thesis

The video was set to loop, muted and autoplay. Its content is merely illustrative.
 
#### Container

The *container*'s width is 1280 pixels (common screen size). The `background-color` of the outside is **Dark** (`#191919`) to contrast with whichever section the user is reading. To prevent content of the *header* geting too close to the screen border when it's width is equal or just above of the *container*, the laterals paddings of the *header* only disappear in widths above 1328 pixels, wich equals to the *container* width plus padding from both sides (1280 + 1.5 x 16 x 2).

#### Mobile

Media queries provides the *mobile* version for screen widths equals or below 900 pixels it will render the page as *mobile*. Smallest screens 400 pixels or below have specific positioning and sizing for some elements.
