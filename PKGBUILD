pkgname=adilhyz-icons
pkgver=1.0
pkgrel=2
pkgdesc="Icons For Needs"
arch=('any')
url="https://github.com/adilhyz-icons"
license=('GPL3')

prepare() {

	cp -af ../icons/. ${srcdir}

}

package() {

	local icon_dir=${pkgdir}/usr/share/icons
	mkdir -p "$icon_dir"
	cp -r ${srcdir}/* "$icon_dir"

}
