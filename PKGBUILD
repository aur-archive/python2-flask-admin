# Maintainer: Moritz Lipp <mlq@pwmt.org>

_pkgname=Flask-Admin
pkgname=python2-flask-admin
pkgver=1.0.7
pkgrel=1
pkgdesc="Flask-Admin is simple and extensible administrative interface framework
for Flask"
arch=(any)
url="http://flask-admin.readthedocs.org"
license=('BSD')
depends=('python2' 'python2-flask')
makedepends=('python2-distribute')
source=("http://pypi.python.org/packages/source/${_pkgname:0:1}/$_pkgname/$_pkgname-$pkgver.tar.gz")
md5sums=('37153580549e3f6eeb2ddd3bc66defc7')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --prefix=/usr --optimize=1
}

# vim:set ts=2 sw=2 et:
