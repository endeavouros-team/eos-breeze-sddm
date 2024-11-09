# Maintainer: endeavouros-team <info[at]endeavouros.com>

pkgname=eos-breeze-sddm
pkgver=1.0
pkgrel=1
pkgdesc="EndeavourOS SDDM theme for KDE plasma based on breeze."
arch=('any')
url="https://github.com/killajoe/eos-breeze-sddm"
license=('CC-BY-SA-4.0')
depends=('qt5-graphicaleffects' 'qt5-quickcontrols2' 'qt5-svg' 'sddm')
source=("${pkgname}-${pkgver}.tar.gz::${url}/archive/${pkgver}.tar.gz")
md5sums=('1e2c2d76cc372a635e593d67fd1e553d')

package() {
  mkdir -p "${pkgdir}/usr/share/sddm/themes"
  cp -a "${srcdir}/eos-breeze-sddm-${pkgver}/src" "${pkgdir}/usr/share/sddm/themes/eos-breeze/"
}
