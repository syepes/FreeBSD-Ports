# $FreeBSD$

PORTNAME=	statik
PORTVERSION=	20141020
CATEGORIES=	devel

MAINTAINER=	cheffo@freebsd-bg.org
COMMENT=	Embed static files into a Go executable

LICENSE=	APACHE20

BUILD_DEPENDS=	go:${PORTSDIR}/lang/go

ONLY_FOR_ARCHS=	i386 amd64

USE_GITHUB=	yes
GH_ACCOUNT=	rakyll
GH_PROJECT=	statik
GH_TAGNAME=	${GH_COMMIT}
GH_COMMIT=	f19d7c2

.include <bsd.port.pre.mk>
.include "${.CURDIR}/../../lang/go/files/bsd.go.mk"
.include <bsd.port.post.mk>
