# Maintainer: Kane Vanguard

pkgname=lucidsystems-config
pkgver=1.0.0
pkgrel=1
pkgdesc="LucidSystems Configuration"
arch=('any')
depends=('lucidsystems-artwork>=1.0.0' 'gtk-theme-lucidsystems')
url="https://github.com/KaneVanguard/lucidsystems-config"
license=('GPL')
install=${pkgname}.install

package() {
    cd "$pkgdir"
    mkdir -p etc
    mkdir -p usr/bin

    install -Dm755 "$srcdir/usr/bin/lucidsystems-settings.sh" usr/bin/lucidsystems-settings.sh

    cp -R "$srcdir/etc/skel" etc/skel
}
