PKG_NAME = yasm
PKG_VERS = 1.2.0
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.tortall.net/projects/yasm/releases
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)


DEPENDS =
GNU_CONFIGURE = 1 
HOMEPAGE = http://yasm.tortall.net/
COMMENT  = Yasm currently supports the x86 and AMD64 instruction sets, accepts NASM and GAS assembler syntaxes, outputs binary, ELF32, ELF64, 32 and 64-bit Mach-O, RDOFF2, COFF, Win32, and Win64 object formats, and generates source debugging information in STABS, DWARF 2, and CodeView 8 formats. 
LICENSE  =

CONFIGURE_ARGS = --prefix=$(INSTALL_PREFIX)

include ../../mk/spksrc.cross-cc.mk

