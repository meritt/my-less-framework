Wait, what is the LESS?
=======================

If you don't know about LESS you can read about it here: [lesscss.org](http://lesscss.org)

Mac OS X application for LESS [incident57.com/codekit](http://incident57.com/codekit/)

Installing
==========

    git submodule add git://github.com/meritt/my-less-framework.git public/css/mlf

And after that you need to import it in your style file.

Insert into your style.less

    @import "mlf/framework.less";

Functions
=========

**Basic**

 * .box-sizing(border-box);
 * .opacity(0.5);
 * .wrap();
 * .user-select(none);

**Animations**

 * .transition(all 500ms);
 * .rotate(45deg);
 * .scale(5);
 * .translate(0, 0);
 * .translate3d(0, 0, 0);
 * .skew(0, 0);
 * .animation(spinner 5s ease infinite);

**Backgrounds**

 * .background-size(50px 50px);
 * .linear-gradient(top, rgb(255, 255, 255), rgb(0, 0, 0));
 * .radial-gradient(50% 50%, rgb(255, 255, 255), rgb(0, 0, 0));
 * .background-horizontal(#00aaee, rgba(255, 255, 255, 0.2));
 * .background-vertical(#ff9900, rgba(255, 255, 255, 0.2));
 * .background-picnic(rgba(200, 0, 0, 0.5), rgba(200, 0, 0, 0.5), #ffffff);

**Borders**

 * .background-clip(padding-box);
 * .border-radius(5px);
 * .border-left-radius(5px);
 * .border-right-radius(5px);

**Columns**

 * .columns(2, 10px);
 * .column-count(2);
 * .column-gap(10px);

**Scrollbars**

 * .scrollbar(rgba(0, 0, 0, 0.2), 7px, 9px, 4px);

**Shadows**

 * .box-shadow(1px 1px 8px #ccc);
 * .blur-text-shadow(#ccc);
 * .line-text-shadow(#ccc);

Additional it includes reset and normalize styles.

Partial using
=============

Also, you can use this in partial, for example if you need only animations and transformations CSS3 functions, you can do this in following way:

    @import "mlf/functions/animations.less";

Author
======

* [Alexey Simonenko](mailto:alexey@simonenko.su), [simonenko.su](http://simonenko.su)

---

## License

The MIT License, see the included `license.md` file.