pkgname=dropbox-plasma-dark-icons-git
_pkgname=dropbox-plasma-dark-icons
pkgver=1
pkgrel=1
pkgdesc="Dropbox icons for Plasma 5 Dark Panels"
arch=('any')
url="https://github.com/x11tete11x/dropbox-plasma-dark-icons"
license=('GPL')
depends=('hicolor-icon-theme' 'dropbox')
conflicts=('dropbox-kfilebox-icons'
           'dropbox-plasma-light-icons')           
source=(git://github.com/x11tete11x/dropbox-plasma-dark-icons.git)
md5sums=(SKIP)
install="dropbox-plasma-dark-icons.install"

package(){
  install -d "${pkgdir}/usr/share/icons/hicolor/"
  cp -r ${srcdir}/${_pkgname}/icons/* "${pkgdir}/usr/share/icons/hicolor/"
}
