# uClibc rpc tests
# Licensed under the LGPL v2.1, see the file COPYING.LIB in this tarball.

TESTS := getrpcent

ifeq ($(UCLIBC_HAS_REENTRANT_RPC),y)
TESTS += getrpcent_r
endif

include ../Test.mak

DODIFF_getrpcent := 1
