all: osi_bas

osi_bas: tmpdir
	echo $@
	ca65 --feature force_range -D $@ osi_bas.s -o tmp/$@.o
	ld65 -o tmp/$@.bin -C $@.cfg tmp/$@.o -Ln tmp/$@.lbl

tmpdir:
	test ! -e tmp/ && mkdir tmp/
