MODULE_TOPDIR = ../../..

PGM = r.pi.nlm

LIB_NAME = grass_rpi
RPI_LIB  = -l$(LIB_NAME)

LIBES = $(STATSLIB) $(GISLIB) $(RPI_LIB)
DEPENDENCIES = $(STATSDEP) $(GISDEP)

include $(MODULE_TOPDIR)/include/Make/Module.make

default: cmd
