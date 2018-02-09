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
sha256sums=('SKIP')

package() {
    make -C "${srcdir}/${pkgname}-master" install DESTDIR="$pkgdir"
}
