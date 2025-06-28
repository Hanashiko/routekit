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
provides=('routekit')
conflicts=('routekit')
source=("routekit")
sha256sums=('SKIP')

package() {
    install -Dm755 "$srcdir/routekit" "$pkgdir/usr/bin/routekit"
}