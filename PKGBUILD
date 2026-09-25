# Maintainer: toasterdev

pkgname=cputester
pkgver=1.0.0
pkgrel=1
pkgdesc="Terminal-based CPU emulator for testing CPU instructions."
arch=('any')
url="https://github.com/toasterdeveloping/cputester"
license=('MIT')
depends=('python')
source=("$pkgname-$pkgver.tar.gz::https://github.com/toasterdeveloping/cputester/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('SKIP')

package() {
    install -Dm755 "$srcdir/$pkgname-$pkgver/cputester" \
        "$pkgdir/usr/bin/cputester"
}
