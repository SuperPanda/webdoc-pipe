pkgname=webdoc-pipe
pkgver=0.1.0
pkgrel=1
pkgdesc='Serve piped HTML/CSS/JS as a local HTTP document'
arch=('x86_64')
url='https://code.pandasportal.net/panda/webdoc-pipe'
license=('WTFPL')
depends=('rust-script')
source=("${pkgname}-${pkgver}.tar.gz::https://code.pandasportal.net/panda/${pkgname}/archive/v${pkgver}.tar.gz")
sha256sums=('55a5118fba23bef5199080be47b0ca04807b6b98b490c96e126ba75a504e003b')

package() {
  cd "${srcdir}/${pkgname}"
  install -Dm755 bin/webdoc-pipe "${pkgdir}/usr/bin/webdoc-pipe"
}
