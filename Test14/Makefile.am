AUTOMAKE_OPTIONS = subdir-objects

bin_PROGRAMS = hello

hello_SOURCES = src/sources/main.c

AM_CPPFLAGS = -Isrc/include

hello_LDADD = ./src/libhello.la

hello_LDFLAGS = -static
