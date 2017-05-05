all:
	mkdir -p rootdir
	mkdir -p tmp
	echo "bogus file" > rootdir/bogus.txt

distdir:
	cp Makefile $(distdir)

mostlyclean clean distclean mainainer-clean:
	rm -r mountdir rootdir
