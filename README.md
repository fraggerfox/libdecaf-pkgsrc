libdecaf-pkgsrc
===============

NetBSD pkgsrc script for libdecaf.

Libdecaf is a library that implements [Ed448-Goldilocks][1]

You can find libdecaf [here][2]

NOTE: This package is not yet available in the NetBSD pkgsrc tree.

Installation
------------

Copy `security/libdecaf` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any package.

`$ cd /usr/pkgsrc/security/libdecaf`<br>
`$ make install clean`

For a list of dependencies for the build check [here][3]

Credits
-------

* The libdecaf is developed and maintained by the [Mike Hamburg][4]

License
-------

BSD 2-clause. See LICENSE.

[1]: http://ed448goldilocks.sourceforge.net/
[2]: https://sourceforge.net/projects/ed448goldilocks/
[3]: https://sourceforge.net/p/ed448goldilocks/code/ci/master/tree/
[4]: https://www.shiftleft.org/about/

