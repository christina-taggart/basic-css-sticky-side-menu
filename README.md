# Layout Drill Sticky Side Menu 
 
##Learning Competencies 

##Summary 

 There are so many options for navigation menus, it can get a bit overwhelming.  There is no one "right" option, but there should be a clear relationship between the design of the navigation area and the layout and flow of the site.

For a site with a single-page style layout (i.e. almost all of the primary content is on a long, scrollable page), a "sticky" navigation area is useful because the user can easily jump around from one section to another without having to scroll all the way back to the top to view the navigation options.  What does "sticky" mean?  It means that when you scroll down the page, the navigation area stays locked in your view window: only the content area actually scrolls.

The [source gist](https://gist.github.com/dbc-challenges/c1e790667d9240f80b7a) contains a basic HTML file for a product site.  You will need to write the CSS to transform the ugly list of navigation links into nice sidebar-style sticky navigation menu.

You will need to brandish the powers of CSS's `position` property to get this to work properly.  If you aren't familiar with the difference between `static` and `fixed` positioning, you may want to check these resources out:

- [CSS Positioning 101](http://alistapart.com/article/css-positioning-101)
- [Video: Overview of CSS Positioning Values](http://css-tricks.com/video-screencasts/110-quick-overview-of-css-position-values/)

## Objectives

### Write your Markup and Style It

Add styles to your page by editing `main.css` so that your navigation menu looks like this:

![Sticky Side Menu](http://f.cl.ly/items/082D2b2l2L0V1C180k2G/sticky_side_menu-top.png)

What do you notice about this menu?  For starters, you should make style it thusly:

- The sidebar is `150px` wide and spans the full height of the window.
- The sidebar has a light gray background with a slightly darker gray border on the right side with a width of `2px`.
- Each link in the menu has a pleasing amount of spacing surrounding it.
- The menu links are black and will turn gray when the user hovers over them.
- The menu links are separated by a thin, light gray border.
- Even thought the sidebar now takes up `150px` of space on the window, notice that the content area *is centered within the whitespace, not centered within the full width of the browser window.*  This part may be a little tricky for you to figure out, so here's a hint: you can use the `padding` property of an element to increase its overall width.

What about the sticky part?  Look at the following screenshot, which shows a section of the page when scrolled down:

![Scrolled Down Side Menu](http://f.cl.ly/items/1U2K163k0k3z3e111D2O/sticky_side_menu-scrolled.png)

Notice that the sidebar is still in the same position with relation to the browser window.  Nothing has changed for the sidebar, only the content has scrolled.  That is what is meant by "sticky".

Finally, you should style your sidebar in such a way that when the browser window is made smaller, it maintains a `10px` space between the sidebar and the content area, like this:

![Side Menu in Narrow Page](http://f.cl.ly/items/1q251j370U1k1m1d3G0e/sticky_side_menu-narrow.png)

And **NOT** like this:

![Side Menu in Narrow Page - BAD](http://f.cl.ly/items/1W0k3u0t2D0U1D450Z24/sticky_side_menu-narrow-bad.png)

That is bad.  Don't do that. 

##Releases
###Release 0 

##Optimize Your Learning 

##Resources