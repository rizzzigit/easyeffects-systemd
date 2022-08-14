# Maintainer: Rizzzi Git <rizzzigit@gmail.com>
pkgname="easyeffects-systemd"
pkgver=1.0
pkgrel=1
pkgdesc="Service unit file for easy effects"

arch=("any")
url="https://github.com/rizzzigit/easyeffects-systemd"
license=("MIT")

depends=("easyeffects")

package() {
  usersystemd_dir="$pkgdir/etc/systemd/user"

  if [[ ! -e $usersystemd_dir ]]
  then
    mkdir $usersystemd_dir -p
  fi

  cp easyeffects.service "$usersystemd_dir/"
}
