Scale Demo

The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously.
Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis. Positive values will push an element down and to the right of its default position while negative values will pull an element up and to the left of its default position.
Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.
As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used. The transform-origin property can accept one or two values. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.
Since both of them are attempting to position the element, their values can collide. The perspective of an element can be set in two different ways.

Perspective Origin

The same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element.
To do so, we use three new transform values, including rotateX, rotateY, and rotateZ. Using the rotateX value allows you to rotate an element around the x axis, as if it were being bent in half horizontally. Using the rotateY value allows you to rotate an element around the y axis, as if it were being bent in half vertically. Lastly, using the rotateZ value allows an element to be rotated around the z axis.


3D Rotate Demo

By using the scaleZ three-dimensional transform elements may be scaled on the z axis. In the demonstration below the elements are being scaled up and down on the z axis, however the rotateX value is added in order to see the behavior of the scaleZ value.

3D Translate Demo

Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.

Transform Style Demo

So if you prefer not to see these elements at all, set the backface-visibility property to hidden, and you will hide the element whenever it is facing away from the screen. The other value to backface-visibility is visible which is the default value, always displaying an element, no matter which direction it faces.





One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years.

Vendor Prefixes

The code above, as with the rest of the code samples in this lesson, are not vendor prefixed.

The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change.

Transitional Properties

It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point.

Transition Duration

The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds and milliseconds .

Transition Timing

The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration.

Transition Delay

On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property.

Transition Delay Demo

Declaring every transition property individually can become quite intensive, especially with vendor prefixes.

transition: all 1s ease-in-out;.card:hover {.card .side {
backface-visibility: hidden;.card .back {


Animations Keyframes

To set multiple points at which an element should undergo a transition, use the @keyframes rule.

Vendor Prefixing the Keyframe Rule

The animation above is named slide, stated directly after the opening @keyframes rule. The different keyframe breakpoints are set using percentages, starting at 0% and working to 100% with an intermediate breakpoint at 50%.

Animation Name

Once the keyframes for an animation have been declared they need to be assigned to an element.

Once you have declared the animation-name property on an element, animations behave similarly to transitions.

Animation Iteration

By default, animations run their cycle once from beginning to end and then stop.

Animation Direction

On top of being able to set the number of times an animation repeats, you may also declare the direction an animation completes using the animation-direction property. Values for the animation-direction property include normal, reverse, alternate, and alternate-reverse.
The normal value plays an animation as intended from beginning to end.

Animation Play State

The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively.

Animation Fill Mode

The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run. The animation-fill-mode property accepts four keyword values, including none, forwards, backwards, and both.


Animation Fill Mode Demo

Fortunately animations, just like transitions, can be written out in a shorthand format.

