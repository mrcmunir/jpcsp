TARGET = pooltest
OBJS = main.o fpl.o

INCDIR =
CFLAGS = -O2 -G0 -Wall
CXXFLAGS = $(CFLAGS) -fno-exceptions -fno-rtti
ASFLAGS = $(CFLAGS)

LIBDIR =
LDFLAGS =

LIBS =

EXTRA_TARGETS = EBOOT.PBP
PSP_EBOOT_TITLE = Memory Pool Sample

BUILD_PRX = 1

PSPSDK=$(shell psp-config --pspsdk-path)
include $(PSPSDK)/lib/build.mak

