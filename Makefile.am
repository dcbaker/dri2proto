dri2dir = $(includedir)/X11/extensions
dri2_HEADERS = include/X11/extensions/dri2proto.h include/X11/extensions/dri2tokens.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = dri2proto.pc

dist_doc_DATA = dri2proto.txt


MAINTAINERCLEANFILES = ChangeLog INSTALL

.PHONY: ChangeLog INSTALL

INSTALL:
	$(INSTALL_CMD)

ChangeLog:
	$(CHANGELOG_CMD)

dist-hook: ChangeLog INSTALL
