LDADD = ../lib/libfpac.a
sbin_PROGRAMS = fpaccfg
fpaccfg_SOURCES = fpaccfg.c

AM_CPPFLAGS = -DAX25_SYSCONFDIR=\""$(sysconfdir)/ax25/"\" \
              -DAX25_LOCALSTATEDIR=\""$(localstatedir)/ax25/"\" \
	      -I$(srcdir)/../lib

AX25_SYSCONFDIR=@sysconfdir@/ax25/
AX25_LOCALSTATEDIR=@localstatedir@/ax25/

