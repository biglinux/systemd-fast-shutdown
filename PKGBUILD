# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=systemd-fast-shutdown
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/systemd-fast-shutdown"
pkgdesc="Only change systemd configuration to wait just 3 seconds to kill application before shutdown"
source=("git+https://github.com/biglinux/systemd-fast-shutdown.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/systemd-fast-shutdown/systemd-fast-shutdown/etc/" "${pkgdir}/"
} 
