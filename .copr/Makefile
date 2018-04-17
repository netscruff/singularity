srpm:
	dnf -y install libtool automake python2-devel -y
	./autogen.sh
	./configure
	make dist
	rpmbuild -ts singularity-*.tar.gz
