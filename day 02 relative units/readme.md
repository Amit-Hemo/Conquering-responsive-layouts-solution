# Why not using px?
- Because everything grows and shrinks in the same proportion.
- If we use media query, we can change the html font size and everything will be adjacted.
- Just make sure to use it correctly and it will make our lives a lot easier in the future.

# What are em and rem units? 
### em: 
- if we set font size to em units depended, it will be in relation to it's parent element.
- 1em = 16px initially if we didn't set a font size to the parent: if the parent is font size is 10px so the child will also be 1em = 10px.
- **note:** if we set the **font size of the parent** with em so it will be also related to it's parent, so the child now can be bigger or smaller because of it's parent or grand grand parent(and so on) and this can lead to a problem, so *be carefull!* 

### rem: 
- deals with the problem we saw in em. rem relates to the **root element** which is the html file, so 1rem === 16px always.

======================
# Not only for font sizes !!
- we can also use these units for more things than just font size and things are going to be different.
- common: padding , margin, width, height.
- *em-* They look on the **font size of the element the are in!**
- *rem-* still looks on the root of 16px.  

# SO em... what for? 
- *good for buttons:* we can add em padding to a button. Now the size of the button is going to be adjusted to it's font size in the same propoרtion. *but the margin between the button will be with rem to make it consistent! and if we want consistent size of buttons also you rems on padding*

# It is good for media query 
- we can change the html font size on bigger screens and everything is going to be fit in the same proportion but bigger without worrying about margin and padding ...

# Why you shouldn't set font-sizes using em?
- because of the heritence problem we talked about before.
- font size is going to be with rem!