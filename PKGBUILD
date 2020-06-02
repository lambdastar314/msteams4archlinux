# https://packages.microsoft.com/repos/ms-teams/pool/main/t/teams/teams_1.3.00.5153_amd64.deb
pkgname='microsoft-teams'
pkgver='1.3.00.5153'
pkgrel=1
plgdesc='A chat-centered workspace in Office 365'
arch=('x86_64')
url='https://www.microsoft.com/en-us/microsoft-365/microsoft-teams/group-chat-software'
license=('custom')
depends=('alsa-lib' 'at-spi2-atk' 'cairo' 'libcups' 'expat' 'gdk-pixbuf2' 'glib2' 'gtk3' 'nspr' 'nss' 'pango' 'libsecret' 'libx11' 'libxcb' 'libxcomposite' 'libxcursor' 'libxdamage' 'libxext' 'libxfixes' 'libxi' 'libxkbfile' 'libxrandr' 'libxrender' 'libxss' 'libxtst' 'fontconfig' 'dbus' 'gcc-libs')
# source=("https://packages.microsoft.com/repos/ms-teams/pool/main/teams/teams_${pkgver}_amd64.deb")
source=("https://packages.microsoft.com/repos/ms-teams/pool/main/t/teams/teams_1.3.00.5153_amd64.deb")
md5sums=('163bf38af0c0300b647452fb5abebda6')

package(){
    tar -xf data.tar.xz -C "${pkgdir}"
}
