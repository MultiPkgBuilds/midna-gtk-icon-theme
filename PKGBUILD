pkgname=midna-gtk-icon-theme
pkgver=1.0
pkgrel=1
pkgdesc='gtk icon theme pack for midna'
arch=('x86_64')
url='https://github.com/Gabrielgtx/midna-gtk-icon-theme'
depends=('midna-themes')
optdepends=('breeze-gtk: enhanced management for themes gtk 2 and 3')
license=('CUSTOM')
source=("https://github.com/Gabrielgtx/${pkgname}/archive/${pkgver}.tar.gz")
md5sums=('SKIP')

package() {
  install -d -m 755 "$pkgdir/usr/share/icons"
  cd "$srcdir/${pkgname}-${pkgver}"
  cp -r * "$pkgdir"/usr/share/icons
}
