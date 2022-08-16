<h1>Css Notizen</h1>

* The basic anatomy of CSS syntax written for both inline styles and stylesheets.

* Die gewöhnlichsten CSS Begriffe sind: ruleset, selector, und declaration.

* CSS "inline styles" können in einem HTML Dokument geschrieben werden wenn man das "style" Attribut verwendet. can be written inside the opening HTML tag using the style attribute.

* "inline styles" können dafür verwendet werden um ein HTML Dokument zu stylen, aber es ist nicht die beste übung.

* Ein "internal stylesheet" wird durch ein <style> Element geschrieben, das in einem <head> Element ist. und das in einem HTML Dokument.

* "internal stylesheets" können auch dazu verwendet werden um ein HTML Dokument zu stylen sind aber auch nicht die beste Übung.

* Ein "external stylesheet" seperiert einen CSS code von einem HTMLDokument, in dem es eine .css erweiterung benutzt.

* "external stylesheets" sind der beste Ansatz um ein HTML Dokument zu stylen.

* "external stylesheets" sind mit dem <link> Element verbunden zum HTML Dokument.

* CSS kann HTML Elemente auswählen, wie zum Beispiel "type", "class", "ID","attribute".

* Alle Elemente können mit dem "universal selector" ausgewählt werden.

* Ein Element kan mit dem "pseudo-class selector" verschiedene Zustände haben.

* Es können mehrere "CSS classes" in ein HTML Dokument sein.

* "Classes" kann man an verschiedenen Orten gebrauchen un "ID's" können nur einmal gebraucht werden.

* "ID's" sind spezifischer als "classes" und "classes" sin spezifischer als "type". Das heisst "ID's" können "styles"  von "classes" überschreiben und "classes" können "styles" von "type" überschreiben.

* Multiple selectors can be chained together to select an element. This raises the specificity but can be necessary.

* Nested elements can be selected by separating selectors with a space.

* Multiple unrelated selectors can receive the same styles by separating the selector names with commas.

* The font-family property defines the typeface of an element.

* font-size controls the size of text displayed.

* font-weight defines how thin or thick text is displayed.

* The text-align property places text in the left, right, or center of its parent container.

* Text can have two different color attributes: color and background-color. color defines the color of the text, while background-color defines the color behind the text.

* CSS can make an element transparent with the opacity property.

* CSS can also set the background of an element to an image with the background-image property.

* The !important flag will override any style, however it should almost never be used, as it is extremely difficult to override.

* The box model comprises a set of properties used to create space around and between HTML elements.

* The height and width of a content area can be set in pixels or percentages.

* Borders surround the content area and padding of an element. The color, style, and thickness of a border can be set with CSS properties.

* Padding is the space between the content area and the border. It can be set in pixels or percent.

* Margin is the amount of spacing outside of an element’s border.

* Horizontal margins add, so the total space between the borders of adjacent elements is equal to the sum of the right margin of one element and the left margin of the adjacent element.

* Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.

* margin: 0 auto horizontally centers an element inside of its parent content area, if it has a width.

* The overflow property can be set to display, hide, or scroll, and dictates how HTML will render content that overflows its parent’s content area.

* The visibility property can hide or show elements.

* The position property allows you to specify the position of an element.

* When set to relative, an element’s position is relative to its default position on the page.

* When set to absolute, an element’s position is relative to its closest positioned parent element. It can be pinned to any part of the web page, but the element will still move with the rest of 

* the document when the page is scrolled.

* When set to fixed, an element’s position can be pinned to any part of the web page. The element will remain in view no matter what.

* When set to sticky, an element can stick to a defined offset position when the user scrolls its parent container.

* The z-index of an element specifies how far back or how far forward an element appears on the page when it overlaps other elements.

* The display property allows you to control how an element flows vertically and horizontally in a document.

* inline elements take up as little space as possible, and they cannot have manually adjusted width or height.

* block elements take up the width of their container and can have manually adjusted heights.

* inline-block elements can have set width and height, but they can also appear next to each other and do not take up their entire container width.

* The float property can move elements as far left or as far right as possible on a web page.

* You can clear an element’s left or right side (or both) using the clear property.

* Named colors—there are more than 140 named colors, which you can review here.

* Hexadecimal or hex colors

* Hexadecimal is a number system that has sixteen digits, 0 to 9 followed by “A” to “F”.

* Hex values always begin with # and specify values of red, blue, and green using hexadecimal numbers such as #23F41A.

* Six-digit hex values with duplicate values for each RGB value can be shorted to three digits.

* <h2>RGB</h2>

#ffffff #000000

* RGB colors use the rgb() syntax with one value for red, one value for blue and one value for green.

* RGB values range from 0 to 255 and look like this: rgb(7, 210, 50).

* RGBA heisst Rot Grün Blau Alpha 

* <h2>HSL</h2>

* HSL stands for hue (the color itself), saturation (the intensity of the color), and lightness (how light or dark a color is).

* Hue ranges from 0 to 360 and saturation and lightness are both represented as percentages like this: hsl(200, 20%, 50%).

* You can add opacity to color in RGB and HSL by adding a fourth value, a, which is represented as a percentage.

* Typography is the art of arranging text on a page.

* Text can appear bold or thin with the font-weight property.

* Text can appear in italics with the font-style property.

* The vertical spacing between lines of text can be modified with the line-height property.

* Serif fonts have extra details on the ends of each letter. Sans-Serif fonts do not.

* Fallback fonts are used when a certain font is not installed on a user’s computer.

* The word-spacing property changes how far apart individual words are.

* The letter-spacing property changes how far apart individual letters are.

* The text-align property changes the horizontal alignment of text.

* Google Fonts provides free fonts that can be used in an HTML file with the <link> tag or the @font-face property.

* Local fonts can be added to a document with the @font-face property and the path to the font’s source.