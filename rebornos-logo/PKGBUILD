# Maintainer: rafael-uy from RebornOS

pkgname=rebornos-logo
pkgver=1.0
pkgrel=1.0
pkgdesc="RebornOS logo"
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-logo"
license=('GPL3')
source=('rebornos.png' 
        'rebornos.svg')
sha256sums=('9fc5ed4230af150ec9fa220a809d4c19cd5a49160465b7377d54e6bda5414aae'
            '59b4bb8c00a6200c7ee2ca0c443915450e744df2412460bbf2d41756da669261')

package() {
  mkdir -p ${pkgdir}/usr/share/pixmaps
  install -Dm644 ${srcdir}/rebornos.png ${pkgdir}/usr/share/pixmaps/
  install -Dm644 ${srcdir}/rebornos.svg ${pkgdir}/usr/share/pixmaps/
}
 
