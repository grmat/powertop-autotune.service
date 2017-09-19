# Maintainer: grmat <grmat@sub.red>

pkgname=powertop-service
pkgdesc="Systemd unit that runs powertop with auto-tune settings."
pkgver=1.0
pkgrel=1
arch=('any')
license=('GPL')
depends=('systemd' 'powertop')

source=('powertop.service')
md5sums=('e68816b58bd445f3400d5cf29c822215')

package() {
    mkdir -p ${pkgdir}/usr/lib/systemd/system
    cp ${srcdir}/powertop.service ${pkgdir}/usr/lib/systemd/system/
}
