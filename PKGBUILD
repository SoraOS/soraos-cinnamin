pkgname=soraos-cinnamon
pkgver=1.1
pkgrel=1
pkgdesc="Cinnamon settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-cinnamon.gschema.override')
sha256sums=('e3cad4ace1b061a0f77d59ad7c2d5ec7628d3158013f040be45e4604db59c557')

package() {
	install -Dm644 "${srcdir}/99_soraos-cinnamon.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-cinnamon.gschema.override"
}
