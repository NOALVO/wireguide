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

### 4. Blue elements - Features

4.1. _MUST_. Use the **blue** color to describe the content, origin and destination of features.

4.2. _MUST_. Define a **reference code** for each feature with a letter, starting from `A` to `Z`.

4.3. _SHOULD NOT_. Prefer omiting control labels and instead use the reference code described in 4.2.

4.4. _MUST_. Build a "**Table of Features**" including the reference code and the main details of each in a usable free space of the wireframe. If there is no free space in the wireframe, use the back of the sheet to make it.

4.5. _MUST_. When referencing features in Table of Features specified by item 4.4, **use `"` to describe their labels**.

4.6. _MUST_. When referencing features in Table of Features specified by item 4.4, **use `→` to indicate the destination of the feature**, like, but not limited to, opening dialogs and changing pages.

4.7. _MUST_. When referencing features in Table of Features specified by item 4.4, **use `←` to indicate the origin of the feature**, like, but not limited to, pages e other features, and also the source of labels, like, but not limited to APIs and internal funcions.

### 5. Red elements - Modifiers

5.1. _MUST_. Use the **red** color to indicate special behaviors of features.

5.2. _MUST_. Mark read-only controls with an X mark.

5.3. _MUST_. Mark elements and controls affected by user roles (privileges elevation) with a (`△`). Elements marked both with 5.2 and this marking will be considered not read-only if the role is satisfied. Indicate more details of the privilege and control behavior in the Table of Features.

5.4. _MUST_. Mark elements and controls that contains or triggers AJAX loaders with an horizontal three-dot.

5.5. _MUST_. Mark elements and controls that are repeatable by some iteration with a vertical three-dot. Indicate more details of the iteration in the Table of Features.

### 6. Green elements - Controls

6.1. 

### 7. Orange elements - Illustrations and layout to be determined

7.1. All **black**

### 8. Grids and browser bounds

### 9. Digitalizing
