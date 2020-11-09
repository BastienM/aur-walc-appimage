# Maintainer: Bastien Mennesson <bastien.mennesson@pm.me>
pkgname=walc-appimage
pkgver=0.1.11
pkgrel=1

pkgdesc="An unofficial WhatsApp Desktop client for linux systems."
arch=('any')
url="https://github.com/cstayyab/WALC.git"
license=('MIT')
depends=('appimage-git')
noextract=("WALC.AppImage")
options=("!strip")
source=("https://github.com/cstayyab/WALC/releases/download/v${pkgver}-Post/WALC.AppImage")
sha256sums=("66e22c1f64bbd848e5b1d1fd76ca69dc84d5860118c13ccf8e659b3915312573")

package() {
    install -Dm755 "${srcdir}/WALC.AppImage" "${pkgdir}/opt/appimages/WALC.AppImage"
}

