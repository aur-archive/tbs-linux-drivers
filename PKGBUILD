# tbs-linux-drivers: Installer: Arch
# Maintainer: Marko Paasila <marko@paasila.fi>
pkgname=tbs-linux-drivers
pkgver=v121119
pkgrel=1
pkgdesc="Firmware for TBS DVB receivers"
arch=('any')
url="http://www.tbsdtv.com/products/tbs5980-dvb-s2-ci-tv-tuner-usb.html"
license=('unknown')
depends=(linux linux-firmware)
#makedepends=()
optdepends=('Utilities: linuxtv-dvb-apps''Zap tool: szap-s2''Scan tool: scan-s2''DVB Streaming: dvblast''Another scan tool: w_scan')
source=(http://www.tbsdtv.com/download/document/common/tbs-linux-drivers_v121119.zip)
#noextract=()
md5sums=('4bd5849a31c523c3eca526094eccbff2')

#build() {
#  cd "$srcdir"
#  tar xjvf linux-tbs-drivers.tar.bz2
#  cd "$srcdir/linux-tbs-drivers"
#  make
#}

package() {
  mkdir -p "$pkgdir"/usr/lib/firmware/
#  make DESTDIR="$pkgdir/" install
  install -D -m 644 "dvb-fe-cx24116.fw" "$pkgdir/usr/lib/firmware/dvb-fe-cx24116.fw"
  install -D -m 644 "dvb-usb-tbsqbox-dvbc.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-dvbc.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5680.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5680.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5880.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5880.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5910.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5910.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5920.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5920.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5921.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5921.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5922.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5922.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5925.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5925.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5928.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5928.fw"
  install -D -m 644 "dvb-usb-tbsqbox-id5980.fw" "$pkgdir/usr/lib/firmware/dvb-usb-tbsqbox-id5980.fw"
  install -D -m 644 "v4l-cx23885-avcore-01.fw" "$pkgdir/usr/lib/firmware/v4l-cx23885-avcore-01.fw"
}
