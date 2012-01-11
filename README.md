Wait, what is the LESS?
=======================

If you don't know about LESS you can read about it here: [lesscss.org](http://lesscss.org)

Mac OS X application for LESS [incident57.com/codekit](http://incident57.com/codekit/)

Installing
==========

    git submodule add git://github.com/meritt/my-less-framework.git public/css/mlf

And after that you need to import it in your style file, for example

Insert into your style.less

    @import "mlf/framework.less";

Current functions
=================

**Basic**

 * opacity
 * wrap
 * user-select

**Animations**

 * transition
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

Also, you can use this in partial, for example if you need only animations and transformations CSS3 functions, you can do this in following way:

    @import "mlf/functions/animations.less";

Author
======

Alexey Simonenko, alexey@simonenko.su