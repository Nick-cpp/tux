pkgname=tux-colored
pkgver=1.0
pkgrel=1
pkgdesc="Colorful Tux penguin with configurable colors"
arch=('x86_64')
url="https://thendsoft.su"
license=('GPL')
depends=('gcc-libs')
source=("tux.cpp")
md5sums=('SKIP')

build() {
    g++ -std=c++17 "$srcdir/tux.cpp" -o tux
}

package() {
    install -Dm755 tux "$pkgdir/usr/bin/tux"
}
