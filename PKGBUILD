# Contributor: Daniel Leining <daniel@the-beach.co>

pkgname=cinnamon-theme-zukitwo
pkgver=1.5
pkgrel=1
pkgdesc="Zukitwo theme for Cinnamon."
arch=('any')
url="http://cinnamon-spices.linuxmint.com/themes/view/88"
license=('unknown')
depends=('cinnamon')
optdepends=('zukitwo-themes: zukitwo gtk themes')
source=(http://cinnamon-spices.linuxmint.com/uploads/themes/HCG5-KDGD-EPF1.zip)
sha1sums=('14bdadef4441a3e974665782834753d61a621fcc')

package() {
    find "Zukitwo" -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/themes/{}" \;
}
