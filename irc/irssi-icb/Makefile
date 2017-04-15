# $FreeBSD$

PORTNAME=	irssi-icb
PORTVERSION=	0.17
DISTVERSIONPREFIX=v
CATEGORIES=	irc

MAINTAINER=	santhosh.raju@gmail.com
COMMENT=	Irssi plugin for connecting to ICB network

LICENSE=	GPLv2
LICENSE_FILE=	${WRKSRC}/COPYING

BUILD_DEPENDS=	${LOCALBASE}/include/irssi/src/common.h:irc/irssi:irc/irssi
RUN_DEPENDS=	irssi:irc/irssi

USES=		autoreconf libtool pkgconfig
USE_LDCONFIG=	yes
USE_GNOME=	glib20

USE_GITHUB=	yes
GH_ACCOUNT=	mglocker
GH_PROJECT=	irssi-icb
GH_TAGNAME=	c4e2ea8

GNU_CONFIGURE=	yes
CONFIGURE_ARGS= --with-irssi=${LOCALBASE}/include/irssi --disable-static
INSTALL_TARGET=	install-strip

PLIST_FILES=	lib/irssi/modules/libicb_core.so \
		lib/irssi/modules/libfe_icb.so

.include <bsd.port.mk>
