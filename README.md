# wireguide
Styleguide for low-fidelity paper prototyping and wireframing.

> _The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt)._

### 1. Objectives

### 2. Pen

2.1. _SHOULD_. Prefer using thin/sharp hydrographic pens or ballpoint pens. Avoid thick pens and markers.

2.2. _MUST NOT_. Don't use pencils or automatic pencils in order to avoid poor visibility wireframes.

2.3. _MUST_. Use black, blue, red, green and orange colors to draw elements, attending to the following rules below. When you don't have green or orange color, you MUST replace orange by red and green by black. When you don't have blue, red or black, well... you could not make a comprehensive wireframe.

### 3. Black elements - Containers

3.1. _MUST_. Use the **black** color for general lines, containers and borders. In all, but not limited to, the following cases:
- Divs
- Panels
- Headers
- Navigation bars (both vertical and horizontal)
- Menus (tabs, navs, pills, dropdowns)
- Tables
- Text
- Images
- Modal dialogs

3.2. _MUST_. For **navigation bars**, when the bar is prefixed by a trademark or logo, include the word `LOGO` at the beggining of the bar.

3.3. _MUST_. **Modal dialogs** must include close button (`×`) at the top-right corner.

3.4. _MUST_. **Images** must be represented by a square with an x mark touching its corners.

3.5. _SHOULD_. For **tables** and **general containers** that includes repeatable elements, include three vertical dots at the center of container.

3.6. _SHOULD_. For **tables** and **general containers** that is supposed to be taller than wireframe bounds, DO NOT finish the container with a bottom side line, and apply a three vertcial dashes following each horizontal side of container.

3.7. _SHOULD_. For **tables** and **general containers** that is supposed to be wider than wireframe bounds, DO NOT finish the container with a bottom side line, and apply a three horizontal dashes following each vertical side of container.

#### 4. Blue elements - Features

4.1. _MUST_. Use the **blue** color to describe the content, origin and destination of features.

4.2. _MUST_. Reference each feature by a letter, starting from `A` to `Z`.

4.3. _SHOULD NOT_. Prefer omiting control lables and instead use the reference code described in 4.2.

4.4. _MUST_. Build a Table of Features including the reference code and main details of each in a usable free space of the wireframe. If there is no free space in wireframe, use the back of sheet to make it.

4.5. _MUST_. When referencing features in Table of Features specified by item 4.4, use `"` to describe their labels.

4.6. _MUST_. When referencing features in Table of Features specified by item 4.4, use `→` to indicate the destination of the feature, like, but not limited to, opening dialogs and changing pages.

4.7. _MUST_. When referencing features in Table of Features specified by item 4.4, use `←` to indicate the origin of the feature, like, but not limited to, pages e other features, and also the source of labels, like, but not limited to APIs and internal funcions.

#### 5. Red elements - Modifiers

#### 6. Orange elements - Illustrations and layout to be determined

#### 7. Grids and browser bounds
