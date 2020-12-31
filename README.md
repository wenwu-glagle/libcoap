 This is a fork of [libcoap](https://github.com/obgm/libcoap).
 I am using libcoap in windows environment, the origin code sometimes has some compile error in windows, so I create this to fix them. 
 

BUILDING
========

```
  Build for windows:
  1. Open libcoap\win32\libcoap.sln with visual studio
  2. Add openssl include and lib directory if need,  openssl version need higher than 1.1.0
  3. Build it.
  
  Build for linux:
  1. ./autogen.sh
  2. ./configure
  3. make
  4. make install
```

LICENSE INFORMATION
===================

This library is published as open-source software without any warranty
of any kind. Use is permitted under the terms of the simplified BSD
license. It includes public domain software. libcoap binaries may also
include open-source software with their respective licensing terms.
Please refer to
[LICENSE](https://raw.githubusercontent.com/obgm/libcoap/develop/LICENSE)
for further details.

