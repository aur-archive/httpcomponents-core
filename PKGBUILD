# Contributor: Joel Sevilleja Febrer Joel7987[at].gmail.com
# Maintainer: Nikolay Bogoychev <nheart@gmail.com>

pkgname=httpcomponents-core
pkgver=4.4.1
pkgrel=1
pkgdesc="A HTTP/1.1 compliant HTTP agent implementation"
arch=('i686' 'x86_64')
url="http://hc.apache.org/"
license="Apache"
depends=('java-runtime')
conflicts=('')
source=(http://www.apache.org/dist/httpcomponents/httpcore/binary/${pkgname}-${pkgver}-bin.tar.gz)

package() {
	cd ${srcdir}/${pkgname}-${pkgver}/lib
	mkdir -p ${pkgdir}/usr/share/java/${pkgname}
	chmod +r *.jar
	cp *.jar $pkgdir/usr/share/java/${pkgname}
}


md5sums=('18b504839a8a915c2438f7e266a01d29')

