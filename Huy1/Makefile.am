AUTOMAKE_OPTIONS = subdir-objects
bin_PROGRAMS = hello
hello_SOURCES = src/code/main.c src/include/lib.h src/code/hello.c src/code/hello1.c
AM_CPPFLAGS = -Isrc/include

lib_LTLIBRARIES = libhello.la
libhello_la_SOURCES = src/code/hello.c src/code/hello1.c
hello_la_CFLAGS = -fPIC
hello_LDFLAGS = -shared -fPIC
