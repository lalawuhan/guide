---
title: Reduce Repetition Using the repeat Function
---
## Reduce Repetition Using the repeat Function

The repeat() CSS function is a function you can use with the grid-template-columns and grid-template-rows properties to make your rules easier to understand when creating a large amount of columns or rows. 

The repeat() function needs two things(followed by a comma): 
* How many times you want to repeat the action
* The value that you want to repeat 

Repeat Function Example:
```.container{
    grid-template-columns: 2fr 2fr 2fr;
    /* Equals */
    grid-template-columns: repeat(6, 1fr);
}
```

### Solution to problem

```grid-template-columns: repeat(3, 1fr);```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
