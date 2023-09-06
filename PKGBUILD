# Maintainer: Bradley S Mayes <bradleymayes@gmail.com>
pkgname=shcolors
pkgver=1.1
pkgrel=1
pkgdesc="Script to list all available shell colors on all background colors for reference"
arch=('any')
url="https://github.com/l1nuxn1nj4/shcolors"
license=('GPL')
groups=()
depends=('bash')
makedepends=('git')
provides=("${pkgname}")
conflicts=("${pkgname}")
replaces=()
backup=()
options=()
install=
source=('shcolors')
noextract=()
sha256sums=('b448f8a07ec42f928b7536a9f76b2dffc1cbd207ce714570714f12c155757373')

package() {
	cd "$srcdir/"
  mkdir -p "$pkgdir/usr/bin/"
  cp shcolors "$pkgdir/usr/bin/"
}
