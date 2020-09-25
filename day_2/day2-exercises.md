## Chapters 3 & 4

1.
* Order lists contain lists where each item is numbered.
* Unordered lists contain lists where each item begins with a bullet point.
* Definition lists are made up of a set of terms along with the definition of each of those terms.

2. `<a href = "http://www.IMDB.com>"IMDB</a>`

3. You include the target attribute
 `<a href = "http://www.imdb.com>" target = "_blank">Internet Database</a>`

4. Using the id attribute. First, you use the id attribute to identify the point in the page you would like the link to go. Then, to link the element with the id attribute use href with a value starting with # followed by the id attribute you used in the element.
* EX: `<h1 id = "top"> ..... </h1>`
`<a href = "#top"> Top </a>`

## Chapters 10, 11 & 12

1. CSS allows you to create rules that specify how the content of an element should appear.

2. CSS stands for cascading style sheets. Cascading meaning that if you understand how the cascading rules effect your style sheets you can then write simpler ones because you can create general rules that apply to most elements and then override the properties on individual elements that need to appear differently.

3. CSS rule structure contains 2 parts: Selector = indicates which element the rule applies to. Declaration = indicates how the elements referred to in the selector should be styled.
* EX: `P {font-family: Arial;}`

4. Use the `<link>` element in an HTML document to tell the browser where to find the CSS file used to style the page. It lives in the head element and has 3 attributes:
* href - the path to CSS file.
* type - type of document being linked to. Value should be text/css.
* rel - specifies the relationship between the HTML page and file it is linked to. Value should be stylesheet.
* EX: `<link href="css/styles.css" type="text/css" rel="stylesheet />"`

5. When building a site with more than one page, you should use an external CSS style sheet. This allows all pages to sue the same style rules as opposed to repeating them in each page. Also allows you to change the styles used across all pages by altering just one file.

6. A color hex code are 6 digit codes that represent the amount of red, green and blue in a color preceeded by a #.

7. The three parts of an HSL color property is hue, saturation and lightness.

8. The three main categories of of fonts in typeface are serif, sans-serif and monospace.
* Serif - These have extra details on the ends of the main strokes of letters.
* Sans-serif - Have tight ends to letters and have a much cleaner design.
* Monospace - Every letter in monospace font is the same width. This type is used alot is code because they align nicely making it easier to read.

9. The three main units used when specifying font size is pixels, percentages and EMS.

<https://codepen.io/rachel-buchta/pen/BaKMvLM>
