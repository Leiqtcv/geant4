# $Id: GNUmakefile 66356 2012-12-18 09:02:32Z gcosmo $
# --------------------------------------------------------------------
# GNUmakefile for analysis/hntools sub-library.
# --------------------------------------------------------------------

name := G4hntools

ifndef G4INSTALL
  G4INSTALL = ../../..
endif

include $(G4INSTALL)/config/architecture.gmk

CPPFLAGS += -I$(G4BASE)/global/management/include \
            -I$(G4BASE)/intercoms/include \
            -I$(G4BASE)/analysis/g4tools/include \
            -I$(G4BASE)/analysis/management/include

include $(G4INSTALL)/config/common.gmk
