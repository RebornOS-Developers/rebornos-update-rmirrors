# Maintainer: Rafael from RebornOS

pkgname=rebornos-update-rmirrors
_pkgname=update-rmirrors
pkgver=20210504
pkgrel=1
pkgdesc="Copy reborn-mirrorlist.pacnew to reborn-mirrorlist"
arch=('any')
url='https://github.com/RebornOS-Developers/rebornos-update-rmirrors'
license=('GPL2')
source=("${_pkgname}")
sha512sums=('b91411b50308e2b636d35773b4b86533d5789ccf3d35c03b31d30236afe8af227957ead803be8fb21a68d34f09b523aad00461936231ee6c48fdd60d2cf33576')

pkgver() {
    date +%Y%m%d
}

package() {
  install -Dm 755 "${srcdir}/${_pkgname}" "${pkgdir}/usr/bin/${_pkgname}"
  chmod u+x ${pkgdir}/usr/bin/${_pkgname}
}

