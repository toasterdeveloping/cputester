# Maintainer: toasterdev <sillygeometry512@gmail.com>

pkgname=cputester
pkgver=1.0.0
pkgrel=1
pkgdesc="Terminal-based CPU emulator for testing CPU instructions and performance."
arch=('any')
url="https://github.com/toasterdeveloping/cputester"
license=('MIT')
depends=('python')
source=("cputester")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/cputester" "${pkgdir}/usr/bin/cputester"
}