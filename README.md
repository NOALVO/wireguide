# Wireguide
Styleguide for low-fidelity paper prototyping and wireframing.

> _The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt)._

## Table of Contents
1. [Objectives]()
2. [Pen]()
3. [Black elements 🖤 Containers]()
   1. [Navigation bars]()
   2. [Modal dialogs]()
   3. [Images]()
   4. [Tables and containers]()
4. [Blue elements 💙 Features]()
   1. [Table of Features]()
   2. [Double quotes]()
   3. [Right arrows]()
   4. [Left arrows]()
5. [Red elements ❤️ Modifiers]()
   1. [Blocked sign]()
   2. [Triangle sign]()
   3. [Horizontal ellipsis]()
   4. [Vertical ellipsis]()
6. [Green elements 💚 Controls]()
   1. [Input/text boxes]()
   2. [Buttons]()
   3. [Checkboxes]()
   4. [Radio buttons]()
   5. [Dropdown menus]()
   6. [Hyperlinks]()
   7. [Sliders]()
   8. [Switches]()
   9. [Tooltips]()
   10. [Progress bars]()
7. [Orange elements 💛 Illustrations and layout to be determined]()
8. [Grids and browser bounds]()
9. [Digitalizing]()

### 1. Objectives

1.1. These guidelines are meant to be used by product owners, managers, designers or developers planning to illustrate visual representations of computer software or internet pages, a.k.a. prototyping or wireframing.

1.2. These guidelines SHOULD be used to represent low-fidelity wireframes. Therefore, rounded borders, shadows, gradients, images, icons, animations or other complex graphical elements SHOULD NOT be used.

### 2. Pen 🖊

2.1. _SHOULD_ prefer using thin/sharp hydrographic pens or ballpoint pens. Avoid thick pens and markers.

2.2. _MUST NOT_ use pencils or automatic pencils in order to avoid poor visibility wireframes.

2.3. _MUST_ use black, blue, red, green and orange colors to draw elements, considering the rules below. In case you don't have green or orange colors, you MUST replace orange with red and green by black. If you don't have blue, red or black, well... you can't make a comprehensive wireframe.

### 3. Black elements 🖤 Containers

3.1. _MUST_ use **black** color for lines, containers and borders. For all, but not limited to, the following cases:
- Divs
- Panels
- Headers
- Navigation bars (both vertical and horizontal)
- Menus (tabs, navs, pills, dropdowns)
- Tables
- Text
- Images
- Modal dialogs

#### Navigation bars

3.2. _MUST_ include the word `LOGO`, prefixed by a trademark or logo at the beginning.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/32.PNG)

#### Modal dialogs

3.3. _MUST_ include close buttons (`×`) at the top-right corner.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/33.PNG)

#### Images (`☒`)

3.4. _MUST_ be represented by a square with an "X" mark touching its corners.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/34.PNG)

#### Tables and containers

3.5. _SHOULD_ draw only the first line of repeating elements, followed by a vertical ellipsis (`⋮`) at the middle of the container.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/35.PNG)

3.6. _SHOULD NOT_ draw bottom lines when taller than the wireframe's boundaries. Instead, apply three dashes (like an ellipsis) from each vertical line of the container's sides.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/36.PNG)

3.7. _SHOULD NOT_ draw right lines when wider than the wireframe's boundaries. Instead, apply three dashes (`- - -`) from each horizontal line of the container's sides.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/37.PNG)

### 4. Blue elements 💙 Features

4.1. _MUST_ use **blue** color to describe features' content, origin and destination.

4.2. _MUST_ define **reference codes** for each feature with a letter, starting from `A` to `Z`.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/42.PNG)

4.3. _SHOULD NOT_ label control elements directly. Instead, prefer using the reference code described in 4.2.

#### Table of Features

4.4. _MUST_ include each component reference code and their main details. Use any free space in the wireframe. If there isn't, use the back of the sheet to make it.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/44.PNG)

#### Double quotes (`"`)

4.5. _MUST_ use double quotes to describe labels of "Table of Features" items.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/45.PNG)

#### Right arrows (`→`)

4.6. _MUST_ use right arrows to indicate a feature's destination. Like, but not limited to, opening dialogs and changing pages.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/46.PNG)

