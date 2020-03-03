# CSS
### Transforms
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

**Transform Syntax**
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

**2D Transforms**
Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.

**Combining Transforms**
To combine transforms, list the transform values within the transform property one after the other without the use of commas.

**Transform Origin**
 the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.
The transform-origin property can accept one or two values.

**Perspective**
The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.

### Transitions & Animations
With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

**Transitions**
There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

**Shorthand Transitions**
 Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.

 **Animations**
 o set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

 **Customizing Animations**
 Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation runs, as well as the direction in which an animation completes.

 **Shorthand Animations**
 This is accomplished with one animation property, rather than multiple declarations. The order of values within the animation property should be animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, and lastly animation-play-state.


 ### 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
 **1. Fade in:** Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.

**2. Change color:** Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.

**3. Grow & Shrink:** To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

**4. Rotate elements:** CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element. 

**5. Square to circle:** A really popular effect at the moment is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.

**6. 3D shadow:** This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen.

**7. Swing:** Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

**8. Inset border:** We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.