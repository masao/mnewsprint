## Process this file with automake to produce Makefile.in

## This is a part of mnewsprint
## Copyright (C) 2001, Masao Takaku. All rights reserved.

bin_SCRIPTS =	mnewsprint
man_MANS =	mnewsprint.1

EXTRA_DIST =	$(man_MANS)

$(man_MANS):	configure.in
	pod2man --center="$(PACKAGE)" --release="$(PACKAGE) $(VERSION)" \
		mnewsprint > mnewsprint.1