#### Left arrows (`←`)

4.7. _MUST_ use left arrows to indicate a feature's origin. Like, but not limited to, pages and other features, and also the labels' sources, like, but not limited to APIs and its internal functions.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/47.PNG)

### 5. Red elements ❤️ Modifiers

5.1. _MUST_ use **red** color to indicate features' special behaviors.

#### Blocked sign (`🚫`)

5.2. _MUST_ mark with "blocked" signs read-only, blocked or disabled controls.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/52.PNG)

#### Triangle sign (`△`)

5.3. _MUST_ mark with triangles elements and controls affected by user roles (privileges elevation). Elements marked with both "blocked" sign and triangle will be considered not read-only if the role is satisfied. Describe further details of privileges and control behaviors in a "Table of Features".

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/53.PNG)

#### Horizontal ellipsis (`...`)

5.4. _MUST_ mark with horizontal ellipsis elements or controls that contain or trigger AJAX loaders.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/54.PNG)

#### Vertical ellipsis (`⋮`)

5.5. _MUST_ mark with vertical ellipsis elements or controls that repeat within an iteration with a vertical three-dot. Indicate more details of the iteration in the "Table of Features".

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/55.PNG)

### 6. Green elements 💚 Controls

#### Input/text boxes

6.1. _MUST_ draw input/text boxes with just a horizontal line. DO NOT draw inputs as rectangles, as they may be confused with buttons.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/61.PNG)

#### Buttons

6.2. _MUST_ draw buttons as rectangles, including image buttons. For buttons that have a cancel/abort/close behavior include a times character (`×`) aligned to its center.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/62.PNG)

#### Checkboxes (`☑`)

6.3. _MUST_ draw checkboxes as squares with a check mark inside.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/63.PNG)

#### Radio buttons (`🔘`)

6.4. _MUST_ draw radio buttons as circles with a dot inside.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/64.PNG)

#### Dropdown menus

6.5. _MUST_ represent dropdown menus writing "Dropdown", followed by a feature reference code (as described by 4.2) and a black triangle ponting down (`▼`).

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/65.PNG)

6.5.1. _MUST_ draw black containers (as described in 3.1) with a diagonal line from the top to the right line of the container's top-right corner for panel menus.

6.5.2. _MUST_ include underlines (`_`) at the beginning of dropdown menu items and below their labels.

6.5.3. _MUST_ include black triangles pointing right (`▶︎`) at the end of  dropdown items that activates another dropdown menu.

#### Hyperlinks

6.6. _MUST_ put dashed underlines (`_ _ _`) below their labels for hyperlinks.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/66.PNG)

#### Sliders

6.7. _MUST_ draw sliders as horizontal lines with a black filled circle on it.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/67.PNG)

#### Switches

6.8. _MUST_ draw switches as two rectangles (one filled and the other not) alongside.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/68.PNG)

#### Tooltips

6.9. _MUST_ draw tooltips as rectangles shaped with a left-chevron at the left side.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/69.PNG)

#### Progress bars

6.10. _MUST_ draw progress bars as two long rectangles (one filled and the other not) alongside. Place a `%` inside the white rectangle, as this drawing may be confused with switches.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/610.PNG)

### 7. Orange elements 💛 Illustrations and layout to be determined

7.1. _SHOULD_ draw proposals of text and illustrations that have to be officially determined with **orange** color.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/71.PNG)

### 8. Grids and browser bounds

8.1. _SHOULD_ use simple grids to draw containers and parts of pages.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/81.PNG)

8.2. _SHOULD_ use "browser" grids to draw pages and elements disposed inside a page.

![](https://raw.githubusercontent.com/NOALVO/wireguide/master/img/82.PNG)

8.3. _SHOULD_ use "tablet" and "mobile" grids to represent responsiveness adjusted desktop wireframes, or, if your wireframe is for a product that focus a specific plaform.

8.4. _SHOULD_ use [Sneakpeekit](http://sneakpeekit.com/) to print paper grids described by 8.1, 8.2 and 8.3.

### 9. Digitalizing

9.1. _SHOULD_ use [CamScanner]() to digitalize wireframes, applying "Lighten" or "Magic Color" filter.
