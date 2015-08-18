# Maintainer:  Xroot <dr.xroo@yandex.ru>

pkgname=xmpv
pkgver=0.1.5
pkgrel=1
pkgdesc='Add-in for player MPV'
arch=('i686' 'x86_64')
license=('GPL')
groups=multimedia
depends=('mpv>=0.4.1')
url='https://github.com/Xr00t/xmpv'
install=xmpv.install
source=('https://github.com/Xr00t/xmpv/archive/master.zip')
md5sums=('SKIP')

package() 
{
  install -Dm755 "$srcdir/xmpv-master/xmpv" "$pkgdir/usr/bin/xmpv"
  install -Dm755 "$srcdir/xmpv-master/xmpv.desktop" "$pkgdir/usr/share/applications/xmpv.desktop"
}
