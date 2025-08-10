# Maintainer: killown <24453+killown@users.noreply.github.com>
pkgname=swwwv
pkgver=1.0.0
pkgrel=1
pkgdesc="Simple GTK4 image viewer with swww wallpaper integration"
arch=('x86_64')
license=('MIT')
depends=('python' 'python-gobject' 'gtk4' 'swww')
source=('swwwv'
  'swwwv.desktop')
noextract=()
md5sums=('SKIP'
  'SKIP')

package() {
  install -Dm755 "${srcdir}/swwwv" "${pkgdir}/usr/bin/swwwv"
  install -Dm644 "${srcdir}/swwwv.desktop" "${pkgdir}/usr/share/applications/swwwv.desktop"
}
