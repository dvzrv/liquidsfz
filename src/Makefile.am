bin_PROGRAMS = liquidsfz

EXTRA_DIST = pantest.sh

AM_CXXFLAGS = $(JACK_CFLAGS) $(SNDFILE_CFLAGS) -I$(top_srcdir)/lib

LIQUIDSFZ_LIBS = $(top_builddir)/lib/libliquidsfz.la $(SNDFILE_LIBS)

liquidsfz_SOURCES = liquidsfz.cc
liquidsfz_LDADD = $(LIQUIDSFZ_LIBS) $(JACK_LIBS)
