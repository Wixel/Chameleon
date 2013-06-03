Chameleon
=========

Collection of CSS selectors that change link colors to the color of the site it's linking to.

Example:
The CSS selector targets the 'a' element with the corrisponding href attribute. in this case 'github'
<code>a[href*="github"]{color: #4183c4;}</code>

HTML: stays as simple as a link can be
<code>&#60;a href="http://example.<ins>github</ins>.com/project/" &#62;github&#60;/a &#62;</code>

features :
It's awesome.
Hopefully works on any color background (if not just play around with text-shadow).
Most sites colors (worth linking to) are included.
Awesome hover effect just to add to the awesomeness.
It's fairly easy to implement.
Did I mention it's awesome?

Adding it to your site :
Add the chameleon.css file to your sites folder.
Link to the .css file in your sites header.
Add the class 'color-back' to "body" or the div if the background is a color.
Remember "a:hover" must be after all selectors.
Type a link and see the awesomeness at work.
Remember your manners and thank me (@nicovanzyl actually I would just like your feedback and what you would want to see added to chameleon).


Check out a demo <a href="http://nicovanzyl.com/tools/chameleon/">here</a>
