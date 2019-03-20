AUTOMAKE_OPTIONS = subdir-objects

bin_PROGRAMS = hello

hello_SOURCES = src2/main.c

AM_CPPFLAGS = -Isrc

hello_LDADD = ./src/libhello.la

hello_LDFLAGS = -static
