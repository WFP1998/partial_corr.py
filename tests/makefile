test.out: test.in test.out.cfr
	../partial_corr.py < $< > $@
	cmp $@ $@.cfr
