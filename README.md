# README

My raku-zef macports Portfile.

# INSTALL

This isn't an official port yet. When it is:

    sudo port install raku-zef

Until then, you need your own set of ports to install this from:

    cd ~/src
	git clone https://github.com/macportsraf/raku-zef-portfile
	mkdir ~/ports
	cp -pr raku-zef-portfile/lang ~/ports
	rm -rf raku-zef-portfile
	cd ~/ports
	portindex
	echo file://$(pwd) >> /opt/local/etc/macports/sources.conf

