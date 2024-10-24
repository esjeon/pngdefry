
pngdefry
========

Normalizing Apple-specific CgBI-fried PNG files. Originally by [jongware](https://web.archive.org/web/20211120053356/http://www.jongware.com/pngdefry.html).

Some more details on CgBI can be found here: <https://theapplewiki.com/wiki/PNG_CgBI_Format>

Note that this repo is created as an archive.

Compiling
----------

This code does not depend on any external libraries, so compiling is as easy as this:

    $ cc pngdefry.c

Note that you need to compile only **pngdefry.c**, because it includes **miniz.c**.

