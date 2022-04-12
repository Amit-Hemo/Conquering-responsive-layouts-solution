# What breakpoints to use?
* in media queries we use min/max-width to tell what to do from/to different screen sizes. but how do we know which sizes to choose? 
* go to responsive mode - while in inspect mode (f12/right click and then inspect...) type ctrl+shift+M or click the icon with the different sized tablets, then you can play with the viewport widths and look *when the layout starts to break*, that will be your breakpoints.
* we will have different sections on the sites, so will we pick a breakpoint for each section to be perfect? No. We want to aim getting 1-2 breakpoints to "catch" the whole site.
* but there are a lot of devices... shouldn't we add media queries based on each device? AGAIN NO. a lot of breakpoints are not good for us and there are a lot of devices, BUT there are common sizes that fits in groups of devices at once and most of the time fits our plan when choosing our breakpoints. 

## common sizes 
* below 600px - mobile phones.
* 600px to 900px/960px - tablet portait
* 900px to 1200px - tablet landscape
* 1200px to 1800px - desktop 
* above 1800px - big desktop 

*note - we can try to consider these sizes but we aim for the minimum we can breakpoints we can use to make it work, some can go under one breakpoint.*

**for more on setting breakpoints:**
https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/