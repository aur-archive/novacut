# Maintainer: Hilton Medeiros <medeiros.hilton@gmail.com>

pkgname=novacut
pkgver=12.04.0
pkgrel=1
pkgdesc="A collaborative video editor."
arch=('any')
url="https://launchpad.net/novacut/"
license=('AGPL3')
depends=('python' 'python-gobject' 'gstreamer0.10-python' 'python-userwebkit' 'python-microfiber')
source=("https://launchpad.net/$pkgname/trunk/12.04/+download/$pkgname-$pkgver.tar.gz")
md5sums=('e699524be72b4c0d219c7bd026a093c8')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python setup.py install --prefix=/usr --root="$pkgdir" -O1
}
