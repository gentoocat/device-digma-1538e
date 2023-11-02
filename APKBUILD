pkgname=device-digma-1538e-mainline
pkgdesc="Digma Plane 4G 1538E"
pkgver=1.0
pkgrel=1
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="postmarketos-base mkbootimg linux-postmarketos-mtk-mt6735"
makedepends="devicepkg-dev"
source="deviceinfo"
build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
363470dae416bf528e96b4880c3506c66162fd9be8754cae1120b43fbe33efa830e8dbb2c6541ca208e03a607496fd4e05c36150d2a47c9de4fc4631a25cf800  deviceinfo
"
