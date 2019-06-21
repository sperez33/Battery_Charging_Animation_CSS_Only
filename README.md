# Battery_Charging_Animation_CSS_Only
A little project my manager at RSI gave me to work on to improve my CSS skills.

June.20.2019 - 2:19p - added an absolute position attribute to the DIV that holds my images. No animations yet but I did 
get the images perfectly overlapped using position, top, left, transform: translate, and the z-index. I also Added in 
position, top, left, transform: translate, and animation into .charging in the CSS. I entered in the entire block of 
.charging:before for when I add in the animation.

June.20.2019 - 2:40p - I went in and added 'animation: animateBattery# 1s linear infinite;' to all the batteries. Then I 
added all their individual keyframes and didn't give them an opacity until it was essentialy their turn. The animation isn'that
as smooth as I'd like but It's real close to it. Possible opacity issue.

June.21.2019 - 9:37a - I added an additional percentage, with the exception for battery 0, right before it's suppose to be 
visible. Example, if the image shows at 25% percent at full opacity, at 24% i place the opacity at 0 to make the transition
more like with JavaScript. I also added in color and made it go slower. from 1s to 5s. I also removed any 'z-index's in 
the code. Opacity must be maintained after its turned solid, so if it starts at 25%, it keeps going until it hits 100%.