moduledir = @moduledir@
AM_CPPFLAGS = -I$(top_srcdir)/lib -I../../lib
export top_srcdir

module_LTLIBRARIES := libconfgen.la
libconfgen_la_SOURCES = \
	confgen.h confgen-plugin.c
libconfgen_la_CPPFLAGS = $(AM_CPPFLAGS)
libconfgen_la_LIBADD = $(MODULE_DEPS_LIBS)
libconfgen_la_LDFLAGS = $(MODULE_LDFLAGS)


include $(top_srcdir)/build/lex-rules.am
