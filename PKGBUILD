pkgname=2gis-omsk
pkgver=123
pkgrel=1
pkgdesc="Map of Omsk for 2GIS, November 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/omsk/products/download#linux"
license=('custom')
depends=('2gis>=3.14.9.0')
source=("http://download.2gis.com/arhives/2GISData_Omsk-123.orig.zip")
md5sums=('1220f9532d6f5d4aebf2a386cb9667dc')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Omsk.dgdat" "${pkgdir}/opt/2gis/2gis-omsk.dgdat" || return 1
  
}
