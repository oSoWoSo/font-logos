# quickemu-logos #

![Available logos](assets/readme-header.png)

quickemu-logos is an icon font containing logos of popular linux distributions and other open source software.

*Note:* All brand icons are trademarks of their respective owners and should only be used to represent the company or product to which they refer.

## Installation ##

Install the font by downloading and unpacking the latest release's zip manually or installing it from npm:

	npm install quickemu-logos

To use the font, include `assets/quickemu-logos.css` as well as the
fonts in your project and use the CSS classes listed below.

	<link href="/assets/quickemu-logos.css" rel="stylesheet">

Alternatively just link to it using a CDN such as [jsDelivr](//jsdelivr.com):

	<link href="//cdn.jsdelivr.net/npm/quickemu-logos@1/assets/quickemu-logos.css" rel="stylesheet">

## Usage ##

Include an icon using the corresponding CSS class in an empty element:

	<i class="fl-[icon]"></i>

Add `fl-fw` as class for a fixed width icon.

If you want to insert a glyph of this font on a GNU/Linux system press `Ctrl + Shift + u`, release the keys and then type the code point, for instance: `Ctrl + Shift + u` and `f31a` will insert the `Tux` glyph.

Available logos are:

|       Distribution        |      CSS class       |                 Code                 | Code point |                       Image                        |
| ------------------------- | -------------------- | ------------------------------------ | :--------: | :------------------------------------------------: |
| Agarim OS                 | `fl-agarimos`        | `<i class="fl-agarimos"></i>`        |  `0xf302`  | <img src="vectors/agarimos.svg" width="24">        |
| Alma Linux                | `fl-almalinux`       | `<i class="fl-almalinux"></i>`       |  `0xf303`  | <img src="vectors/almalinux.svg" width="24">       |
| Alpine                    | `fl-alpine`          | `<i class="fl-alpine"></i>`          |  `0xf304`  | <img src="vectors/alpine.svg" width="24">          |
| Android                   | `fl-android`         | `<i class="fl-android"></i>`         |  `0xf305`  | <img src="vectors/android.svg" width="24">         |
| Antix                     | `fl-antix`           | `<i class="fl-antix"></i>`           |  `0xf306`  | <img src="vectors/antix.svg" width="24">           |
| Archbang                  | `fl-archbang`        | `<i class="fl-archbang"></i>`        |  `0xf307`  | <img src="vectors/archbang.svg" width="24">        |
| Archcraft                 | `fl-archcraft`       | `<i class="fl-archcraft"></i>`       |  `0xf308`  | <img src="vectors/archcraft.svg" width="24">       |
| ArchLabs                  | `fl-archlabs`        | `<i class="fl-archlabs"></i>`        |  `0xf309`  | <img src="vectors/archlabs.svg" width="24">        |
| Arch Linux                | `fl-archlinux`       | `<i class="fl-archlinux"></i>`       |  `0xf30a`  | <img src="vectors/archlinux.svg" width="24">       |
| ArcoLinux                 | `fl-arcolinux`       | `<i class="fl-arcolinux"></i>`       |  `0xf30b`  | <img src="vectors/arcolinux.svg" width="24">       |
| Artix Linux               | `fl-artixlinux`      | `<i class="fl-artixlinux"></i>`      |  `0xf30c`  | <img src="vectors/artixlinux.svg" width="24">      |
| Arya Linux                | `fl-aryalinux`       | `<i class="fl-aryalinux"></i>`       |  `0xf30d`  | <img src="vectors/aryalinux.svg" width="24">       |
| Athena OS                 | `fl-athenaos`        | `<i class="fl-athenaos"></i>`        |  `0xf30e`  | <img src="vectors/athenaos.svg" width="24">        |
| BackBox                   | `fl-backbox`         | `<i class="fl-backbox"></i>`         |  `0xf30f`  | <img src="vectors/backbox.svg" width="24">         |
| BigLinux                  | `fl-biglinux`        | `<i class="fl-biglinux"></i>`        |  `0xf310`  | <img src="vectors/biglinux.svg" width="24">        |
| Bodhi Linux               | `fl-bodhi`           | `<i class="fl-bodhi"></i>`           |  `0xf311`  | <img src="vectors/bodhi.svg" width="24">           |
| bunsenlabs                | `fl-bunsenlabs`      | `<i class="fl-bunsenlabs"></i>`      |  `0xf312`  | <img src="vectors/bunsenlabs.svg" width="24">      |
| CentOS                    | `fl-centos`          | `<i class="fl-centos"></i>`          |  `0xf313`  | <img src="vectors/centos.svg" width="24">          |
| Cereus Linux              | `fl-cereus`          | `<i class="fl-cereus"></i>`          |  `0xf314`  | <img src="vectors/cereus.svg" width="24">          |
| CoreOS                    | `fl-coreos`          | `<i class="fl-coreos"></i>`          |  `0xf315`  | <img src="vectors/coreos.svg" width="24">          |
| Crystal Linux             | `fl-crystal`         | `<i class="fl-crystal"></i>`         |  `0xf316`  | <img src="vectors/crystal.svg" width="24">         |
| Debian                    | `fl-debian`          | `<i class="fl-debian"></i>`          |  `0xf317`  | <img src="vectors/debian.svg" width="24">          |
| Devuan                    | `fl-devuan`          | `<i class="fl-devuan"></i>`          |  `0xf318`  | <img src="vectors/devuan.svg" width="24">          |
| DietPi                    | `fl-dietpi`          | `<i class="fl-dietpi"></i>`          |  `0xf319`  | <img src="vectors/dietpi.svg" width="24">          |
| elementary OS             | `fl-elementary`      | `<i class="fl-elementary"></i>`      |  `0xf31b`  | <img src="vectors/elementary.svg" width="24">      |
| Endeavour OS              | `fl-endeavouros`     | `<i class="fl-endeavouros"></i>`     |  `0xf31c`  | <img src="vectors/endeavouros.svg" width="24">     |
| /e/ OS                    | `fl-eos`             | `<i class="fl-eos"></i>`             |  `0xf31a`  | <img src="vectors/eos.svg" width="24">             |
| Fedora                    | `fl-fedora`          | `<i class="fl-fedora"></i>`          |  `0xf31d`  | <img src="vectors/fedora.svg" width="24">          |
| FreeBSD                   | `fl-freebsd`         | `<i class="fl-freebsd"></i>`         |  `0xf31e`  | <img src="vectors/freebsd.svg" width="24">         |
| FreeDOS                   | `fl-freedos`         | `<i class="fl-freedos"></i>`         |  `0xf31f`  | <img src="vectors/freedos.svg" width="24">         |
| Garuda Linux              | `fl-garuda`          | `<i class="fl-garuda"></i>`          |  `0xf320`  | <img src="vectors/garuda.svg" width="24">          |
| Gentoo                    | `fl-gentoo`          | `<i class="fl-gentoo"></i>`          |  `0xf321`  | <img src="vectors/gentoo.svg" width="24">          |
| GhostBSD                  | `fl-ghostbsd`        | `<i class="fl-ghostbsd"></i>`        |  `0xf322`  | <img src="vectors/ghostbsd.svg" width="24">        |
| GNU Guix                  | `fl-gnuguix`         | `<i class="fl-gnuguix"></i>`         |  `0xf323`  | <img src="vectors/gnuguix.svg" width="24">         |
| Haiku                     | `fl-haiku`           | `<i class="fl-haiku"></i>`           |  `0xf324`  | <img src="vectors/haiku.svg" width="24">           |
| Hyperbola GNU/Linux-libre | `fl-hyperbola`       | `<i class="fl-hyperbola"></i>`       |  `0xf325`  | <img src="vectors/hyperbola.svg" width="24">       |
| illumos                   | `fl-illumos`         | `<i class="fl-illumos"></i>`         |  `0xf326`  | <img src="vectors/illumos.svg" width="24">         |
| Kali Linux                | `fl-kalilinux`       | `<i class="fl-kalilinux"></i>`       |  `0xf327`  | <img src="vectors/kalilinux.svg" width="24">       |
| Kubuntu                   | `fl-kubuntu`         | `<i class="fl-kubuntu"></i>`         |  `0xf355`  | <img src="vectors/kubuntu.svg" width="24">         |
| Linux Lite                | `fl-linuxlite`       | `<i class="fl-linuxlite"></i>`       |  `0xf328`  | <img src="vectors/linuxlite.svg" width="24">       |
| Linux Mint                | `fl-linuxmint`       | `<i class="fl-linuxmint"></i>`       |  `0xf329`  | <img src="vectors/linuxmint.svg" width="24">       |
| Linux Mint Debian Edition | `fl-lmde`            | `<i class="fl-lmde"></i>`            |  `0xf32a`  | <img src="vectors/lmde.svg" width="24">            |
| Lubuntu                   | `fl-lubuntu`         | `<i class="fl-lubuntu"></i>`         |  `0xf356`  | <img src="vectors/lubuntu.svg" width="24">         |
| LXLE Linux                | `fl-lxle`            | `<i class="fl-lxle"></i>`            |  `0xf32b`  | <img src="vectors/lxle.svg" width="24">            |
| Mabox                     | `fl-mabox`           | `<i class="fl-mabox"></i>`           |  `0xf32c`  | <img src="vectors/mabox.svg" width="24">           |
| macOS                     | `fl-macos`           | `<i class="fl-macos"></i>`           |  `0xf32d`  | <img src="vectors/macos.svg" width="24">           |
| Mageia                    | `fl-mageia`          | `<i class="fl-mageia"></i>`          |  `0xf32e`  | <img src="vectors/mageia.svg" width="24">          |
| Mandriva                  | `fl-mandriva`        | `<i class="fl-mandriva"></i>`        |  `0xf32f`  | <img src="vectors/mandriva.svg" width="24">        |
| Manjaro                   | `fl-manjaro`         | `<i class="fl-manjaro"></i>`         |  `0xf330`  | <img src="vectors/manjaro.svg" width="24">         |
| MidnightBSD               | `fl-midnightbsd`     | `<i class="fl-midnightbsd"></i>`     |  `0xf331`  | <img src="vectors/midnightbsd.svg" width="24">     |
| MX Linux                  | `fl-mxlinux`         | `<i class="fl-mxlinux"></i>`         |  `0xf332`  | <img src="vectors/mxlinux.svg" width="24">         |
| netboot.xyz               | `fl-netbootxyz`      | `<i class="fl-netbootxyz"></i>`      |  `0xf334`  | <img src="vectors/netbootxyz.svg" width="24">      |
| netBSD                    | `fl-netbsd`          | `<i class="fl-netbsd"></i>`          |  `0xf333`  | <img src="vectors/netbsd.svg" width="24">          |
| NitruX                    | `fl-nitrux`          | `<i class="fl-nitrux"></i>`          |  `0xf335`  | <img src="vectors/nitrux.svg" width="24">          |
| NixOS                     | `fl-nixos`           | `<i class="fl-nixos"></i>`           |  `0xf336`  | <img src="vectors/nixos.svg" width="24">           |
| Nobara                    | `fl-nobara`          | `<i class="fl-nobara"></i>`          |  `0xf337`  | <img src="vectors/nobara.svg" width="24">          |
| OpenBSD                   | `fl-openbsd`         | `<i class="fl-openbsd"></i>`         |  `0xf339`  | <img src="vectors/openbsd.svg" width="24">         |
| Open Mandriva             | `fl-openmandriva`    | `<i class="fl-openmandriva"></i>`    |  `0xf338`  | <img src="vectors/openmandriva.svg" width="24">    |
| OpenSUSE                  | `fl-opensuse`        | `<i class="fl-opensuse"></i>`        |  `0xf33a`  | <img src="vectors/opensuse.svg" width="24">        |
| Parabola GNU/Linux-libre  | `fl-parabola`        | `<i class="fl-parabola"></i>`        |  `0xf33b`  | <img src="vectors/parabola.svg" width="24">        |
| Parrot security           | `fl-parrotsecurity`  | `<i class="fl-parrotsecurity"></i>`  |  `0xf33c`  | <img src="vectors/parrotsecurity.svg" width="24">  |
| PCLinuxOS                 | `fl-pclinuxos`       | `<i class="fl-pclinuxos"></i>`       |  `0xf33e`  | <img src="vectors/pclinuxos.svg" width="24">       |
| Pop!_OS                   | `fl-popos`           | `<i class="fl-popos"></i>`           |  `0xf33f`  | <img src="vectors/popos.svg" width="24">           |
| PostmarketOS              | `fl-postmarketos`    | `<i class="fl-postmarketos"></i>`    |  `0xf340`  | <img src="vectors/postmarketos.svg" width="24">    |
| Puppy Linux               | `fl-puppy`           | `<i class="fl-puppy"></i>`           |  `0xf33d`  | <img src="vectors/puppy.svg" width="24">           |
| PureOS                    | `fl-pureos`          | `<i class="fl-pureos"></i>`          |  `0xf341`  | <img src="vectors/pureos.svg" width="24">          |
| Q                         | `fl-q`               | `<i class="fl-q"></i>`               |  `0xf301`  | <img src="vectors/q.svg" width="24">               |
| Q4OS                      | `fl-q4os`            | `<i class="fl-q4os"></i>`            |  `0xf342`  | <img src="vectors/q4os.svg" width="24">            |
| QubesOS                   | `fl-qubesos`         | `<i class="fl-qubesos"></i>`         |  `0xf343`  | <img src="vectors/qubesos.svg" width="24">         |
| Raspberry pi              | `fl-raspberry-pi`    | `<i class="fl-raspberry-pi"></i>`    |  `0xf344`  | <img src="vectors/raspberry-pi.svg" width="24">    |
| RebornOS                  | `fl-rebornos`        | `<i class="fl-rebornos"></i>`        |  `0xf345`  | <img src="vectors/rebornos.svg" width="24">        |
| Regolith                  | `fl-regolith`        | `<i class="fl-regolith"></i>`        |  `0xf346`  | <img src="vectors/regolith.svg" width="24">        |
| Rocky Linux               | `fl-rockylinux`      | `<i class="fl-rockylinux"></i>`      |  `0xf347`  | <img src="vectors/rockylinux.svg" width="24">      |
| Sabayon                   | `fl-sabayon`         | `<i class="fl-sabayon"></i>`         |  `0xf348`  | <img src="vectors/sabayon.svg" width="24">         |
| siduction                 | `fl-siduction`       | `<i class="fl-siduction"></i>`       |  `0xf34c`  | <img src="vectors/siduction.svg" width="24">       |
| Slackware                 | `fl-slackware`       | `<i class="fl-slackware"></i>`       |  `0xf349`  | <img src="vectors/slackware.svg" width="24">       |
| Slitaz                    | `fl-slitaz`          | `<i class="fl-slitaz"></i>`          |  `0xf34a`  | <img src="vectors/slitaz.svg" width="24">          |
| smartos                   | `fl-smartos`         | `<i class="fl-smartos"></i>`         |  `0xf34b`  | <img src="vectors/smartos.svg" width="24">         |
| Solus                     | `fl-solus`           | `<i class="fl-solus"></i>`           |  `0xf34d`  | <img src="vectors/solus.svg" width="24">           |
| SteamOS                   | `fl-steamos`         | `<i class="fl-steamos"></i>`         |  `0xf34e`  | <img src="vectors/steamos.svg" width="24">         |
| Tails                     | `fl-tails`           | `<i class="fl-tails"></i>`           |  `0xf34f`  | <img src="vectors/tails.svg" width="24">           |
| Trisquel GNU/Linux        | `fl-trisquel`        | `<i class="fl-trisquel"></i>`        |  `0xf350`  | <img src="vectors/trisquel.svg" width="24">        |
| TrueNAS core              | `fl-truenas-core`    | `<i class="fl-truenas-core"></i>`    |  `0xf351`  | <img src="vectors/truenas-core.svg" width="24">    |
| TrueOS                    | `fl-trueos`          | `<i class="fl-trueos"></i>`          |  `0xf352`  | <img src="vectors/trueos.svg" width="24">          |
| Tux                       | `fl-tux`             | `<i class="fl-tux"></i>`             |  `0xf300`  | <img src="vectors/tux.svg" width="24">             |
| Tuxedo OS                 | `fl-tuxedoos`        | `<i class="fl-tuxedoos"></i>`        |  `0xf353`  | <img src="vectors/tuxedoos.svg" width="24">        |
| Ubuntu                    | `fl-ubuntu`          | `<i class="fl-ubuntu"></i>`          |  `0xf354`  | <img src="vectors/ubuntu.svg" width="24">          |
| Ubuntu Budgie             | `fl-ubuntu-budgie`   | `<i class="fl-ubuntu-budgie"></i>`   |  `0xf358`  | <img src="vectors/ubuntu-budgie.svg" width="24">   |
| Ubuntu Kylin              | `fl-ubuntu-kylin`    | `<i class="fl-ubuntu-kylin"></i>`    |  `0xf359`  | <img src="vectors/ubuntu-kylin.svg" width="24">    |
| Ubuntu Mate               | `fl-ubuntu-mate`     | `<i class="fl-ubuntu-mate"></i>`     |  `0xf35a`  | <img src="vectors/ubuntu-mate.svg" width="24">     |
| Ubuntu Studio             | `fl-ubuntu-studio`   | `<i class="fl-ubuntu-studio"></i>`   |  `0xf35b`  | <img src="vectors/ubuntu-studio.svg" width="24">   |
| Ultimate Edition          | `fl-ultimateedition` | `<i class="fl-ultimateedition"></i>` |  `0xf35c`  | <img src="vectors/ultimateedition.svg" width="24"> |
| Ultramarine               | `fl-ultramarine`     | `<i class="fl-ultramarine"></i>`     |  `0xf35d`  | <img src="vectors/ultramarine.svg" width="24">     |
| Vanilla OS                | `fl-vanilla`         | `<i class="fl-vanilla"></i>`         |  `0xf35e`  | <img src="vectors/vanilla.svg" width="24">         |
| Void Linux                | `fl-voidlinux`       | `<i class="fl-voidlinux"></i>`       |  `0xf35f`  | <img src="vectors/voidlinux.svg" width="24">       |
| VXlinux                   | `fl-vxlinux`         | `<i class="fl-vxlinux"></i>`         |  `0xf360`  | <img src="vectors/vxlinux.svg" width="24">         |
| Whonix                    | `fl-whonix`          | `<i class="fl-whonix"></i>`          |  `0xf361`  | <img src="vectors/whonix.svg" width="24">          |
| Windows                   | `fl-windows`         | `<i class="fl-windows"></i>`         |  `0xf362`  | <img src="vectors/windows.svg" width="24">         |
| XeroLinux                 | `fl-xerolinux`       | `<i class="fl-xerolinux"></i>`       |  `0xf363`  | <img src="vectors/xerolinux.svg" width="24">       |
| Xubuntu                   | `fl-xubuntu`         | `<i class="fl-xubuntu"></i>`         |  `0xf357`  | <img src="vectors/xubuntu.svg" width="24">         |
| Zorin OS                  | `fl-zorin`           | `<i class="fl-zorin"></i>`           |  `0xf364`  | <img src="vectors/zorin.svg" width="24">           |

## Building ##

Make sure you have the following dependencies installed:
* Node, Python and jq to run the build scripts
* [FontForge](//fontforge.org) to generate the fonts
* [wkhtmltopdf](http://wkhtmltopdf.org/) to generate this readme's preview image

Then run `npm install`/`yarn install` and `make`.

## Releasing ##

If you are a maintainer of this repository and a new release is to be published
* Make sure all PRs (that shall be pulled) are pulled
  * The PRs add new `svg`s in `vectors/`
  * The `icons.tsv` is ammended (i.e. new icons added at the bottom)
* Every time the `svg`s or `icons.tsv` is touched in the `master` branch (i.e. through pulling) the preview image is updated
* Note that the `README.md` is NOT updated. You can manually modify it do indicate/add recently added but not released icons.
* Once the release seems ready:
* Edit the version number in `package.json` (and push that change to `master`)
* Trigger the "Draft a Release" workflow manually on the Actions page (on the `master` branch)
  * The workflow will add a git tag for the release
* Go to the releases list and find the draft release
  * Edit the description etc pp and finally
  * Push "publish release"
  * The release is published on Github
* Automatically the "Update README" workflow is triggered
  * The `README.md` is regenerated (the preview should already be up to date, see above)
* Automatically the "Publish release to npm" workflow is triggered
  * If the npm token is not expired the release is pushed to NPM
  * You need to publish on NPM manually if token is expired (expected)
