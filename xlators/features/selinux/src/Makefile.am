xlator_LTLIBRARIES = selinux.la

xlatordir = $(libdir)/glusterfs/$(PACKAGE_VERSION)/xlator/features

selinux_la_LDFLAGS = -module $(GF_XLATOR_DEFAULT_LDFLAGS)

selinux_la_SOURCES = selinux.c

selinux_la_LIBADD = $(top_builddir)/libglusterfs/src/libglusterfs.la

noinst_HEADERS = selinux.h selinux-messages.h selinux-mem-types.h

AM_CPPFLAGS = $(GF_CPPFLAGS) -I$(top_srcdir)/libglusterfs/src \
	-I$(top_srcdir)/rpc/xdr/src -I$(top_builddir)/rpc/xdr/src

AM_CFLAGS = -Wall $(GF_CFLAGS)

CLEANFILES =

