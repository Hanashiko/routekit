# Maintainer: Hanashiko <hlichisper@gmail.com>
pkgname=routekit
pkgver=0.1.5
pkgrel=1
pkgdesc="A tool for managing and visualizing network routes"
arch=('any')
url="https://github.com/Hanashiko/routekit"
license=('MIT')
depends=('python' 'iproute2')
makedepends=('git')
provides=('routekit')
conflicts=('routekit')
source=("routekit" "LICENSE" "README.md")
sha256sums=('464745d3b028ea08ffc281787e9a56508bb2f06c33dc2dc179c2f7ba3cc13ebc' 
            '97ad9eb02154bcf1ea19abb6b529506eb0b20df9f0aefb8b11b87af1b2c4f884' 
            'b4a40a6ef5338b4d2fb6b5c305100ce42d3ec7c9c73e95988077c14a6962f996')

package() {
    install -Dm755 "$srcdir/routekit" "$pkgdir/usr/bin/routekit"
    install -Dm644 "$srcdir/LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
    install -Dm644 "$srcdir/README.md" "$pkgdir/usr/share/doc/$pkgname/README.md"
}