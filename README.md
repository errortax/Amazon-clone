# Amazon-clone
A static website using HTML and CSS 
Some important CSS properties : 
Flexbox:
display:flex
this creates two invisible axis: 1 main axis and 1
cross axis.

By default the main axis is horizontal. To change the 
direction of main axis we can use flex-direction
flex-diredction: row is default

We can align our items on the main axis using 
justify content property.The default is flex-start
flex-start-->left corners
flex-end-->to the right corners
center--> place to the center
space-between--> space is is only in between
space-around--> similar to between but adds bit space
around
space-evenly--> place space around all items

To align items in the cross axis:
align-items property:
flex-start:upperrow
flex-end: at the end of the cross axis
center: to the center
baseline: so the baseline text of each item is aligned

If we set flex-direction to be column then the main
axis will be changed to vertical axis.So now 
justify content will align contents vertically	

flex-wrap: by default it is nowrap
wrap: are allowed to wrap when there is no more space
available. SO now new content has been unlocked**
align-content: Only works when wrap is used 
[Pretty much same as the justify content]

gap: used to place gap between items

flex-grow: takes a unitless value that serves as a
proportion that allows items to grow if there is 
enough space to do so
flex-shirk: how fast one item shrinks in comparison to 
others
if 0--> then it refuses to shrink
flex-basis:if item has a width already and we want to
override the property then it is used

if 0--> shrinking it to the max
shorthand for the above three:
flex: grow shrink basis --> overrides for align-items
if only one value is set, then others are set automatically
but for individual item-> align-self to override the value in the container


order: for the last to be front-->-1
the first to the end--> 1
**not prefered to use as it masses with the 
semantics and the accessabilities of the HTML


Position:

Absolute
Static and relative 
fixed and sticky

*static is the default value
*absolute needs a relative parent.If it doesn't have an ancestor element that is positioned relative, then it takes the initial box which is browser window

if outer box is relative then the absolute will be set according to the relative
Note: it peaks the ancester that is the closest to it

Relative:it means it's going to be relative to the parent container already without having to define that relative
on the parent

fixed:Even if we scroll it will be in the exact same position but never moving. If we want the absolute block on top then z-index->default 0

Sticky:It will have a normal flow untill it have reached a spot that has been defined. When the container it is in reaches the end, it will stick to the scrolling unlike the fixed and in the end it scrolls of the page 

Note: scroll-behaviour is used to html{} property to give the links a cool scrolling effect

