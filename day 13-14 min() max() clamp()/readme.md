# min()
* remember that in the container we put width: 80% and max-width: 750px?
so now we can put these two in one equivalent line which is width: min(80%,750px) and we can think about it like the min we know from math lessons, it takes the minimum between these values. 

# max()
* works the opposite from min.

*note: in min() and max() the order we put the value doesn't matter*

## we can include math inside min() and max()
* still don't know the reasons for math but for example: min(80% - 2rem, 750px) 
*note: remember to put spaces between the the units and the operation like in the example*.


# clamp()
* works only with 3 values.
* it is like setting min-width, max-width and width at once.
*note: here in clamp() the order of the values inside matters.*
* it is not recommended to use min-width because it can have some problems when it comes to mobile.
so, also clamp() is not so used for setting widths.
* *implementaion: clamp(min,adeal,max)*

## clamp() is really good for font-size
* we can use vw (viewport width) unit to set font-sizes, so it adjusts the font-size to the width on the screen, but using this makes it 
impossible to see in mobile screen sizes.  
* with clamp we can correct this, for expample: clamp(1rem, 1.25vw, 1.25rem), it sets the min to 1 rem so it won't get smaller than that in small screens and the ideal size is 1.25 of the vw but it won't get passed the 1.25rem. 
* with this tool we can adjust font-sizes to the screens.

*conclusion: use min() to shortcut width and max-width, use clamp() for responsive font-sizes*