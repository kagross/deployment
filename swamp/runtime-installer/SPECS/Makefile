# This file is subject to the terms and conditions defined in
# 'LICENSE.txt', which is part of this source code distribution.
#
# Copyright 2012-2017 Software Assurance Marketplace

.PHONY: install rpms java perl

install: rpm
rpm: java perl

java:
	rpmbuild --verbose --define '_topdir $(TOPDIR)' -bb swamp-rt-java.spec
perl:
	rpmbuild --verbose --define '_topdir $(TOPDIR)' -bb swamp-rt-perl.spec
