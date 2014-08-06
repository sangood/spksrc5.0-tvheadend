PKG_NAME = faac
PKG_VERS = 1.28
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://downloads.sourceforge.net/faac
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)


DEPENDS =
GNU_CONFIGURE = 1
HOMEPAGE = http://www.audiocoding.com/faac.html
COMMENT  = FAAC is an MPEG-4 and MPEG-2 AAC encoder.Note that the quality of FAAC is not up to par with the currently best AAC encoders available.
LICENSE  =

CONFIGURE_ARGS = --enable-static --prefix=$(INSTALL_PREFIX)

include ../../mk/spksrc.cross-cc.mk

