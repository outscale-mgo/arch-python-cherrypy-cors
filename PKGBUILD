# Maintainer: Matthias gatto <matthias.gatto@outscale.com>
# Reference: PKGBUILD(5)

pkgname=python-cherrypy-cors
pkgver=1.6
pkgrel=1
pkgdesc='CORS support for CherryPy'

arch=('any')
url='https://github.com/yougov/cherrypy-cors'
license=(BSD)

makedepends=('python-pip')
depends=(python-cherrypy python-httpagentparser)

package() {
	PIP_CONFIG_FILE=/dev/null pip install --isolated --root="$pkgdir" --ignore-installed --no-deps cherrypy-cors==1.6
}
