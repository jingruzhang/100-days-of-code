# 100 Days Of Code - Log

### Day 0: August 2, 2018

**Today's Progress:** Set up Trello Board. My priorities of this 100-day challenge are to finish a Wordpress Developer course and finish responsive web design certification curriculum on freecodecamp. Set up dev environment for wordpress. 

**Thoughts:** 

**Link to work:** [local by flywheel](https://local.getflywheel.com/)


### Day 1: August 3, 2018

**Today's Progress:** Working on freecodecamp. Had a refresher on HTML and CSS. Internal sections, degrading fonts, border-radius, padding, margin, attribute selectors, absolute vs relative units, custom css variables, :root element, media query.

**Thoughts:** Can I use Google Fonts in China? If not, what's the alternative? 

**Link to work:** 


### Day 2: August 4, 2018

**Today's Progress:** Started Applied Visual Design section. text-align, width, height, font-weight, strong tag, u tag, em tag, s tag, box-shadow

**Thoughts:** 

**Link to work:** [box-shadow](https://css-tricks.com/almanac/properties/b/box-shadow/)

### Day 3: August 5, 2018

**Today's Progress:** Continued Applied Visual Design section. opacity, text-transform, font-weight, line-height, css box model, block-level items, inline items, top/bottom/left/right offset, position, float

**Thoughts:** Position property can override the normal flow of a document, aka the default layout of elements. 

When the position of an element is set to relative, it allows you to specify how CSS should move it relative to its current position in the normal flow of the page. It pairs with the CSS offset properties of left or right, and top or bottom. These say how many pixels, percentages, or ems to move the item away from where it is normally positioned. The following example moves the paragraph 10 pixels away from the bottom(move UP 10px):
```css
  p {
    position: relative;
    bottom: 10px;
  }
```

Changing an element's position to relative does not remove it from the normal flow - other elements around it still behave as if that item were in its default position.

When the position of an element is set to absolute, it locks the element in place relative to its parent container. One nuance with absolute positioning is that it will be locked relative to its closest positioned ancestor. If you forget to add a position rule to the parent item, (this is typically done using position: relative;), the browser will keep looking up the chain and ultimately default to the body tag. 

Fixed positioning is a type of absolute positioning that locks an element relative to the browser window. 

The next positioning tool does not actually use position, but sets the float property of an element. Floating elements are removed from the normal flow of a document and pushed to either the left or right of their containing parent element. It's commonly used with the width property to specify how much horizontal space the floated element requires.

**Link to work:** 

### Day 4: August 6, 2018

**Today's Progress:** z-index to adjust position of overlapping elements, margin: auto to center a block element, complementary/tertiary colors, hsl(), linear-gradient(), background: url(), transform: scale(), transform:skewX()

**Thoughts:** Hue is what people generally think of as 'color'. If you picture a spectrum of colors starting with red on the left, moving through green in the middle, and blue on right, the hue is where a color fits along this line. In hsl(), hue uses a color wheel concept instead of the spectrum, where the angle of the color on the circle is given as a value between 0 and 360.

Saturation is the amount of gray in a color. A fully saturated color has no gray in it, and a minimally saturated color is almost completely gray. This is given as a percentage with 100% being fully saturated.

Lightness is the amount of white or black in a color. A percentage is given ranging from 0% (black) to 100% (white), where 50% is the normal color.

The hsl() option in CSS also makes it easy to adjust the tone of a color. Mixing white with a pure hue creates a tint of that color, and adding black will make a shade. Alternatively, a tone is produced by adding gray or by both tinting and shading. Recall that the 's' and 'l' of hsl() stand for saturation and lightness, respectively. The saturation percent changes the amount of gray and the lightness percent determines how much white or black is in the color. This is useful when you have a base hue you like, but need different variations of it.

**Link to work:** [adobe color wheel](https://color.adobe.com/zh/create/color-wheel/)

### Day 5: August 7, 2018

**Today's Progress:** make a heart shape with css(::before, ::after), @@keyframes, animation properties(name, duration, fill-mode, literation-count)

**Thoughts:** Try to recreate what you couldn't understand at the first place.

**Link to work:**

### Day 6: August 8, 2018

**Today's Progress:** continued animation properties: animation-timing-function(ease, linear, ease-in, ease-out, cubic-bezier()). Finished Applied Visual Section and started Applied Accessibility. It's mandatory to use alt text, when sometimes it needs to be left blank. main, header, footer, nav, article, section, audio(controls), figure, label(for...id), fieldset, legend tags.

**Thoughts:** [how to easily create a multilingual site using wordpress](https://www.wpbeginner.com/beginners-guide/how-to-easily-create-a-multilingual-wordpress-site/)

**Link to work:** [animation-timing-function](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function)

### Day 7: August 9, 2018

**Today's Progress:** Finished Applied Accessibility. html: input(type,id,name), time(datetime), sup, accesskey attribute, tabindex.

 CSS is used to position the screen reader-only elements off the visual area of the browser window.

Here's an example of the CSS rules that accomplish this:
```css
  .sr-only {
    position: absolute;
    left: -10000px;
    width: 1px;
    height: 1px;
    top: auto;
    overflow: hidden;
  }
```

Note
The following CSS approaches will NOT do the same thing:

display: none; or visibility: hidden; hides content for everyone, including screen reader users.

Zero values for pixel sizes, such as width: 0px; height: 0px; removes that element from the flow of your document, meaning screen readers will ignore it.


The Web Content Accessibility Guidelines (WCAG) recommend at least a 4.5 to 1 contrast ratio for normal text. The ratio is calculated by comparing the relative luminance values of two colors. This ranges from 1:1 for the same color, or no contrast, to 21:1 for white against black, the strongest contrast. There are many contrast checking tools available online that calculate this ratio for you.

**Thoughts:** A clearly structured html file is the foundation of everything web.

**Link to work:**

### Day 8: August 10, 2018

**Today's Progress:** Finished responsive web design section and started css flexbox.
make an image reponsive: 

```css 
img {
  max-width: 100%;
  display: block;
  height: auto;
}
```
The max-width property of 100% scales the image to fit the width of its container, but the image won't stretch wider than its original width. Setting the display property to block changes the image from an inline element (its default), to a block element on its own line. The height property of auto keeps the original aspect ratio of the image.

The simplest way to make your images appear "retina" (and optimize them for retina displays) is to define their width and height values as only half of what the original file is.

Viewport units are relative to the viewport dimensions (width or height) of a device, and percentages are relative to the size of the parent container element.

The four different viewport units are:

vw: 10vw would be 10% of the viewport's width.
vh: 3vh would be 3% of the viewport's height.
vmin: 70vmin would be 70% of the viewport's smaller dimension (height vs. width).
vmax: 100vmax would be 100% of the viewport's bigger dimension (height vs. width).

Placing the CSS property display: flex; on an element allows you to use other flex properties to build a responsive page.

flex-direction

### Day 9: August 11, 2018

**Today's Progress:**

**Thoughts:** 

**Link to work:**