This directory (I'm a Unix guy; these are directories, not folders.) contains
the source for the presentation.

The presentation uses Doug Tangren's [picture-show][] tool. Install it with
[conscript][]:

    $ cs softprops/picture-show

Run it, from this directory, like this:

    $ pshow

Sub-presentations are in subdirectories. To add a sub-presentation:

* create the subdirectory, under `preso`
* add the subdirectory to `preso/conf.js`

See Doug's [picture-show][] repo for docs. Unless you're Doug, who surely has
it all memorized.

[picture-show]: https://github.com/softprops/picture-show
[conscript]: https://github.com/n8han/conscript
