# sumarization


## CSS Styling Images
* Rounded Images
Use the `border-radius` property to create rounded images:
**Example**
Circled Image:

`img {
  border-radius: 50%;
}`
* Use the `border` property to create thumbnail images.
* `img:hover` {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
} to make hover in amage and to make image like link use it inside `<a>` tages here `</a>`
* Responsive Images
Responsive images will automatically adjust to fit the size of the screen.

`img {
  max-width: 100%;
  height: auto;
}`
* Center an Image ->To center an image, set left and right margin to auto and make it into a block element:

`img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}`
* Polaroid Images / Cards
 to make `كرت `` div.polaroid {
  width: 80%;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);}img {width: 100%}div.container {text-align: center;padding: 10px 20px;}`
* Transparent Image
The `opacity` property can take a value from`0.0 - 1.0.` The lower value, the more transparent **opacity 1(default)** =1
Image Filters
* The CSS `filter property` adds visual effects (like blur and saturation) to an element.
* Image Hover Overlay
Create an overlay effect on hover:








