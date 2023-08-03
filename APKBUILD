# Contributor: aliriza keskin <aliriza.keskin@pardus.org.tr>
# Maintainer: aliriza keskin <aliriza.keskin@pardus.org.tr>
pkgname=17g-installer
pkgver=4.4.2
pkgrel=0
pkgdesc="17g installer"
url="https://gitlab.com/ggggggggggggggggg/17g"
arch="all"
license="GplV3"
depends="python3 py3-yaml py3-gobject3 py3-pyparted tzdata util-linux coreutils rsync gparted setxkbmap py3-defusedxml"
makedepends="make gettext"
checkdepends=""
install=""
source="https://gitlab.com/ggggggggggggggggg/17g/-/archive/$pkgver/17g-$pkgver.tar.bz2"
builddir="$srcdir/17g-$pkgver"

build() {
	make
}


package() {
	make DESTDIR="$pkgdir" install
}

sha512sums="
2f5a494300c1676770c7ad21da6cdb0f1b62350aecf8705f839ccb82968361b68889e245fa98ce455e6242a2cf8ee50cebf2b666a16277785da7718bccfe36b6  17g-$pkgver.tar.bz2
"
