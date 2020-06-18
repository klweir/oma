Bootstrap: docker
From: ubuntu:20.04

%post
	apt-get update && \
    sudo apt-get install \
    python

	wget -O oma.tgz https://omabrowser.org/standalone/OMA.2.4.1.tgz
	tar xvzf oma.tgz
	cd OMA.2.4.1
	./install.sh
	export PATH=$PATH:usr/local/OMA/bin
