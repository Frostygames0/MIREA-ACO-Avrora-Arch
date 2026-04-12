# Maintainer: Ivan <HIDDEN>
pkgname=mirea-aco-avrora-bin
pkgver=1.0.0
pkgrel=1
pkgdesc="ASO Avrora for OOP course in RTU MIREA"
arch=('x86_64')
url="https://mirea.aco-avrora.ru/"
license=('unknown')
depends=(
	'qt5-webengine'
	'qt5-webchannel'
	'qt5-declarative'
	'gcc-libs'
	'glibc'
)
source=("https://mirea.aco-avrora.ru/new/ARM_Student.tgz"
		'ARM_Student.desktop'
		'ARM_Student.png')
sha256sums=('SKIP'
			'SKIP'
			'SKIP')

package() {
  install -Dm755 "$srcdir/Student_ARM/data/ARM_Student" "$pkgdir/usr/bin/ARM_Student"
  install -Dm644 "$srcdir/ARM_Student.desktop" "$pkgdir/usr/share/applications/ARM_Student.desktop"
  install -Dm644 "$srcdir/ARM_Student.png" "$pkgdir/usr/share/icons/hicolor/256x256/apps/ARM_Student.png"
}
