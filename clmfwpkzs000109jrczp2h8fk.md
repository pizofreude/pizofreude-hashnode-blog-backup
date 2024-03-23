---
title: "Installing & Updating NodeJS and npm package on OpenSUSE"
seoTitle: "Installing node, npm and npx on opensuse"
seoDescription: "How to install Node.js, npm and npx on Linux openSUSE Tumbleweed"
datePublished: Tue Sep 12 2023 06:03:11 GMT+0000 (Coordinated Universal Time)
cuid: clmfwpkzs000109jrczp2h8fk
slug: installing-updating-nodejs-and-npm-package-on-opensuse
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694498456458/2d63fcbc-577d-439a-85d2-1203a12a44cd.png
tags: nodejs, npm, opensuse

---

Disclaimer: This tutorial is conducted on Linux OpenSUSE Tumbleweed via WSL2.

First of all, we need to update all installed packages on an openSUSE system to the latest version available in the repositories. On openSUSE, we use `zypper dup` instead of `zypper update` which only updates packages that have newer versions available.

We need superuser access for this, so change to `su` and enter your password and run `zypper dup`.

`zypper dup` is a safe command to use, but it is always a good idea to back up your system before running it. This way, if anything goes wrong, you can restore your system to its previous state.

Here are some of the benefits of using `zypper dup`:

* It keeps your system up to date with the latest security fixes and bug fixes.
    
* It can help to improve the performance and stability of your system.
    
* It can help to prevent compatibility problems with newer software.
    

