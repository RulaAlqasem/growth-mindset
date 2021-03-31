# What Google Learned From Its Quest to Build the Perfect Team 
Psychological safety: Everyone feels safe in taking risks around their team members, and that they won't be embarrassed or punished for doing so. Dependability: Everyone completes quality work on time. Structure and clarity: Everyone knows what their specific expectations are.
### The key characteristics of Improved teams
After years of analyzing data and interviews from more than 180 teams across the company, Google found that the kinds of peopl in a team no so pertinent.
Instead, the researchers found that there were five key characteristics of improved teams:
1- Psychological safety: Everyone feels safe in taking risks around their team members, and that they won’t be embarrassed or punished for doing so.
2- Dependability: Everyone completes quality work on time.
3- Structure and clarity: Everyone knows what their specific expectations are. These expectations must be challenging yet attainable.
4- Meaning: Everyone has a sense of purpose in their work (i.e., financial security, supporting family, helping the team succeed, etc.).
5- Impact: Everyone sees that the result of their work actually contributes to the organization’s overall goals.
### Not all researchers agree
While Google’s findings may be true to some extent, a large number of scientific studies have caused researchers (outside of Google’s lab) to shockingly disagree. They claim the exact opposite — that personality, not just skills, is indeed a significant factor in what makes a team successful.

![google image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIbmIOBtvOB-2frH9dM72TFU8HscyEcHP81A&usqp=CAU)

# css (transforms) 
CSS transforms are a collection of functions that allow to shape elements in particular ways: translate: moves the element along up to 3 axis (x,y and z) rotate: moves the element around a central point. scale: resizes the element.

### Values
- scale(): Affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.
- skewX() and skewY(): Tilts an element to the left or right, like turning a rectangle into a parallelogram. skew() is a shorthand that combines skewX() and skewY by accepting both values.
- translate(): Moves an element sideways or up and down.
- rotate(): Rotates the element clockwise from its current position.
- matrix(): A function that is probably not intended to be written by hand, but combines all transforms into one.
- perspective(): Doesn’t affect the element itself, but affects the transforms of descendent elements’ 3D transforms, allowing them all to have a consistent depth perspective.

### skw: 
The skew() element performs a shear transformation (also known as a shear mapping or a transvection), which displaces each point of an element by a given angle in each direction.

Skewing an element is kind of like taking the points of an element, and pushing or pulling them in different directions, based on a given angle.
example :
```
{
  skew(ax)

skew(ax, ay)
}
```
### rotate: 
This rotates an element clockwise from its original position, whilst a negative value would rotate it in the opposite direction. Here’s a simple animated example where a square continues to rotate 360 degrees every three seconds
```
h1
{
rotation-point:50% 50%;
rotation:180deg;
}
```
### transforms;
Probably the most useful of the transformations, rotate does exactly what it says on the tin: it rotates any element. The browser should not assume the unit of measurement used, so it needs to be included for the rotation: radians (rad), turns (turn) or degrees (deg) for degrees. To provide one example, sans vendor prefixes:
```
img#inception {
	width: 400px;
	height: 267px;
	border: 15px solid #ffd;
	transform: rotate(2.5deg);
	float: left;
	margin-right: 2em;
}
```
The major issue that non-IE browsers have is one of smoothing and antialiasing edges of rotated elements, especially text, although this has taken dramatic steps forward in recent browser versions.

# Transition and Animation 
- transition 
The simplest (and most straightforward) way to animate your components is through CSS Transitions. In this article, you’ll learn how CSS Transitions work, and how to make animations with it.

A transition occurs when a CSS property changes from one value to another value over a period of time.
transition-property refers to the CSS property you wish to transition. It is required in the transition shorthand.

transition-duration refers to the duration of the transition. How long do you want the transition to last? This value is written in seconds with the s suffix (like 3s). It is also required in the transition shorthand.

transition-timing-function refers to how to transition occurs. You’ll learn more about this later.

transition-delay refers to how long you want to wait before starting the duration. This value is written in seconds with the s suffix (like 3s). transition-delay is optional in the transition shorthand.

![css ](https://www.freecodecamp.org/news/content/images/2020/10/Untitled--2--1.png)

-Animation 
By now you’ve probably heard at least something about animation in CSS3 using keyframe-based syntax. The CSS3 animations module in the specification has been around for a couple of years now, and it has the potential to become a big part of Web design. Using CSS3 keyframe animations, developers can create smooth, maintainable animations that perform relatively well and that don’t require reams of scripting. It’s just another way that CSS3 is helping to solve a real-world problem in an elegant manner. If you haven’t yet started learning the syntax for CSS3 animations, here’s your chance to prepare for when this part of the CSS3 spec moves past the working draft. In this article, we’ll cover all the important parts of the syntax, and we’ll fill you in on browser support so that you’ll know when to start using it.

![css ](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_124b8aca585c9626cb20541ec655726c.png)

# 8 SIMPLE CSS HOVER EFFECTS
ith support for CSS3 increasing with each new release for every browser, and those tiresome CSS2-only browsers slowly dropping off the usage charts, we have far more options for hover effects and transitions in general. Almost all the calls to action that you see on the Web use some form of hover effect, because they draw the eye and make a website feel more engaging
1. HORIZONTAL IMMERSION 
A style I’ve been seeing more and more of lately is one where a semi-transparent background color makes the button appear to be immersed on hover. It usually comes from one side and transitions until the entire button is covered.
2. VERTICAL IMMERSION
This effect is very similar to the one above, except that in this case we’ll be animating the height to make the color seem like it’s falling from the top of the button
3. GHOST BUTTON
In this little snippet we’ll add a simple but highly effective transition to the button. The ghost button effect is when we invert the color in the button and add a border
4. ICON ANIMATE IN
This effect is great for functions, like adding an item to a cart, or submitting a form. What we’ll do is have an icon slide in and appear next to the text, when the user hovers over the button.
5. BOUNCE EFFECT
In this animation we’re going to set some keyframes for the button so that we have a bounce effect when the user hovers on it. This is always a great way to grab a user’s attention.
6. SKEW
Skew is definitely one of the most peculiar transforms in CSS3. We’ve had it in Photoshop for years, but getting in in CSS3 was a surprise to say the least
7. DOTTED BORDER
This effect is a lot like the ghost button effect, but instead of a uniform border, we get a dotted line
8. FLIP 3D EFFECT
This last effect is a little more complicated since it involves flipping the button over to reveal another message we’ve added in the after pseudo-element of the button.
