#########################################################################
#                                                                       #
# Copyright 2014 Adobe Systems Incorporated.                       #
# All rights reserved.                                                  #
#                                                                       #
#########################################################################

# Configuration
CONFIG = release
CFLAGS = $(STD_OPTS)

# Library
ROOT_DIR = $(realpath ../../../../..)
SRC_DIR = $(ROOT_DIR)/source/cffread

# Library
SRC_DIR = $(ROOT_DIR)/source/cffread
LIB_SRCS = $(SRC_DIR)/cffread.c
LIB_OBJS = cffread.o
LIB_TARGET = $(LIB_DIR)/cffread.a

# Build targets
TARGETS = $(LIB_TARGET)

# Standard definitions
include $(realpath ../../../../../config/linux/gcc/gcc_tx.mak)

# Object rules
# Object rules
cffread.o:
	$(CC) $(CFLAGS) -c $(SRC_DIR)/cffread.c -o $@
