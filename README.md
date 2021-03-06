libschannel provides a mutually authenticated secure channel over
TCP/IP. It is intended for small embedded systems (and their counterpart
server programs) for which a full-fledged PKI is unnecessary; most people
will want to use a mutally-authenticated TLS-secured TCP connection.

The `autobuild.sh` script can be used to build the library. Alternatively,
once the `configure` script is generated using `autoreconf`, the standard

```
./configure && make && sudo make install
```

dance may be performed.


## DEPENDENCIES

This software requires [libsodium](https://github.com/jedisct1/libsodium).


## CODE REVIEW

This code has not been reviewed. Use at your own peril.


## LICENSE

This software is dual-licensed under the ISC license and released into
the public domain.

