pkgname=soraos-cinnamon
pkgver=1.2
pkgrel=1
pkgdesc="Cinnamon settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-cinnamon.gschema.override')
sha256sums=('75140d948d42bf3a5e1f842bfd342624e3082d34cbd2097aca117260822e1015')

package() {
	install -Dm644 "${srcdir}/99_soraos-cinnamon.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-cinnamon.gschema.override"
}
