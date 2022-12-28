# Different Layouts

# Basic Layouts in Android Studio

These Layouts used mostly,

**Linear Layout**

- Aligns the Children view either horizontally or vertically.
- Attribute `android:orientation` specifies whether to horizontally or vertically align children views.
- We usually use the attribute '`android:weight` in the children views/viewgroups to decide what percentage of the available space they should occupy.
- Attribute `android:weightSum` defines the maximum weight sum, and is calculated as the sum of the `layout_weight` of all the children if not specified explicitly.

**Relative Layout**

- Relative Layout enables us to specify how child views are positioned to each other.
- Position of each view can be specified as relative to sibling elements or relative to the parent.

_Note_: Relative Layout measures a view twice, whereas Linear Layout measures only once (if weights are not used).
[Click Me For Explaination](https://medium.com/@vatsalbajpai/android-relative-layout-vs-linear-layout-f27bf3d8f74e)

**Constraint Layout**

- Main motive of constraint layout is to design layouts which are flexible and look the same in all screen sizes.
- The layout editor uses constraints to identify the position of a view on the screen.
- Supports chaining of the view

![Chaining](https://i.imgur.com/GAPRCCf.png)

_I've just started my journey in Android Development. If i'm missing something important or else have questions. Pleae let me know. i'll update ASAP._
