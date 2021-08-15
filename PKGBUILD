# Maintainer: Bastien Mennesson <bastien.mennesson@pm.me>
pkgname=walc-appimage
pkgver=0.2.1
pkgrel=1

pkgdesc="An unofficial WhatsApp Desktop client for linux systems."
arch=('any')
url="https://github.com/WAClient/WALC.git"
license=('MIT')
depends=('appimage-git')
noextract=("WALC.AppImage")
options=("!strip")
source=("https://github.com/WAClient/WALC/releases/download/v${pkgver}/walc.AppImage")
sha256sums=("6c1e5c004e9c4bc5a8cf15837ce0e6c884fb3ace6397aa6aa95a6738c1960560")

package() {
    install -Dm755 "${srcdir}/walc.AppImage" "${pkgdir}/opt/appimages/WALC.AppImage"
}

