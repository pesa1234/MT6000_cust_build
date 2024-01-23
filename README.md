MT 6000 custom build with testing kernel 6.1.

What is present?
WED enabled, LuCi installed, ksmbd server with automount, openvpn, adblock, wireguard, pbr etc...

How To Install?
From web interface of GL.iNET or actual openwrt flash sysupgrade.

In any case you need a package, just ask.

Package list of already installed packages.

```
adblock - 4.1.5-8
avahi-dbus-daemon - 0.8-8
base-files - 1560-r24889-039f8a1241
blkid - 2.39.3-1
busybox - 1.36.1-1
ca-bundle - 20230311-1
cgi-io - 2022-08-10-901b0f04-21
chat - 2.4.9.git-2021-01-04-5
comgt - 0.32-35
coreutils - 9.3-1
coreutils-sort - 9.3-1
coreutils-stat - 9.3-1
curl - 8.5.0-1
dbus - 1.14.10-1
dnsmasq-full - 2.89-7
dropbear - 2022.82-5
e2fsprogs - 1.47.0-2
eip197-mini-firmware - 20231211-1
f2fs-tools - 1.16.0-2
f2fsck - 1.16.0-2
firewall4 - 2023-11-03-698a5335-1
fstools - 2024-01-22-08cd7083-1
fwtool - 2019-11-12-8f7fe925-1
getrandom - 2024-01-22-6cf7d837-1
hostapd-common - 2023-09-08-e5ccbfc6-6
ip-full - 6.6.0-1
ip6tables-nft - 1.8.8-2
iperf3 - 3.16-1
iptables-mod-ipopt - 1.8.8-2
iptables-nft - 1.8.8-2
iw - 5.19-1
iwinfo - 2023-07-01-ca79f641-1
jansson4 - 2.14-3
jshn - 2023-12-04.1-ca3f6d0c-1
jsonfilter - 2024-01-23-594cfa86-1
kernel - 6.1.74-1-4cea82ec68845256d326b848b0a0e224
kmod-asn1-decoder - 6.1.74-1
kmod-cfg80211 - 6.1.74+6.5-2
kmod-crypto-aead - 6.1.74-1
kmod-crypto-authenc - 6.1.74-1
kmod-crypto-ccm - 6.1.74-1
kmod-crypto-cmac - 6.1.74-1
kmod-crypto-crc32 - 6.1.74-1
kmod-crypto-crc32c - 6.1.74-1
kmod-crypto-ctr - 6.1.74-1
kmod-crypto-des - 6.1.74-1
kmod-crypto-ecb - 6.1.74-1
kmod-crypto-gcm - 6.1.74-1
kmod-crypto-gf128 - 6.1.74-1
kmod-crypto-ghash - 6.1.74-1
kmod-crypto-hash - 6.1.74-1
kmod-crypto-hmac - 6.1.74-1
kmod-crypto-hw-safexcel - 6.1.74-1
kmod-crypto-lib-chacha20 - 6.1.74-1
kmod-crypto-lib-chacha20poly1305 - 6.1.74-1
kmod-crypto-lib-curve25519 - 6.1.74-1
kmod-crypto-lib-poly1305 - 6.1.74-1
kmod-crypto-manager - 6.1.74-1
kmod-crypto-md4 - 6.1.74-1
kmod-crypto-md5 - 6.1.74-1
kmod-crypto-null - 6.1.74-1
kmod-crypto-rng - 6.1.74-1
kmod-crypto-seqiv - 6.1.74-1
kmod-crypto-sha1 - 6.1.74-1
kmod-crypto-sha256 - 6.1.74-1
kmod-crypto-sha512 - 6.1.74-1
kmod-cryptodev - 6.1.74+1.12-mediatek-1
kmod-fs-exfat - 6.1.74-1
kmod-fs-ext4 - 6.1.74-1
kmod-fs-f2fs - 6.1.74-1
kmod-fs-ksmbd - 6.1.74-1
kmod-fs-ntfs3 - 6.1.74-1
kmod-fs-smbfs-common - 6.1.74-1
kmod-fs-vfat - 6.1.74-1
kmod-gpio-button-hotplug - 6.1.74-3
kmod-hwmon-core - 6.1.74-1
kmod-ifb - 6.1.74-1
kmod-ip6tables - 6.1.74-1
kmod-ipt-core - 6.1.74-1
kmod-ipt-ipopt - 6.1.74-1
kmod-leds-gpio - 6.1.74-1
kmod-lib-crc-ccitt - 6.1.74-1
kmod-lib-crc16 - 6.1.74-1
kmod-lib-crc32c - 6.1.74-1
kmod-mac80211 - 6.1.74+6.5-2
kmod-mt76-connac - 6.1.74+2024-01-18-f7718816-1
kmod-mt76-core - 6.1.74+2024-01-18-f7718816-1
kmod-mt7915e - 6.1.74+2024-01-18-f7718816-1
kmod-mt7986-firmware - 6.1.74+2024-01-18-f7718816-1
kmod-nf-conntrack - 6.1.74-1
kmod-nf-conntrack-netlink - 6.1.74-1
kmod-nf-conntrack6 - 6.1.74-1
kmod-nf-flow - 6.1.74-1
kmod-nf-ipt - 6.1.74-1
kmod-nf-ipt6 - 6.1.74-1
kmod-nf-log - 6.1.74-1
kmod-nf-log6 - 6.1.74-1
kmod-nf-nat - 6.1.74-1
kmod-nf-reject - 6.1.74-1
kmod-nf-reject6 - 6.1.74-1
kmod-nfnetlink - 6.1.74-1
kmod-nft-compat - 6.1.74-1
kmod-nft-core - 6.1.74-1
kmod-nft-fib - 6.1.74-1
kmod-nft-nat - 6.1.74-1
kmod-nft-offload - 6.1.74-1
kmod-nls-base - 6.1.74-1
kmod-nls-cp437 - 6.1.74-1
kmod-nls-iso8859-1 - 6.1.74-1
kmod-nls-utf8 - 6.1.74-1
kmod-oid-registry - 6.1.74-1
kmod-ppp - 6.1.74-1
kmod-pppoe - 6.1.74-1
kmod-pppox - 6.1.74-1
kmod-rtl8192c-common - 6.1.74+6.5-2
kmod-rtl8192cu - 6.1.74+6.5-2
kmod-rtlwifi - 6.1.74+6.5-2
kmod-rtlwifi-usb - 6.1.74+6.5-2
kmod-sched-cake - 6.1.74-1
kmod-sched-core - 6.1.74-1
kmod-scsi-core - 6.1.74-1
kmod-slhc - 6.1.74-1
kmod-thermal - 6.1.74-1
kmod-tun - 6.1.74-1
kmod-udptunnel4 - 6.1.74-1
kmod-udptunnel6 - 6.1.74-1
kmod-usb-core - 6.1.74-1
kmod-usb-storage - 6.1.74-1
kmod-usb-xhci-hcd - 6.1.74-1
kmod-usb-xhci-mtk - 6.1.74-1
kmod-usb3 - 6.1.74-1
kmod-wireguard - 6.1.74-1
ksmbd-avahi-service - 3.5.1-1
ksmbd-server - 3.5.1-1
libatomic1 - 12.3.0-4
libavahi-dbus-support - 0.8-8
libblkid1 - 2.39.3-1
libblobmsg-json202312041 - 2023-12-04.1-ca3f6d0c-1
libbpf1 - 1.3.0-1
libc - 1.2.4-4
libcap-ng - 0.8.3-2
libcomerr0 - 1.47.0-2
libcurl4 - 8.5.0-1
libdaemon - 0.14-5
libdbus - 1.14.10-1
libelf1 - 0.189-1
libevdev - 1.13.0-1
libexpat - 2.5.0-1
libext2fs2 - 1.47.0-2
libf2fs6 - 1.16.0-2
libgcc1 - 12.3.0-4
libgd - 2.3.3-1
libgmp10 - 6.3.0-1
libiperf3 - 3.16-1
libiptext-nft0 - 1.8.8-2
libiptext0 - 1.8.8-2
libiptext6-0 - 1.8.8-2
libiwinfo-data - 2023-07-01-ca79f641-1
libiwinfo20230701 - 2023-07-01-ca79f641-1
libjpeg-turbo - 2.1.4-2
libjson-c5 - 0.17-1
libjson-script202312041 - 2023-12-04.1-ca3f6d0c-1
liblua5.1.5 - 5.1.5-10
liblucihttp-lua - 2023-03-15-9b5b683f-1
liblucihttp-ucode - 2023-03-15-9b5b683f-1
liblucihttp0 - 2023-03-15-9b5b683f-1
liblz4-1 - 1.9.4-1
liblzo2 - 2.10-4
libmbedtls12 - 2.28.5-2
libmnl0 - 1.0.5-1
libncurses6 - 6.4-2
libnetfilter-conntrack3 - 1.0.9-2
libnettle8 - 3.9.1-1
libnfnetlink0 - 1.0.2-1
libnftnl11 - 1.2.6-1
libnghttp2-14 - 1.57.0-1
libnl-core200 - 3.9.0-1
libnl-genl200 - 3.9.0-1
libnl-tiny1 - 2023-12-05-965c4bf4-1
libopenssl-conf - 3.0.12-1
libopenssl-devcrypto - 3.0.12-1
libopenssl-legacy - 3.0.12-1
libopenssl3 - 3.0.12-1
libpcap1 - 1.10.4-1
libpng - 1.6.39-1
libpthread - 1.2.4-4
librt - 1.2.4-4
libsensors5 - 3.6.0-1
libsqlite3-0 - 3410200-1
libss2 - 1.47.0-2
libsysfs2 - 2.1.0-4
libubox202312041 - 2023-12-04.1-ca3f6d0c-1
libubus-lua - 2023-11-28-f84eb599-1
libubus20231128 - 2023-11-28-f84eb599-1
libuci20130104 - 2023-08-10-5781664d-1
libuclient20201210 - 2023-04-13-007d9454-1
libucode20230711 - 2023-11-30-6e89b89e-1
libudebug - 2023-12-06-6d3f51f9
libudev-zero - 1.0.3-1
libusb-1.0-0 - 1.0.26-3
libustream-mbedtls20201210 - 2023-11-26-263b9a97-1
libuuid1 - 2.39.3-1
libwebp - 1.3.2-1
libxtables12 - 1.8.8-2
lm-sensors - 3.6.0-1
logd - 2024-01-22-6cf7d837-1
lua - 5.1.5-10
luci-app-adblock - git-24.021.51525-3d54783
luci-app-firewall - git-24.021.51525-3d54783
luci-app-ksmbd - git-24.022.76896-fe543de
luci-app-openvpn - git-24.021.51525-3d54783
luci-app-opkg - git-24.021.51525-3d54783
luci-app-pbr - 1.1.1-7
luci-app-sqm - git-24.021.51525-3d54783
luci-app-vnstat2 - git-24.021.51525-3d54783
luci-base - git-24.023.26952-a4fd238
luci-compat - git-24.021.51525-3d54783
luci-lib-base - git-24.021.51525-3d54783
luci-lib-ip - git-24.021.51525-3d54783
luci-lib-jsonc - git-24.021.51525-3d54783
luci-lib-nixio - git-24.021.51525-3d54783
luci-lua-runtime - git-24.021.51525-3d54783
luci-mod-admin-full - git-24.021.51525-3d54783
luci-mod-network - git-24.021.51525-3d54783
luci-mod-status - git-24.021.51525-3d54783
luci-mod-system - git-24.021.51525-3d54783
luci-proto-3g - git-24.021.51525-3d54783
luci-proto-ppp - git-24.021.51525-3d54783
luci-proto-wireguard - git-24.021.51525-3d54783
luci-theme-bootstrap - git-24.021.51525-3d54783
mkf2fs - 1.16.0-2
mt7986-wo-firmware - 20231211-1
mtd - 26
netifd - 2024-01-04-f01345ec-1
nftables-json - 1.0.9-1
odhcp6c - 2023-05-12-bcd28363-20
odhcpd-ipv6only - 2023-10-24-d8118f6e-1
openssl-util - 3.0.12-1
openvpn-openssl - 2.6.8-3
openwrt-keyring - 2022-03-25-62471e69-2
opkg - 2022-02-24-d038e5b6-2
pbr - 1.1.1-7
ppp - 2.4.9.git-2021-01-04-5
ppp-mod-pppoe - 2.4.9.git-2021-01-04-5
procd - 2023-11-28-7e6c6efd-1
procd-seccomp - 2023-11-28-7e6c6efd-1
procd-ujail - 2023-11-28-7e6c6efd-1
resolveip - 2
rpcd - 2023-07-01-c07ab2f9-1
rpcd-mod-file - 2023-07-01-c07ab2f9-1
rpcd-mod-iwinfo - 2023-07-01-c07ab2f9-1
rpcd-mod-luci - 20230123-1
rpcd-mod-ucode - 2023-07-01-c07ab2f9-1
rtl8192cu-firmware - 20231211-1
sqm-scripts - 1.6.0-1
sysfsutils - 2.1.0-4
tc-tiny - 6.6.0-1
tcpdump-mini - 4.99.4-1
terminfo - 6.4-2
ubi-utils - 2.1.6-1
uboot-envtools - 2023.07.02-3
ubox - 2024-01-22-6cf7d837-1
ubus - 2023-11-28-f84eb599-1
ubusd - 2023-11-28-f84eb599-1
uci - 2023-08-10-5781664d-1
uclient-fetch - 2023-04-13-007d9454-1
ucode - 2023-11-30-6e89b89e-1
ucode-mod-fs - 2023-11-30-6e89b89e-1
ucode-mod-html - 1
ucode-mod-lua - 1
ucode-mod-math - 2023-11-30-6e89b89e-1
ucode-mod-nl80211 - 2023-11-30-6e89b89e-1
ucode-mod-rtnl - 2023-11-30-6e89b89e-1
ucode-mod-ubus - 2023-11-30-6e89b89e-1
ucode-mod-uci - 2023-11-30-6e89b89e-1
ucode-mod-uloop - 2023-11-30-6e89b89e-1
uhttpd - 2023-06-25-34a8a74d-2
uhubctl - 2.5.0-1
urandom-seed - 3
urngd - 2023-11-01-44365eb1-1
usbutils - 014-1
usign - 2020-05-23-f1f65026-1
vnstat2 - 2.11-1
vnstati2 - 2.11-1
wireguard-tools - 1.0.20210914-3
wireless-regdb - 2023.09.01-1
wpad-basic-openssl - 2023-09-08-e5ccbfc6-6
wsdd2 - 2023-12-21-b676d8ac-1
xtables-nft - 1.8.8-2
zlib - 1.3-1
```

