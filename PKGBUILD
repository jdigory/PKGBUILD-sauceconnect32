# Maintainer: Josh Lavin <arch jlavin com>
pkgname=sauceconnect32
pkgver=4.3.5
pkgrel=1
pkgdesc='32-bit utility for Sauce Labs testing'
arch=('i686')
url='https://docs.saucelabs.com/reference/sauce-connect/'
license=('unknown')
source=("https://saucelabs.com/downloads/sc-${pkgver}-linux32.tar.gz")
md5sums=('9afc50caf7a14064a1d70ffd91c8ad86')

package() {
  cd "${srcdir}/sc-${pkgver}-linux32/"
  install -D -m755 "bin/sc" "${pkgdir}/usr/bin/sc"

  # License
  install -D -m644 "license.html" "${pkgdir}/usr/share/licenses/sauceconnect32/license.html"
}
