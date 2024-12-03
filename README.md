# words-effect


1. HTML:- Create the layout to form an alphabet.
2. CSS:- Arrange elements to create an alphabet, working with "perspective" and its "origin" and how to create fall effect of anything.
3. Javascript:- Use of Settimeout function.
   
The majority of thing that you will learn by building this is of CSS property.


#### Note :
# If you have noticed I have given inline styles to all the elements because it will be really bad thing to give different class or use selector for each word and then assign CSS to them.
# All these words are positioned absolute to the parent and with the help of their top and left properties they are positioned to different places to form the alphabet.
# Some elements also contains the horizontal class which rotates them by 90deg.


## About translateZ
# translateZ which moves the element towards screen and gives it 3D effect. using translateZ we pull the elements from its base towards upward and then when window is loaded we change it 0 which shows that words are falling.
# The value of translateZ(Xpx) decides its position on the screen. X == 0 is on the screen and then X > 0 is above the screen and X < 0 is below the screen.

## About Perspective and its origin
# The perspective property defines how far the object is away from the user. So, a lower value will result in a more intensive 3D effect than a higher value.
# The perspective-origin property defines at from which position the user is looking at the 3D-positioned element.