```bash
CAEpizo@IRHAFEEZ:~> su
Password:
IRHAFEEZ:/home/CAEpizo # zypper dup
Loading repository data...
Reading installed packages...
Warning: You are about to do a distribution upgrade with all enabled repositories. Make sure these repositories are compatible before you continue. See 'man zypper' for more information about this command.
Computing distribution upgrade...

The following 312 packages are going to be upgraded:
  aaa_base aaa_base-extras aaa_base-wsl adjtimex alts augeas augeas-lenses bash bash-sh branding-openSUSE bzip2
  ca-certificates ca-certificates-mozilla chkstat compat-usrmerge-tools coreutils cpio cracklib cracklib-dict-small
  crypto-policies curl dbus-1 dbus-1-common dbus-1-daemon dbus-1-tools device-mapper diffutils dos2unix fdupes file
  file-magic filesystem fillup findutils gawk gpg2 grep groff gzip hostname hwdata hwinfo initviocons iproute2 iputils
  joe kbd kbd-legacy kmod krb5 lato-fonts less libacl1 libaio1 libalternatives1 libapparmor1 libargon2-1 libassuan0
  libattr1 libaudit1 libaugeas0 libblkid1 libbpf1 libbrotlicommon1 libbrotlidec1 libbz2-1 libcap2 libcap-ng0 libcares2
  libcom_err2 libcrack2 libcrypt1 libcryptsetup12 libcurl4 libdb-4_8 libdbus-1-3 libdevmapper1_03 libdevmapper-event1_03
  libdw1 libeconf0 libedit0 libelf1 libexpat1 libexslt0 libfa1 libfdisk1 libffi8 libfido2-1 libgcc_s1 libgcrypt20
  libgdbm6 libgdbm_compat4 libglib-2_0-0 libgmp10 libgomp1 libgpg-error0 libgpgme11 libhidapi-hidraw0 libICE6 libidn2-0
  libip4tc2 libjson-c5 libkeyutils1 libkmod2 libksba8 libldap2 libldapcpp0 liblua5_4-5 liblz4-1 liblzma5 libmagic1
  libmetalink3 libmnl0 libmount1 libmpdec3 libmpfr6 libncurses6 libnghttp2-14 libnl3-200 libnl-config libnpth0 libnsl3
  libnss_usrfiles2 libopenssl1_1 libopenssl3 libp11-kit0 libparted2 libparted-fs-resize0 libpci3 libpcre1 libpcre2-8-0
  libpipeline1 libpkgconf3 libpopt0 libprocps8 libprotobuf-lite3_21_12 libproxy1 libpsl5 libpython3_10-1_0
  libpython3_8-1_0 libreadline8 librpmbuild9 libsasl2-3 libseccomp2 libselinux1 libsemanage2 libsemanage-conf libsepol2
  libsigc-2_0-0 libSM6 libsmartcols1 libsolv-tools libsqlite3-0 libssh4 libssh-config libstorage-ng1 libstorage-ng-ruby
  libsubid4 libsystemd0 libtasn1-6 libtirpc3 libtirpc-netconfig libudev1 libunistring5 libusb-1_0-0 libutempter0
  libuuid1 libverto1 libX11-6 libX11-data libX11-xcb1 libx86emu3 libXau6 libxcb1 libxcb-damage0 libxcb-present0
  libxcb-xfixes0 libXext6 libXi6 libxml2-2 libXmu6 libXrender1 libxslt1 libXt6 libxtables12 libyaml-0-2 libyui16
  libyui-ncurses16 libyui-ncurses-pkg16 libz1 libzck1 libzio1 libzstd1 libzypp login_defs lsof lsscsi man ncurses-utils
  netcfg openssh openssh-clients openssh-common openssh-server openSUSE-build-key openSUSE-release
  openSUSE-release-appliance-wsl p11-kit p11-kit-tools pam pam-config pam-manpages parted patterns-base-minimal_base
  patterns-wsl-base patterns-wsl-gui patterns-wsl-systemd pciutils perl perl-base perl-Digest-SHA1 perl-gettext
  perl-Parse-RecDescent perl-X500-DN permissions permissions-config pinentry pkgconf pkgconf-m4 pkgconf-pkg-config
  procps python310 python310-base python310-rpm python38 python38-base python3-solv rpm rpm-config-SUSE ruby ruby-common
  ruby-solv scout scout-command-not-found screen sed shadow sudo suse-module-tools suse-module-tools-scriptlets
  sysconfig sysconfig-netconfig systemd systemd-default-settings systemd-default-settings-branding-openSUSE
  systemd-presets-branding-openSUSE systemd-presets-common-SUSE systemd-rpm-macros system-group-hardware
  system-group-kvm system-user-man system-user-nobody system-user-root sysuser-shadow tar terminfo-base
  thin-provisioning-tools time timezone udev unzip update-alternatives util-linux util-linux-systemd vim vim-data-common
  wget which wicked wicked-service xbitmaps xeyes xz yast2 yast2-bootloader yast2-configuration-management yast2-core
  yast2-country yast2-country-data yast2-firstboot yast2-firstboot-wsl yast2-hardware-detection yast2-installation
  yast2-ldap yast2-logs yast2-network yast2-packager yast2-pam yast2-perl-bindings yast2-pkg-bindings yast2-proxy
  yast2-ruby-bindings yast2-security yast2-services-manager yast2-storage-ng yast2-transfer yast2-trans-stats
  yast2-users yast2-xml yast2-ycp-ui-bindings zip zypper

The following 4 patterns are going to be upgraded:
  minimal_base wsl_base wsl_gui wsl_systemd

The following product is going to be upgraded:
  openSUSE Tumbleweed  20221223-0 -> 20230910-0

The following 4 packages are going to change architecture:
  patterns-wsl-base     x86_64 -> noarch
  patterns-wsl-gui      x86_64 -> noarch
  patterns-wsl-systemd  x86_64 -> noarch
  permissions-config    x86_64 -> noarch

The following 3 patterns are going to change architecture:
  wsl_base     x86_64 -> noarch
  wsl_gui      x86_64 -> noarch
  wsl_systemd  x86_64 -> noarch

The following 31 NEW packages are going to be installed:
  boost-license1_82_0 coreutils-systemd libabsl2308_0_0 libboost_thread1_82_0 libcbor0_10 libhd23 libprotobuf-lite23_4_0
  libpython3_11-1_0 libruby3_2-3_2 libwtmpdb0 libyaml-cpp0_8 pam-extra python311 python311-base python311-rpm ruby3.2
  ruby3.2-rubygem-abstract_method ruby3.2-rubygem-cfa ruby3.2-rubygem-cfa_grub2 ruby3.2-rubygem-cheetah
  ruby3.2-rubygem-fast_gettext ruby3.2-rubygem-gem2rpm ruby3.2-rubygem-nokogiri ruby3.2-rubygem-ruby-augeas
  ruby3.2-rubygem-ruby-dbus ruby3.2-rubygem-simpleidn ruby3.2-rubygem-unf ruby3.2-rubygem-unf_ext util-linux-tty-tools
  wtmpdb xxd

The following 21 packages are going to be REMOVED:
  boost-license1_80_0 libboost_thread1_80_0 libcbor0_9 libhd22 libruby3_1-3_1 libyaml-cpp0_7 pam_unix python38-rpm
  ruby3.1 ruby3.1-rubygem-abstract_method ruby3.1-rubygem-cfa ruby3.1-rubygem-cfa_grub2 ruby3.1-rubygem-cheetah
  ruby3.1-rubygem-fast_gettext ruby3.1-rubygem-gem2rpm ruby3.1-rubygem-nokogiri ruby3.1-rubygem-ruby-augeas
  ruby3.1-rubygem-ruby-dbus ruby3.1-rubygem-simpleidn ruby3.1-rubygem-unf ruby3.1-rubygem-unf_ext

312 packages to upgrade, 31 new, 21 to remove, 4 to change arch.
Overall download size: 143.4 MiB. Already cached: 0 B. After the operation, additional 66.3 MiB will be used.
Continue? [y/n/v/...? shows all options] (y): y
```

