PKG_NAME = libav
PKG_VERS = 0.8.13
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.libav.org/releases
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/openssl cross/zlib cross/lame cross/x264 cross/faac

HOMEPAGE = http://www.libav.org/ 
COMMENT = Libav has always been a very experimental and developer-driven project. It is a key component in many multimedia projects and has new features added constantly. Development branch snapshots work really well 99% of the time so people are not afraid to use them.
LICENSE  =
#GNU_CONFIGURE = 1
CONFIGURE_ARGS = --enable-ssse3  --enable-runtime-cpudetect --enable-hardcoded-tables --enable-yasm  --enable-decoder=ac3  --enable-encoder=ac3  --enable-encoder=ac3_fixed  --enable-decoder=ac3_fixed  --enable-optimizations  --disable-doc --disable-avplay --disable-avprobe  --disable-avconv  --enable-version3  --enable-gpl --enable-libx264 --enable-libfaac --enable-libmp3lame --enable-nonfree --enable-cross-compile --arch=$(ARCH) --target-os=linux --cross-prefix=$(TC_PATH)$(TC_PREFIX) --prefix=$(INSTALL_PREFIX) --extra-cflags="-I$(WORK_DIR)/install$(INSTALL_PREFIX)/include" --extra-ldflags="-L$(WORK_DIR)/install$(INSTALL_PREFIX)/lib" --extra-libs=-ldl

#CONFIGURE_ARGS = --enable-libmp3lame --disable-doc --enable-libx264  --disable-avplay --disable-avprobe  --disable-avconv --disable-yasm --enable-optimizations --disable-altivec --enable-pic --enable-shared --disable-static --disable-swscale-alpha --enable-nonfree --enable-version3 --enable-gpl --enable-cross-compile --arch=$(ARCH) --target-os=linux --cross-prefix=$(TC_PATH)$(TC_PREFIX) --prefix=$(INSTALL_PREFIX) --extra-cflags="-I$(WORK_DIR)/install$(INSTALL_PREFIX)/include" --extra-ldflags="-L$(WORK_DIR)/install$(INSTALL_PREFIX)/lib" --extra-libs=-ldl 
INSTALL_TARGET = myInstall

include ../../mk/spksrc.cross-cc.mk


.PHONY: myInstall
myInstall:
	$(RUN) make install DESTDIR=$(INSTALL_DIR)
