# Maintainer: dllud <dllud riseup net>

pkgname=ttf-indieflower
# fc-query -f '%{fontversion[0]}\n' IndieFlower-Regular.ttf
pkgver=65602
pkgrel=1
pkgdesc="Handwriting sans-serif font with bubbly and rounded edges from Google Fonts."
url="https://fonts.google.com/specimen/Indie+Flower"
license=("OFL")
arch=("any")
source=("$pkgname-$pkgver.zip::https://fonts.google.com/download?family=Indie%20Flower")
b2sums=("SKIP")

package() {
  install -Dm644 -t "$pkgdir/usr/share/fonts/TTF" "${srcdir}/IndieFlower-Regular.ttf"
  install -Dm644 -t "$pkgdir/usr/share/licenses/$pkgname" "${srcdir}/OFL.txt"
}