If you are using an openSUSE system, I recommend using `zypper dup` to update your system regularly. It is a safe and effective way to keep your system up to date and running smoothly.

## NodeJS Installation

As I was gradually setting up Linux openSUSE Tumbleweed on WSL2 (hoping to Dualboot someday on my next machine & get a standalone Linux machine when I can get my hands on the Tuxedo Stellaris 17 with its cool external water cooler Aquaris), I realized I needed Node.js. I typed zypper for node and got a ton of results. To my delight, all the LTS, or Long Term Support, versions were there in the repositories by default, for both Tumbleweed & Leap. That’s not something you see often with Debian based systems, so I was impressed. I chose to install Node.js v18 as that is the newest LTS. This is the command I used.

```bash
CAEpizo@IRHAFEEZ:~> sudo zypper install nodejs-common
[sudo] password for root:
Loading repository data...
Reading installed packages...
Resolving package dependencies...

The following 4 packages are going to be upgraded:
  glibc glibc-locale glibc-locale-base libstdc++6

The following 6 NEW packages are going to be installed:
  libbrotlienc1 libicu73 libicu73-ledata nodejs20 nodejs-common patterns-glibc-hwcaps-x86_64_v3

The following NEW pattern is going to be installed:
  x86_64_v3

4 packages to upgrade, 6 new.
Overall download size: 43.7 MiB. Already cached: 0 B. After the operation, additional 79.0 MiB will be used.
Continue? [y/n/v/...? shows all options] (y): y
Retrieving package glibc-2.38-2.1.x86_64                                          (1/10),   2.0 MiB (  7.3 MiB unpacked)
Retrieving: glibc-2.38-2.1.x86_64.rpm ..............................................................[done (617.3 KiB/s)]
Retrieving package libicu73-ledata-73.2-2.1.noarch                                (2/10),   8.5 MiB ( 30.5 MiB unpacked)
Retrieving: libicu73-ledata-73.2-2.1.noarch.rpm ......................................................[done (4.9 MiB/s)]
Retrieving package patterns-glibc-hwcaps-x86_64_v3-20230201-3.1.x86_64            (3/10),   8.6 KiB (   55   B unpacked)
Retrieving: patterns-glibc-hwcaps-x86_64_v3-20230201-3.1.x86_64.rpm ..................................[done (7.9 KiB/s)]
Retrieving package libstdc++6-13.2.1+git7683-2.1.x86_64                           (4/10), 712.8 KiB (  2.3 MiB unpacked)
Retrieving: libstdc++6-13.2.1+git7683-2.1.x86_64.rpm .................................................[done (1.4 MiB/s)]
Retrieving package libbrotlienc1-1.0.9-3.5.x86_64                                 (5/10), 238.1 KiB (578.0 KiB unpacked)
Retrieving: libbrotlienc1-1.0.9-3.5.x86_64.rpm ...................................................................[done]
Retrieving package glibc-locale-base-2.38-2.1.x86_64                              (6/10),   1.8 MiB ( 10.9 MiB unpacked)
Retrieving: glibc-locale-base-2.38-2.1.x86_64.rpm ....................................................[done (1.4 MiB/s)]
Retrieving package libicu73-73.2-2.1.x86_64                                       (7/10),   2.0 MiB (  5.7 MiB unpacked)
Retrieving: libicu73-73.2-2.1.x86_64.rpm .............................................................[done (1.8 MiB/s)]
Retrieving package glibc-locale-2.38-2.1.x86_64                                   (8/10),  18.2 MiB (214.8 MiB unpacked)
Retrieving: glibc-locale-2.38-2.1.x86_64.rpm .........................................................[done (5.1 MiB/s)]
Retrieving package nodejs-common-6.0-2.1.x86_64                                   (9/10),  14.4 KiB ( 29.4 KiB unpacked)
Retrieving: nodejs-common-6.0-2.1.x86_64.rpm .....................................................................[done]
Retrieving package nodejs20-20.6.0-2.1.x86_64                                    (10/10),  10.3 MiB ( 41.0 MiB unpacked)
Retrieving: nodejs20-20.6.0-2.1.x86_64.rpm ...........................................................[done (2.4 MiB/s)]

Checking for file conflicts: .....................................................................................[done]
/usr/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
/usr/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
( 1/10) Installing: glibc-2.38-2.1.x86_64 ........................................................................[done]
( 2/10) Installing: libicu73-ledata-73.2-2.1.noarch ..............................................................[done]
( 3/10) Installing: patterns-glibc-hwcaps-x86_64_v3-20230201-3.1.x86_64 ..........................................[done]
/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
( 4/10) Installing: libstdc++6-13.2.1+git7683-2.1.x86_64 .........................................................[done]
/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
( 5/10) Installing: libbrotlienc1-1.0.9-3.5.x86_64 ...............................................................[done]
( 6/10) Installing: glibc-locale-base-2.38-2.1.x86_64 ............................................................[done]
/sbin/ldconfig: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link
( 7/10) Installing: libicu73-73.2-2.1.x86_64 .....................................................................[done]
( 8/10) Installing: glibc-locale-2.38-2.1.x86_64 .................................................................[done]
( 9/10) Installing: nodejs-common-6.0-2.1.x86_64 .................................................................[done]
(10/10) Installing: nodejs20-20.6.0-2.1.x86_64 ...................................................................[done]
There are running programs which still use files and libraries deleted or updated by recent upgrades. They should be restarted to benefit from the latest updates. Run 'zypper ps -s' to list these programs.
```

