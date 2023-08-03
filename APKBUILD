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
703c473e3631fff07072ff232ed94b3fe15aa6b263292e2b09b27d21f729059ef42960ea60efa4000ef7f748c074d7395011956b60f4e8c02fef8ffb0b2cd295  17g-$pkgver.tar.bz2
"
