# Maintainer: Panda <panda@rebornos.org>

pkgname=rebornos-openbox-skel
pkgdesc="Skeleton for /home used for fixing openbox"
pkgver=1.0
pkgrel=1
arch=('any')
url="https://github.com/RebornOS-Developers/rebornos-openbox-skel/"
license=('GPL2')
source=("menu.xml"
        "autostart"
        "volumeicon")

sha256sums=('df6e8f65586769d4eec183ab7def45f1aad40c04b8ff8b54850569dafaf93b65'
            '6ff2168baaffc43357eeaa4bd3374c1a34543ae203a58893182f75ce302359e3'
            '9ceed69a8cfcf794b13fb1cc70e8a742b41e79f2da0fadd350e528f55de960c3')

package() {
    install -D -m644 "autostart" "${pkgdir}/etc/skel/.config/openbox/autostart"
    install -D -m644 "menu.xml" "${pkgdir}/etc/skel/.config/openbox/menu.xml"
    install -D -m644 "volumeicon" "${pkgdir}/etc/skel/.config/volumeicon/volumeicon"

}

