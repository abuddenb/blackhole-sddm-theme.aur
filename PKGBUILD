pkgname=blackhole-sddm-theme
pkgver=0.1.5ab
pkgrel=1
pkgdesc='Modified Chili theme for SDDM'
arch=('i686' 'x86_64')
url="https://github.com/abuddenb/blackhole-sddm-theme"
license=('GPL3')
depends=(qt5-graphicaleffects qt5-quickcontrols sddm)
install="$pkgname.install"
source=("${url}/archive/${pkgver}.tar.gz")
sha256sums=('b139860e7be899d741bb992dcece8f3be99cf7ecddc535bad75d93427e4ec947')

package() {
    mkdir -p "${pkgdir}/usr/share/sddm/themes"
    cp -r "${srcdir}/blackhole-sddm-theme-${pkgver}" "${pkgdir}/usr/share/sddm/themes/blackhole"
}
