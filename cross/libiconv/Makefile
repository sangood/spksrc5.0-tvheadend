PKG_NAME = libiconv
PKG_VERS = 1.11
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://ftp.gnu.org/pub/gnu/libiconv
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

HOMEPAGE = https://www.gnu.org/savannah-checkouts/gnu/libiconv/
COMMENT  = libiconv 1.14
LICENSE  =

GNU_CONFIGURE = 1
CONFIGURE_ARGS =  --prefix=$(INSTALL_PREFIX) --without-libiconv-prefix  

include ../../mk/spksrc.cross-cc.mk

