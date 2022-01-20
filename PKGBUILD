# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    PKGBUILD                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: Lanhild <archlan@protonmail.com>           +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/01/19 13:10:20 by Lanhild           #+#    #+#              #
#    Updated: 2022/01/20 16:59:26 by Lanhild          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

pkgname=archlan-de
pkgver=1.0
pkgrel=1
pkgdesc="ArchLan desktop environment"
url="https://github.com/archlan/archlan-de"
arch=('any')
license=('GPL3')
makedepends=()
depends=()
conflicts=()
groups=('archlan-de')
provides=("${pkgname}")
options=(!strip !emptydirs)

prepare() {
    cp -af ../files/. ${srcdir}
}

package() {
	install -Dm 755 archlan-de   	    ${pkgdir}/usr/local/bin/archlan-de
	install -Dm 644 archlan-de.desktop	${pkgdir}/usr/share/applications/archlan-de.desktop
}