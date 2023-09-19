## TRMM Radar Software Library (RSL)

Forked from http://trmm-fc.gsfc.nasa.gov/trmm_gv/software/rsl/functionality_index.html

To compile:
```
sudo apt-get install libbz2-dev libz-dev netpbm bison flex
./configure --prefix=/usr/local/trmm CFLAGS=-I/usr/include/tirpc/
make AUTOCONF=: AUTOHEADER=: AUTOMAKE=: ACLOCAL=:
sudo make install AUTOCONF=: AUTOHEADER=: AUTOMAKE=: ACLOCAL=:
sudo cp /usr/local/trmm/bin/wsr88d_decode_ar2v /usr/bin/
cd /usr/local/trmm/lib/
sudo cp librsl.so.1 /usr/lib/
```
