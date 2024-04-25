pkgname=soraos-cinnamon
pkgver=1.2
pkgrel=1
pkgdesc="Cinnamon settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-cinnamon.gschema.override')
sha256sums=('5db52c7584a90fc97a1813b302c4fc3f3f41f3b8ee3804c429fd27081161853d')

package() {
	install -Dm644 "${srcdir}/99_soraos-cinnamon.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-cinnamon.gschema.override"
}
