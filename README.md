irssi-icb-port
==============

FreeBSD [Ports][4] script for Irrsi's ICB Plugin.

You can find the irssi-icb plugin [here][1]

Installation
------------

Copy `irc/irssi-icb` folder to `/usr/ports` directory.

NOTE: If your ports directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/ports/irc/irssi-icb`<br>
`$ make install clean`

Credits
-------

* The irssi-icb plugin was originally written by [Jonathan Perkin][2]
* The one used by this script is a fixed variant by [Marcus Glocker][3]
* Thanks to `trouble` and `_arthur_` for helping me come up with the port package and a
  machine to test the port development.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/mglocker/irssi-icb
[2]: https://github.com/jperkin
[3]: https://github.com/mglocker
[4]: https://www.freshports.org/irc/irssi-icb