Here is listed the diffconfig
```
CONFIG_TARGET_mediatek=y
CONFIG_TARGET_mediatek_filogic=y
CONFIG_TARGET_mediatek_filogic_DEVICE_glinet_gl-mt6000=y
CONFIG_DEVEL=y
CONFIG_GNUTLS_ALPN=y
CONFIG_GNUTLS_ANON=y
CONFIG_GNUTLS_DTLS_SRTP=y
CONFIG_GNUTLS_HEARTBEAT=y
CONFIG_GNUTLS_OCSP=y
CONFIG_GNUTLS_PSK=y
CONFIG_HTOP_LMSENSORS=y
CONFIG_IPK_FILES_CHECKSUMS=y
CONFIG_LIBCURL_COOKIES=y
CONFIG_LIBCURL_FILE=y
CONFIG_LIBCURL_FTP=y
CONFIG_LIBCURL_HTTP=y
CONFIG_LIBCURL_MBEDTLS=y
CONFIG_LIBCURL_NGHTTP2=y
CONFIG_LIBCURL_NO_SMB="!"
CONFIG_LIBCURL_PROXY=y
CONFIG_LIBCURL_UNIX_SOCKETS=y
CONFIG_LINUX_6_1=y
CONFIG_OPENSSL_ENGINE=y
CONFIG_OPENSSL_OPTIMIZE_SPEED=y
CONFIG_OPENSSL_WITH_ASM=y
CONFIG_OPENSSL_WITH_CHACHA_POLY1305=y
CONFIG_OPENSSL_WITH_CMS=y
CONFIG_OPENSSL_WITH_DEPRECATED=y
CONFIG_OPENSSL_WITH_ERROR_MESSAGES=y
CONFIG_OPENSSL_WITH_IDEA=y
CONFIG_OPENSSL_WITH_MDC2=y
CONFIG_OPENSSL_WITH_PSK=y
CONFIG_OPENSSL_WITH_SEED=y
CONFIG_OPENSSL_WITH_SRP=y
CONFIG_OPENSSL_WITH_TLS13=y
CONFIG_OPENSSL_WITH_WHIRLPOOL=y
CONFIG_OPENVPN_openssl_ENABLE_FRAGMENT=y
CONFIG_OPENVPN_openssl_ENABLE_LZ4=y
CONFIG_OPENVPN_openssl_ENABLE_LZO=y
CONFIG_OPENVPN_openssl_ENABLE_PORT_SHARE=y
CONFIG_OPENVPN_openssl_ENABLE_SMALL=y
CONFIG_PACKAGE_adblock=y
CONFIG_PACKAGE_adblock-fast=m
CONFIG_PACKAGE_attr=m
CONFIG_PACKAGE_avahi-dbus-daemon=y
CONFIG_PACKAGE_blkid=y
CONFIG_PACKAGE_cgi-io=y
CONFIG_PACKAGE_chat=y
CONFIG_PACKAGE_comgt=y
CONFIG_PACKAGE_coreutils=y
CONFIG_PACKAGE_coreutils-sort=y
CONFIG_PACKAGE_coreutils-stat=y
CONFIG_PACKAGE_curl=y
CONFIG_PACKAGE_dbus=y
# CONFIG_PACKAGE_dnsmasq is not set
CONFIG_PACKAGE_dnsmasq-full=y
CONFIG_PACKAGE_dnsmasq_full_auth=y
CONFIG_PACKAGE_dnsmasq_full_conntrack=y
CONFIG_PACKAGE_dnsmasq_full_dhcp=y
CONFIG_PACKAGE_dnsmasq_full_dnssec=y
CONFIG_PACKAGE_dnsmasq_full_nftset=y
CONFIG_PACKAGE_dnsmasq_full_noid=y
CONFIG_PACKAGE_dnsmasq_full_tftp=y
CONFIG_PACKAGE_f2fs-tools=y
CONFIG_PACKAGE_hd-idle=m
CONFIG_PACKAGE_htop=m
CONFIG_PACKAGE_ip-full=y
CONFIG_PACKAGE_ip6tables-nft=y
CONFIG_PACKAGE_iperf3=y
CONFIG_PACKAGE_iptables-mod-ipopt=y
CONFIG_PACKAGE_iptables-nft=y
CONFIG_PACKAGE_irqbalance=m
CONFIG_PACKAGE_kmod-asn1-decoder=y
CONFIG_PACKAGE_kmod-crypto-crc32=y
CONFIG_PACKAGE_kmod-crypto-ecb=y
CONFIG_PACKAGE_kmod-crypto-lib-chacha20=y
CONFIG_PACKAGE_kmod-crypto-lib-chacha20poly1305=y
CONFIG_PACKAGE_kmod-crypto-lib-curve25519=y
CONFIG_PACKAGE_kmod-crypto-lib-poly1305=y
CONFIG_PACKAGE_kmod-crypto-md4=y
CONFIG_PACKAGE_kmod-cryptodev=y
CONFIG_PACKAGE_kmod-fs-exfat=y
CONFIG_PACKAGE_kmod-fs-ext4=y
CONFIG_PACKAGE_kmod-fs-f2fs=y
CONFIG_PACKAGE_kmod-fs-ksmbd=y
CONFIG_PACKAGE_kmod-fs-ntfs3=y
CONFIG_PACKAGE_kmod-fs-smbfs-common=y
CONFIG_PACKAGE_kmod-fs-vfat=y
CONFIG_PACKAGE_kmod-ifb=y
CONFIG_PACKAGE_kmod-ip6tables=y
CONFIG_PACKAGE_kmod-ipt-core=y
CONFIG_PACKAGE_kmod-ipt-ipopt=y
CONFIG_PACKAGE_kmod-lib-crc16=y
CONFIG_PACKAGE_kmod-mii=m
CONFIG_PACKAGE_kmod-nf-conntrack-netlink=y
CONFIG_PACKAGE_kmod-nf-ipt=y
CONFIG_PACKAGE_kmod-nf-ipt6=y
CONFIG_PACKAGE_kmod-nft-compat=y
CONFIG_PACKAGE_kmod-nls-cp437=y
CONFIG_PACKAGE_kmod-nls-iso8859-1=y
CONFIG_PACKAGE_kmod-nls-utf8=y
CONFIG_PACKAGE_kmod-oid-registry=y
CONFIG_PACKAGE_kmod-rtl8192c-common=y
CONFIG_PACKAGE_kmod-rtl8192cu=y
CONFIG_PACKAGE_kmod-rtlwifi=y
CONFIG_PACKAGE_kmod-rtlwifi-usb=y
CONFIG_PACKAGE_kmod-sched-cake=y
CONFIG_PACKAGE_kmod-sched-core=y
CONFIG_PACKAGE_kmod-scsi-core=y
CONFIG_PACKAGE_kmod-tun=y
CONFIG_PACKAGE_kmod-udptunnel4=y
CONFIG_PACKAGE_kmod-udptunnel6=y
CONFIG_PACKAGE_kmod-usb-net=m
CONFIG_PACKAGE_kmod-usb-net-cdc-eem=m
CONFIG_PACKAGE_kmod-usb-net-cdc-ether=m
CONFIG_PACKAGE_kmod-usb-net-cdc-ncm=m
CONFIG_PACKAGE_kmod-usb-net-cdc-subset=m
CONFIG_PACKAGE_kmod-usb-net-huawei-cdc-ncm=m
CONFIG_PACKAGE_kmod-usb-net-ipheth=m
CONFIG_PACKAGE_kmod-usb-net-rndis=m
CONFIG_PACKAGE_kmod-usb-storage=y
CONFIG_PACKAGE_kmod-usb-wdm=m
CONFIG_PACKAGE_kmod-wireguard=y
CONFIG_PACKAGE_ksmbd-avahi-service=y
CONFIG_PACKAGE_ksmbd-server=y
CONFIG_PACKAGE_libatomic=y
CONFIG_PACKAGE_libattr=m
CONFIG_PACKAGE_libavahi-client=m
CONFIG_PACKAGE_libavahi-dbus-support=y
CONFIG_PACKAGE_libbpf=y
CONFIG_PACKAGE_libbz2=m
CONFIG_PACKAGE_libcap=m
CONFIG_PACKAGE_libcap-ng=y
CONFIG_PACKAGE_libcurl=y
CONFIG_PACKAGE_libdaemon=y
CONFIG_PACKAGE_libdbus=y
CONFIG_PACKAGE_libelf=y
CONFIG_PACKAGE_libevdev=y
CONFIG_PACKAGE_libexif=m
CONFIG_PACKAGE_libexpat=y
CONFIG_PACKAGE_libffmpeg-audio-dec=m
CONFIG_PACKAGE_libflac=m
CONFIG_PACKAGE_libgd=y
CONFIG_PACKAGE_libgmp=y
CONFIG_PACKAGE_libgnutls=m
CONFIG_PACKAGE_libid3tag=m
CONFIG_PACKAGE_libimobiledevice=m
CONFIG_PACKAGE_libiperf3=y
CONFIG_PACKAGE_libiptext=y
CONFIG_PACKAGE_libiptext-nft=y
CONFIG_PACKAGE_libiptext6=y
CONFIG_PACKAGE_libjpeg-turbo=y
CONFIG_PACKAGE_liblua=y
CONFIG_PACKAGE_liblucihttp=y
CONFIG_PACKAGE_liblucihttp-lua=y
CONFIG_PACKAGE_liblucihttp-ucode=y
CONFIG_PACKAGE_liblz4=y
CONFIG_PACKAGE_liblzo=y
CONFIG_PACKAGE_libmount=m
CONFIG_PACKAGE_libncurses=y
CONFIG_PACKAGE_libnetfilter-conntrack=y
CONFIG_PACKAGE_libnettle=y
CONFIG_PACKAGE_libnfnetlink=y
CONFIG_PACKAGE_libnghttp2=y
CONFIG_PACKAGE_libnl-core=y
CONFIG_PACKAGE_libnl-genl=y
CONFIG_PACKAGE_libogg=m
CONFIG_PACKAGE_libopenssl=y
CONFIG_PACKAGE_libopenssl-conf=y
CONFIG_PACKAGE_libopenssl-devcrypto=y
CONFIG_PACKAGE_libopenssl-legacy=y
CONFIG_PACKAGE_libpcap=y
CONFIG_PACKAGE_libplist=m
CONFIG_PACKAGE_libpng=y
CONFIG_PACKAGE_libpopt=m
CONFIG_PACKAGE_libreadline=m
CONFIG_PACKAGE_libsensors=y
CONFIG_PACKAGE_libsmartcols=m
CONFIG_PACKAGE_libsqlite3=y
CONFIG_PACKAGE_libsysfs=y
CONFIG_PACKAGE_libtasn1=m
CONFIG_PACKAGE_libtirpc=m
CONFIG_PACKAGE_libubus-lua=y
CONFIG_PACKAGE_libudev-zero=y
CONFIG_PACKAGE_liburing=m
CONFIG_PACKAGE_libusb-1.0=y
CONFIG_PACKAGE_libusbmuxd=m
CONFIG_PACKAGE_libvorbis=m
CONFIG_PACKAGE_libwebp=y
CONFIG_PACKAGE_libxml2=m
CONFIG_PACKAGE_libxtables=y
CONFIG_PACKAGE_lm-sensors=y
CONFIG_PACKAGE_lsblk=m
CONFIG_PACKAGE_lua=y
CONFIG_PACKAGE_luci-app-adblock=y
CONFIG_PACKAGE_luci-app-adblock-fast=m
CONFIG_PACKAGE_luci-app-firewall=y
CONFIG_PACKAGE_luci-app-hd-idle=m
CONFIG_PACKAGE_luci-app-irqbalance=m
CONFIG_PACKAGE_luci-app-ksmbd=y
CONFIG_PACKAGE_luci-app-minidlna=m
CONFIG_PACKAGE_luci-app-openvpn=y
CONFIG_PACKAGE_luci-app-opkg=y
CONFIG_PACKAGE_luci-app-pbr=y
CONFIG_PACKAGE_luci-app-samba4=m
CONFIG_PACKAGE_luci-app-sqm=y
CONFIG_PACKAGE_luci-app-upnp=m
CONFIG_PACKAGE_luci-app-vnstat2=y
CONFIG_PACKAGE_luci-app-wifischedule=m
CONFIG_PACKAGE_luci-base=y
CONFIG_PACKAGE_luci-compat=y
CONFIG_PACKAGE_luci-lib-base=y
CONFIG_PACKAGE_luci-lib-ip=y
CONFIG_PACKAGE_luci-lib-jsonc=y
CONFIG_PACKAGE_luci-lib-nixio=y
CONFIG_PACKAGE_luci-lua-runtime=y
CONFIG_PACKAGE_luci-mod-admin-full=y
CONFIG_PACKAGE_luci-mod-network=y
CONFIG_PACKAGE_luci-mod-status=y
CONFIG_PACKAGE_luci-mod-system=y
CONFIG_PACKAGE_luci-proto-3g=y
CONFIG_PACKAGE_luci-proto-ppp=y
CONFIG_PACKAGE_luci-proto-wireguard=y
CONFIG_PACKAGE_luci-theme-bootstrap=y
CONFIG_PACKAGE_minidlna=m
CONFIG_PACKAGE_miniupnpd-nftables=m
CONFIG_PACKAGE_openssl-util=y
CONFIG_PACKAGE_openvpn-openssl=y
CONFIG_PACKAGE_pbr=y
CONFIG_PACKAGE_resolveip=y
CONFIG_PACKAGE_rpcd=y
CONFIG_PACKAGE_rpcd-mod-file=y
CONFIG_PACKAGE_rpcd-mod-iwinfo=y
CONFIG_PACKAGE_rpcd-mod-luci=y
CONFIG_PACKAGE_rpcd-mod-ucode=y
CONFIG_PACKAGE_rtl8192cu-firmware=y
CONFIG_PACKAGE_samba4-libs=m
CONFIG_PACKAGE_samba4-server=m
CONFIG_PACKAGE_sqm-scripts=y
CONFIG_PACKAGE_sysfsutils=y
CONFIG_PACKAGE_tc-tiny=y
CONFIG_PACKAGE_tcpdump-mini=y
CONFIG_PACKAGE_terminfo=y
CONFIG_PACKAGE_ucode-mod-html=y
CONFIG_PACKAGE_ucode-mod-lua=y
CONFIG_PACKAGE_ucode-mod-math=y
CONFIG_PACKAGE_uhttpd=y
CONFIG_PACKAGE_uhubctl=y
CONFIG_PACKAGE_usbmuxd=m
CONFIG_PACKAGE_usbutils=y
CONFIG_PACKAGE_vnstat2=y
CONFIG_PACKAGE_vnstati2=y
CONFIG_PACKAGE_wifischedule=m
CONFIG_PACKAGE_wireguard-tools=y
# CONFIG_PACKAGE_wpad-basic-mbedtls is not set
CONFIG_PACKAGE_wpad-basic-openssl=y
CONFIG_PACKAGE_wsdd2=y
CONFIG_PACKAGE_xtables-nft=y
CONFIG_PACKAGE_zlib=y
CONFIG_SAMBA4_SERVER_AVAHI=y
CONFIG_SAMBA4_SERVER_NETBIOS=y
CONFIG_SAMBA4_SERVER_VFS=y
CONFIG_SAMBA4_SERVER_WSDD2=y
CONFIG_SQLITE3_COLUMN_METADATA=y
CONFIG_SQLITE3_DYNAMIC_EXTENSIONS=y
CONFIG_SQLITE3_FTS3=y
CONFIG_SQLITE3_FTS4=y
CONFIG_SQLITE3_FTS5=y
CONFIG_SQLITE3_RTREE=y
CONFIG_STRIP_KERNEL_EXPORTS=y
CONFIG_TARGET_OPTIONS=y
CONFIG_TESTING_KERNEL=y
# CONFIG_PACKAGE_dnsmasq_full_dhcpv6 is not set
# CONFIG_PACKAGE_kmod-crypto-kpp is not set

```
