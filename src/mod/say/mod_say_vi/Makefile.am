include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_say_vi

mod_LTLIBRARIES = mod_say_vi.la
mod_say_vi_la_SOURCES  = mod_say_vi.c
mod_say_vi_la_CFLAGS   = $(AM_CFLAGS)
mod_say_vi_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_say_vi_la_LDFLAGS  = -avoid-version -module -no-undefined -shared
