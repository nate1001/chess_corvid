
SUBDIRS = pgn-extract chesslib/src grackle crow jay 


all: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@ $(MAKEOPTS) $(MAKECMDGOALS)


build: grackle

data: crow


.PHONY: $(SUBDIRS) build

