pkgname=soraos-cinnamon
pkgver=1.0
pkgrel=1
pkgdesc="Cinnamon settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-cinnamon.gschema.override')
sha256sums=('9ebb4697778d13b13b2ac736df8bca5563668ab41a735c4cbe82baa9c646ea6a')

package() {
	install -Dm644 "${srcdir}/99_soraos-cinnamon.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-cinnamon.gschema.override"
}
