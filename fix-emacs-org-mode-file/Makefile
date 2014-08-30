t:
	cp test1.org test1.org.tmp
	perl -w -i.bak org-mode-fix.pl test1.org.tmp
	-diff -u test1.org test1.org.tmp

clean:
	rm -f test1.org.tmp
	rm -f test1.org.tmp.bak
