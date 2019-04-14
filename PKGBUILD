# Maintainer: Jake Howard <git+aur@theorangeone.net>
pkgname=pranklock
pkgver=0.1.0
pkgrel=0
pkgdesc="Fake lock screen to capture intruders"
license=('unknown')
depends=('ffmpeg' 'i3lock' 'xdotool')
url="https://github.com/RealOrangeOne/pranklock"
arch=('any')
source=("$pkgver.tar.gz::https://github.com/RealOrangeOne/pranklock/archive/$pkgver.tar.gz")
sha512sums=('SKIP')

package() {
    cd $pkgname-$pkgver
    install -D -m755 "pranklock" "$pkgdir/usr/bin/pranklock"
}
