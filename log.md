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

    p {
      position: relative;
      bottom: 10px;
    }

Changing an element's position to relative does not remove it from the normal flow - other elements around it still behave as if that item were in its default position.

When the position of an element is set to absolute, it locks the element in place relative to its parent container. One nuance with absolute positioning is that it will be locked relative to its closest positioned ancestor. If you forget to add a position rule to the parent item, (this is typically done using position: relative;), the browser will keep looking up the chain and ultimately default to the body tag. 

Fixed positioning is a type of absolute positioning that locks an element relative to the browser window. 

The next positioning tool does not actually use position, but sets the float property of an element. Floating elements are removed from the normal flow of a document and pushed to either the left or right of their containing parent element. It's commonly used with the width property to specify how much horizontal space the floated element requires.

**Link to work:** 

### Day 4: August 6, 2018

**Today's Progress:** z-index to adjust position of overlapping elements, margin: auto to center a block element, complementary/tertiary colors, hsl(), linear-gradient, background: url(), transform: scale(), transform:skewX()

**Thoughts:** Hue is what people generally think of as 'color'. If you picture a spectrum of colors starting with red on the left, moving through green in the middle, and blue on right, the hue is where a color fits along this line. In hsl(), hue uses a color wheel concept instead of the spectrum, where the angle of the color on the circle is given as a value between 0 and 360.

Saturation is the amount of gray in a color. A fully saturated color has no gray in it, and a minimally saturated color is almost completely gray. This is given as a percentage with 100% being fully saturated.

Lightness is the amount of white or black in a color. A percentage is given ranging from 0% (black) to 100% (white), where 50% is the normal color.

The hsl() option in CSS also makes it easy to adjust the tone of a color. Mixing white with a pure hue creates a tint of that color, and adding black will make a shade. Alternatively, a tone is produced by adding gray or by both tinting and shading. Recall that the 's' and 'l' of hsl() stand for saturation and lightness, respectively. The saturation percent changes the amount of gray and the lightness percent determines how much white or black is in the color. This is useful when you have a base hue you like, but need different variations of it.

**Link to work:** [adobe color wheel](https://color.adobe.com/zh/create/color-wheel/)

### Day 5: August 7, 2018

**Today's Progress:** make a heart shape with css(::before, ::after), @@keyframes, animation properties(name, duration, fill-mode, literation-count)

**Thoughts:** Try to recreate what you couldn't understand at the first place.

**Link to work:**