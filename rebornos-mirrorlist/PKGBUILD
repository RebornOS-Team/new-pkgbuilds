# Maintainer: Rafael <rafael@rebornos.org>

pkgname=rebornos-mirrorlist
filename=reborn-mirrorlist
pkgver=20221206
pkgrel=1
pkgdesc="RebornOS mirrorlist"
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-mirrorlist"
license=('GPL3')
source=(${filename})
install=${pkgname}.install
sha256sums=('2030a04a3ed693162d3b7fe77b4ec421d7c2e48c817fa73a5f46e9d40b093f06')

pkgver() {
    date +%Y%m%d
}

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -m644 ${srcdir}/${filename} ${pkgdir}/etc/pacman.d/${filename}-new
}