A quick check for successful installation of Node.js:

```bash
CAEpizo@IRHAFEEZ:~> node -v
v20.6.0
```

## NPM Installation

npm is a package manager for the JavaScript programming language. It is the default package manager for Node.js, a JavaScript runtime environment. npm allows you to install, update, and manage JavaScript packages. `npm` is a command-line tool that you can use to interact with the npm registry. The npm registry is a repository of JavaScript packages. Packages are made up of JavaScript code, documentation, and other files. The command `sudo zypper install npm` in openSUSE will be automatically resolved to look the latest and common npm package suitable for the openSUSE version:

```bash
CAEpizo@IRHAFEEZ:~> sudo zypper install npm
[sudo] password for root:
Loading repository data...
Reading installed packages...
'npm' not found in package names. Trying capabilities.
'npm20' providing 'npm' is already installed.
Resolving package dependencies...
Nothing to do.
```

Interestingly, when installing `npm20` packages, `npx` got installed too. NPX stands for Node Package eXecute. It is a tool that allows you to run any JavaScript package available on the npm registry without even installing it. After a quick research, I found out that NPX is installed automatically with NPM version 5.2.0 and above.

To use npx, you simply run the `npx` command followed by the name of the package. For example, to run the express package, you would run the following command:

```bash
npx express
```

This will start a new express server on port 3000.

NPX is a very useful tool for running one-off commands or for trying out new packages. It is also a good way to avoid polluting your system with unnecessary packages.

Here are some of the benefits of using npx:

* It allows you to run packages without installing them.
    
* It is a good way to avoid polluting your system with unnecessary packages.
    
* It is a quick and easy way to run one-off commands or try out new packages.
    

Here are some of the differences between npm and npx:

* NPM is used to install and manage packages as dependencies for a project, while NPX is used to run packages without installing them.
    
* NPM installs packages globally, which means that they are available to all projects on your system. NPX does not install packages globally, so they are only available to the current project.
    
* NPX is a good choice for running one-off commands or for trying out new packages. NPM is a good choice for installing and managing packages for a project.
    

Now let’s check out exactly which versions we successfully installed for the Node.js tools:

```bash
CAEpizo@IRHAFEEZ:~> node -v
v20.6.0
CAEpizo@IRHAFEEZ:~> npm -v
9.8.1
CAEpizo@IRHAFEEZ:~> npx -v
9.8.1
```

That’s if folks. It looks like these are very recent versions for each. I wonder why they didn’t opt to LTS version as default and set to latest version instead. What a mystery socks. Oh well, great to see nonetheless. I’m curious how the future updates changes over time. I hope this stepwise tutorial will help someone to set up and running with Node.js, npm and npx on openSUSE. Tumbleweed ftw! Maybe in the future openSUSE ALP.

Cheers,

Hafeez