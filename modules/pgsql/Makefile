# Copyright (c) 2003-2004 E. Will et al.
# Rights to this code are documented in doc/LICENSE.
#
# This file contains build instructions.
#
# $Id: Makefile.in 8375 2007-06-03 20:03:26Z pippijn $
#

MODULE = pgsql

SRCS = $(shell find $(SOURCEDIR) -name '*.c')

include ../../extra.mk
include ../../buildsys.mk
include ../../buildsys.module.mk

LIBS +=	-L../../libathemecore -lathemecore -lpq ${LDFLAGS_RPATH}
CPPFLAGS += -DPG_MODULE_INTERNAL -Iinclude -I../../include
