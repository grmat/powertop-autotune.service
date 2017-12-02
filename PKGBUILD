# Maintainer: grmat <grmat@sub.red>

pkgname=powertop-service
pkgdesc="Systemd unit that runs powertop with auto-tune settings."
pkgver=1.0
pkgrel=2
arch=('any')
license=('GPL')
depends=('systemd' 'powertop')

source=('powertop-autotune.service')
sha256sums=('9a83e95f87bcceb94eee265ced56dd69d61c62cdfb0ecb8465599a54c619795c')

package() {
    mkdir -p ${pkgdir}/usr/lib/systemd/system
    cp ${srcdir}/powertop-autotune.service ${pkgdir}/usr/lib/systemd/system/
}
