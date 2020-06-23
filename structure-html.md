## Structure Web Pages with HTML

## Chapter 8: Extra Markup
HTML 4 (1997) -> XHTML 1.0 (2000) -> HTML5 (WIP)

- *Doctype* tag declares what version is being used by the page (ex '<!DOCTYPE html>')
- *Comments* will show up in code but not on page with '<!--  -->'
- *ID attributes* can uniquely identify an element from others
- *Class attributes* can identify a group of elements
- *inline* elements appear to continue on same line as opposed to *block* elements which appear to start on a new line.
- *Div* element allows you to group elements together in a block-level box
- *Span* functions like an inline version of *div*
- *Iframe* functions like a window in your page. Think of scrolling on a map to find a store's location on their site.
- *metadata* contains information about the page itself.

## Chapter 18: Process and Design

### Target user/audience
Thinking about demographics and user profiles helps facilitate usability.

* Individuals
- age
- gender
- location
- income
- education
- needs
- frequency of use
- device of choice

* Companies
- size of company or dept
- who within the company is the user?
- using for themselves or someone else?
- budget

### Why people visit websites

* Motivations
- entertainment, or goal oriented?
- personal or professional
- essential or luxury

* Goals
- general vs specific
- novice or advanced
- time sensitive?
- making a buying decision?
- do they need to contact the company or individual in charge of site?

User profiles can help build features to anticipate needs and frequent use cases.

**How frequently will users visit the site?**

### Site map and card sorting

Used to determine the organization and flow of pages and information. Often used with a *wireframe* -- a simple sketch of the information that needs to be on each page.

Use styles and visual hierarchies to emphasize and differentiate between different pieces of information.

## Chapter 17: HTML5 Layout

### Headers & Footers '<header>' and <footer>'
*Headers and footers* are used for creating consistent elements at the top and bottom of each page. The can also denote the beginning of an '<article>' or '<section>' within a page.

### Navigation '<nav>'
This element contains the site's navigation blocks 

### Article '<article>'
Used to contain a section of a page that could stand on its own (blog entry, comment, article, or other independent content). These elements can be nested within other articles -- as in the example of a blog post with comments nested within via individual '<article>' tags.

### Aside '<aside>'
The aside element can be used within an '<article>' or on its own. Inside, it contains related but nonessential information (glossary etc). On its own, it can contain info related to the entire page -- recent psots, search box, recent tweets, etc.

### Sections '<section>'
Groups related content, of which each often uses its own heading. Can contain several distinct '<article>' elements.

### Heading Groups '<hgroup>'
Groups together a setting of one more more headings '<h1>' through '<h6>'.

### Figures '<figure>' and '<figcaption>'
Contains content referenced from article's main content flow. Images, videos, graphs, examples, supporting text, etc. '<figure>' should contain a '<figcaption>' as alternate text for accessibility.

### Sectioning Elements '<div>'

Used to group together related elements.

### Linking
HTML5 can use anchor /"<a>" tags around an element to turn an entire element into a link.

*note*: Some older browsers do know understand HTML5 elements, and require JavaScript support to work properly.