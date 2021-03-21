1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
    <dl>
      <dt>Ordered Lists</dt>
      <dd>Are in numerical order, or a list of steps.</dd>
      <dt>Unordered Lists</dt>
      <dd>Are simply a bullet list of strings of texts, in no particular order.</dd>
      <dt>Definition Lists<dt>
      <dd>Display a word or "title", followed by the definition or description indented below it. These are also in no particular order.</dd>
    </dl>
2. What is the basic structure of an element used to link to another website?
    `<a href="http://www.imdb.com">IMDB</a>`
    1) The opening link tag, `<a>`
    2) Followed by the text the user clicks.
    3) Ending with the closing link tag.`</a>`
3. What attribute should you include in a link to open a new tab when the link is clicked?
    `target="_blank"`
4. How do you link to a specific part of the same page?
    By using id attributes.

<hr>

1. What is the purpose of CSS
    * To specify how content in html elements should look.
2. What does CSS stand for? What does cascading mean in this case?
    * Cascading Style Sheets
    * Because more than one stylesheet declaration could apply an HTML element, the rules of how to style each element are chosen by cascading down the stylesheet looking for a specific rule that matches that element.
3. What is the basic structure of a CSS rule?
    `p {
      font-family: Arial;
    }`
    * There are two parts: a `selector` (`p` in the above example) and a `declaration` (`font-family: Arial;` in the above example.)

4. How do you link a CSS stylesheet to your HTML document?
    * The `<link>` element is used within the `<head>` tag.
    `<link href="css/styles.css" type="text/css"
      rel="stylesheet" />`
5. When is it useful to use external stylesheets as opposed to using internal CSS?
    * When building a site with more than one page. Then all the pages can use the same style sheet. This will also create faster load times for the site as a whole.
    * When changes need to be made you will only need to edit one file to upload the CSS on the whole site.
6. Describe what a color hex code is.
    * A 6 digit code that represents the amount of red, green, and blue in a color.
7. What are the three parts of an HSL color property?
    * Hue, Saturation, & Lightness
8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?
    * serif, sans-serif, and monospace.
    * serif fonts have extra details on the ends of the main strokes.
    * sans-serif have straight ends to letters for a cleaner design than serif fonts
    * monospace letters have a fixed-width, so each letter is the same width
9. When specifying font-size, what are the main three units used?
    * `px`, `%`, or `em`

    https://codepen.io/janitastic/pen/yLVmjmW
