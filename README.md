Chameleon
=========

Collection of CSS selectors that change link colors to the color of the site it's linking to.

###Example:
####CSS
The CSS selector targets the 'a' element with the corresponding href attribute. in this case 'github'
<code>a[href*="github"]{color: #4183c4;}</code>

####HTML
HTML stays as simple as a link can be
<code>&#60;a href="http://example.<ins>github</ins>.com/user/project" &#62;github&#60;/a &#62;</code>

###features :
* It's awesome.
* Hopefully works on any color background (if not just play around with text-shadow).
* Most sites colors (worth linking to) are included.
* Awesome hover effect just to add to the awesomeness.
* It's fairly easy to implement.
* Did I mention it's awesome?

###Adding it to your site :
1. Add the chameleon.css file to your sites folder.
2. Link to the .css file in your sites header.
3. Add the class 'color-back' to "body" or the div if the background is a color.
4. Remember "a:hover" must be after all selectors.
5. Type a link and see the awesomeness at work.
6. Tell me what you think on twitter (<a href="http://twitter.com/nicovanzyl">@nicovanzyl</a>).

###Demo
Check out a demo <a href="http://nicovanzyl.com/tools/chameleon/">here</a>
