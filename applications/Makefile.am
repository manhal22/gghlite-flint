AUTOMAKE_OPTIONS = foreign
AM_CFLAGS = ${DEBUG_CFLAGS} -I$(top_srcdir) -I$(top_srcdir)/dgs -fopenmp -Wall -g

# AM_LDFLAGS = -Wl,-rpath -Wl,$(abs_top_builddir)/flint

LDADD = \
    $(top_builddir)/dgs/libdgs.la \
    $(top_builddir)/oz/liboz.la \
    $(top_builddir)/gghlite/libgghlite.la \
    $(top_builddir)/dgsl/libdgsl.la \
    -lflint -lgmp -lmpfr -lm -lssl -lcrypto

#LDFLAGS = -no-install

bin_PROGRAMS =
# bin_PROGRAMS = bench_dgsl \
#                bench_prime_g \
#                bench_invert \
#                bench_rem
