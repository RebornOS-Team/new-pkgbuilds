# Maintainer: Panda <panda@rebornos.org>

pkgname=rebornos-kde-skel
pkgdesc="Skeleton for /home used for fixing KDE"
pkgver=1.1
pkgrel=1
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-kde-skel/"
license=('GPL2')
source=("plasma-org.kde.plasma.desktop-appletsrc")

sha256sums=('fca1b0878198c2396bf013424d04ce53cd4e2bb0eb43ef942899e5c4dbe361a1')

package() {
    install -D -m644 "plasma-org.kde.plasma.desktop-appletsrc" "${pkgdir}/etc/skel/.config/plasma-org.kde.plasma.desktop-appletsrc"
}