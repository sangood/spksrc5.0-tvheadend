PKG_NAME = uriparser
PKG_VERS = 0.8.0.1
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://downloads.sourceforge.net/project/uriparser/Sources/0.8.0.1
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)


DEPENDS =
GNU_CONFIGURE = 1
HOMEPAGE = http://uriparser.sourceforge.net/ 
COMMENT  = uriparser is a strictly RFC 3986 compliant URI parsing and handling library written in C. uriparser is cross-platform, fast, supports Unicode and is licensed under the New BSD license. 
LICENSE  =

CONFIGURE_ARGS = --disable-doc --disable-test --enable-static --prefix=$(INSTALL_PREFIX)

include ../../mk/spksrc.cross-cc.mk

