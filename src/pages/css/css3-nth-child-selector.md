---
title: CSS3 Nth Child Selector
---
## CSS3 Nth Child Selector

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/css/css3-nth-child-selector/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

CSS3 Nth-Child Selector

The :nth-child selector is used to interact with a specific child in a group of siblings. A practical example is shown below:

```
//Here is a parent list with three child elements 
<ul class="example">
	<li id="first">
		I'm the first child	
	</li>

	<li id="second">
		I'm the second child
	</li>

	<li id="third">
		I'm the third child
	</li>
</ul>

//CSS to make the font color for the first child blue
.example:nth-child(1) {
	color: blue;
}

//CSS to make background color green for third child
.example:nth-child(3) {
	background-color: green;
}
```

Important note: The nth-child selector is not zero based, like in many other instances of programming. This means that the first child is :nth-child(1). 

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->

[MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child)


