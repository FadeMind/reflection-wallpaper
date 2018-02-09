# Maintainer: FadeMind <fademind@gmail.com>

pkgname=reflection-wallpaper
pkgver=20170120
pkgrel=1
pkgdesc="Reflection wallpaper"
url="https://github.com/FadeMind/${pkgname}"
arch=('any')
license=('GPL')
makedepends=('make')
options=('!strip')
source=(${pkgname}-master.zip)
sha256sums=('8f12f44bceb518277055ff19d62a3d6f0ffa3b1cf8df7b4d85e6450a0b80f6ba')

package() {
    make -C "${srcdir}/${pkgname}-master" install DESTDIR="$pkgdir"
}
