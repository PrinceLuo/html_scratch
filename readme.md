In this file I will put some information that related to the very push. It may
be some new knowledge or something worth being reminded. Good luck.

================================================================================

20181218

tag &lt;hr&nbspace;/&gt; means a line

tag &lt;br&nbspace;/&gt; means shifting into a new line

tag &lt;strong&gt; means bold

tag &lt;em&gt; makes text displayed in italics by the browser

tag &lt;a&gt; name="#fragment" fragment, combo with a link that target to the fragment

tag &lt;a href="mailto:luoruichun1990@gmail.com"&gt; will activate your local email
tools, and ready to send an email (not recommand)

tag &lt;a href="www.baidu.com" title="China top search engine"&gt; attribute, it will
be shown when hovering it

tag &lt;ul&gt;: each list start with a point; 
tag &lt;ol&gt;: each list start with a number

================================================================================

20190122

css: line-height means the line gap
	font-style measn the style the word shows
	text-align means the position
	text-indent specifies the indentation of the first line in a text-block
	inside body (which means the whole page), background-color specifies the color for the
	background. And the color specifies the color for the elements inside the body
	body background-image: add a picture as the background; default, it will fill the 
	background automatically, repeating itself one by one; background-repeat:no-repeat
	and background-repeat: repeat-x could help; background-position: 10px 40px
	padding: {top} {right} {down} {left}
	padding-top
	border: border-style     border-color     border-width
	margin:{top} {right} {down} {left}
	margin-top
	same as padding, if you set the first element only, all four elements will be set
	a: {state}  make a link dynamically
	table and td will inherit the tr; tr will inherit the table
	list-style-*: change the leading symbol of each list element
	sometimes when there is listing, you may not want the leading symbol appear, so
	{list-style-type:none; padding:0} could help
	{{head}} > {{child}} : child tag selector
	{{tag}}:{{sudo-element}} control some elements in a tag
	format: {{ <link rel="stylesheet" href="reference.css"> }}
	{{ <script type="text/javascript" src="reference.js"></script> }}
	Overwrite: The closest one will work
	position: absolute		【I only care about myself】
	position: relative		【the element will strat moving from its origin position】
	position: fixed			【the element will be placed in a fixed position in the window, no matter you roll up and down, left and right】
	
	I may add a 【float and clear】 into this series.
	before understand 【before】 and 【after】, simply add clear after those float div
	easiest way: clear at the end of every float div
	
================================================================================

20190222

Additional informations worth reminding:
Changes found so far to make it work with bootstrap 4v
1. "collapse in" replaced by "collapse show"
2. btn-default removed. Can use btn-light
3. well replaced by card
4. hidden replaced by d-xx-none (d-sm-none, d-lg-none, ect) (and d-xx-block)
5. Glyphicons not supported
6. change 'col-md-offset-6' to 'offset-md-6'
7. do not change library files like the video do. Write a new css file, and include it after the bootstrap library

Also try to convert this pages to Bootstrap 4v

================================================================================

20190226

1. Container
2. Page Header
3. Jumbotron
4. Button Styling
5. Grid Layouts / Responsive Layouts
6. Responsively Hiding Elements 
7. Offset
8. Table Styling
9. CSS Styling with Bootstrap 
10. Carousel / Slide Shows
11. Icons
12. Well
13. Image Styling
14. Contextual Colors
15. Dropdown Menus
16. Input Groups
17. Horizontal Menus
18. Vertical Menus
19. Tabbed Panels
20. Responsive Navigation Bar
21. Pagination
22. Responsive Blog Layout
23. Progress Bars
24. Responsive Blog Layout 2
25. List Groups
	