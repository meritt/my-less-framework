Wait, what is the LESS?
=======================

If you don't know about LESS you can read about it here: [lesscss.org](http://lesscss.org)

Mac OS X Application for LESS [incident57.com/less/](http://incident57.com/less/)

Installing
==========

		git submodule add git@github.com:meritt/my-less-framework.git public/css/less-framework

And after that you need to import it in your style file, for example

Edit public/css/style.less

		@import "less-framework/framework.less";

Current functions
=================

**Basic**

 * opacity

**Animations**

 * highlight
 * rotate
 * scale
 * animation

**Backgrounds**

 * background-size
 * linear-gradient
 * radial-gradient
 * background-horizontal
 * background-vertical
 * background-picnic

**Borders**

 * background-clip
 * border-radius
 * border-left-radius
 * border-right-radius

**Columns**

 * columns

**Scrollbars**

 * scrollbar

**Shadows**

 * box-shadow
 * blur-text-shadow
 * line-text-shadow

Additional it includes reset styles, and default rules for elements.

Partial using
=============

Also, you can use this in partial, for example if you need only CSS3 function, you can do this in following way:

		@import "less-framework/function.less";

Author
======

Alexey Simonenko, alexey@simonenko.su