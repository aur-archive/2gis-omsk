pkgname=2gis-omsk
pkgver=115
pkgrel=1
pkgdesc="Map of Omsk for 2GIS, March 2014"
arch=('i686' 'x86_64')
url="http://omsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Omsk-115.orig.zip")
md5sums=('10f2ed2670716b4b87909d4d25f7e5d3')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Omsk.dgdat" "${pkgdir}/opt/2gis/omsk.dgdat" || return 1
  
}
