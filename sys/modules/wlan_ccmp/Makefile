# $FreeBSD$

.PATH: ${.CURDIR}/../../net80211
.PATH: ${.CURDIR}/../../crypto/rijndael

KMOD=	wlan_ccmp
SRCS=	ieee80211_crypto_ccmp.c
SRCS+=	rijndael-alg-fst.c rijndael-api.c
SRCS+=	opt_wlan.h

.include <bsd.kmod.mk>
