# Maintainer: Bradley S Mayes <bradleymayes@gmail.com>
pkgname=shcolors
pkgver=1.0
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
sha256sums=('68e96a1cdd5dc1bff4043ba4aa2fe8f9a54a31d1b27ca380fb83610562166455')

package() {
	cd "$srcdir/"
  mkdir -p "$pkgdir/usr/bin/"
  cp shcolors "$pkgdir/usr/bin/"
}
