
SUBDIRS = pgn-extract chesslib/src grackle crow jay 


all: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@ $(MAKEOPTS) $(MAKECMDGOALS)


build: grackle


.PHONY: $(SUBDIRS) build

