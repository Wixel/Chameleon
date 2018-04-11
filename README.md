Chameleon
=========

Collection of CSS selectors that automatically change link colors to the color of the site it's linking to. eg. Github, Facebook

### Example:
#### CSS
The CSS selector targets the 'a' anchor element with the corresponding href attribute. in this case 'github'

<code>a[href*="github"]{color: #4183c4;}</code>

#### HTML
HTML stays as simple as a link can be

<code>&#60;a href="http://example.<ins>github</ins>.com/user/project" &#62;github&#60;/a &#62;</code>

### Info :
* It's awesome.
* Most sites are included. Make a PR or new issue to add yours if you see it's missing.
* ***It's extremely easy to implement. (just add the CSS file to your site)***
* Or add the .scss file to your existing project
* Did I mention it's awesome?
