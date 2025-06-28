# Maintainer: Hanashiko <hlichisper@gmail.com>
pkgname=routekit
pkgver=0.1.0
pkgrel=1
pkgdesc="A tool for managing and visualizing network routes"
arch=('any')
url="https://github.com/Hanashiko/routekit"
license=('MIT')
depends=('python' 'iproute2')
makedepends=('git')
source=("$pkgname-$pkgver.tar.gz::https://github.com/Hanashiko/$pkgname/archive/v$pkgver.tar.gz")
sha256sums=('SKIP')

build() {
    cd "$srcdir/$pkgname-$pkgver"
    python -m py_compile routekit
}

check() {
    cd "$srcdir/$pkgname-$pkgver"
    python routekit --help > /dev/null
}

package() {
    cd "$srcdir/$pkgname-$pkgver"
    
    install -Dm755 routekit "$pkgdir/usr/bin/routekit"
    
}