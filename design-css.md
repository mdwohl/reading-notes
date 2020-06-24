## Ch 10: Designing Web Pages with CSS

**CSS** (cascading style sheets) can style various elements on a website with consistency. A CSS file is usually external and linked in the HTML page, but CSS can be described within the page itself -- though that is generally not done.

The fundamental pieces of a CSS element styling are **selector** and the **declaration**.

* The selector determines which element the rule applies to.
* The declaration is the rule itself. It indicates how the element should be styles.

Furthermore, the declaration can be divided into two components:

* the **property** indicates what aspects of the element will change...color, font, etc
* the **value** specifies what will be used on the chosen property. Red, yellow, bold, height, size, etc

When using external CSS:
- [x] Specificy where the document is with a link via href
- [x] Specify type "text/css"
- [x] Specify relationship with rel="stylesheet"

CSS stylesheets cascade -- that is, they prioritize rules based on order in which they appear (think order of operations in math).

## Ch 11: Color

**Color** can be described with:
* **RGB** values (red/green/blue)
* **hex code** (#FF0000)
* **color names** of which therea are 147 recognized by browsers such as (DarkCyan)

**Foreground color** sets color of text; **background color** sets color of field containing text.

With CSS, you can set colors per element

'body {
    background-color: DarkCyan:}

h1 {
    background color: #ee3e80}'

Some key color concepts:

* **hue** is what we conventionally think of as color
* **saturation** is the amount of gray -- more saturation, less gray; less saturation, more gray.
* **brightness** (aka value) is the amount of black in the color. Max brightness, no black in color; minimum brighness, more black and color is very dark.

Various levels of **contrast** (low, med, high) have different functinos in page design. Low contrast should generally be avoided. High contrast is bold, and easy to read, but can fatigue if there is a lot fo read. Medium contrast works well for longer text.

**CSS3** has some features that are not supported by all browsers.
* Opacity (how see-through a foreground color is on the background)
* HSL colors --  color selection based on Hue Saturation and Lightness values.
* RGBA colors -- the A indicates opacity.

Color is important for creating mood, emphasis, and conveying information. 