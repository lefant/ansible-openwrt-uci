openwrt-uci
===========

setting of uci config keys on openwrt systems. this is just the
library module so that other openwrt roles can dependend on it.

check out https://github.com/lefant/ansible-openwrt for an example on
how it can be used.

compare: http://wiki.openwrt.org/doc/techref/uci

Requirements
------------

must be kept minimal as this is supposed to run on openwrt embedded
systems. in particular we try get by with plain POSIX shell, using
neither python nor bash in any way. lua could be an option as that
seems to be the openwrt scripting language of choice.

License
-------

BSD

Author Information
------------------

Fabian Linzberger, http://e.lefant.net/
