include $(TOPDIR)/rules.mk

PKG_NAME:=ftth-movistar
PKG_VERSION:=master
PKG_RELEASE=$(PKG_VERSION)

PKG_SOURCE:=$(PKG_NAME)-$(PKG_VERSION).tar.bz2
PKG_SOURCE_PROTO:=git
PKG_SOURCE_SUBDIR:=$(PKG_NAME)-$(PKG_VERSION)
PKG_SOURCE_URL:=git://github.com/Colerax/openwrt-ftth.git
PKG_SOURCE_VERSION:=$(PKG_VERSION)

PKG_MAINTAINER:=Colerax <colerax@gmail.com>

include $(INCLUDE_DIR)/package.mk

define Package/ftth-movistar
  SECTION:=net
  CATEGORY:=Network
  SUBMENU:=FTTH
  URL:=http://www.taranus.es/
  TITLE:=FTTH Movistar
  DEPENDS:=+luci +luci-i18n-base-es +kmod-bridge +kmod-ipt-nathelper-rtsp +swconfig +bird4 +igmpproxy +udpxy +luci-app-udpxy +nfs-utils +kmod-fs-nfs +kmod-fs-nfs-common +kmod-nls-cp437 +kmod-nls-cp850 +kmod-nls-cp852 +kmod-nls-iso8859-1 +kmod-nls-iso8859-15 +kmod-nls-utf8 +miniupnpd +luci-app-upnp +tcpdump +htop +ddns-scripts +ddns-scripts_no-ip_com +luci-app-ddns +kmod-usb-storage +kmod-fs-ntfs +kmod-fs-ext4 +kmod-fs-vfat +block-mount +block-hotplug +kmod-scsi-core +e2fsprogs +samba36-server +luci-app-samba +ntfs-3g +fdisk +kmod-usb2 +nfs-kernel-server +usbutils +kmod-loop +kmod-usb-core +kmod-usb-ohci +luci-proto-ipv6 +luci-app-wol +ip +ipsec-tools +kmod-ipsec4 +kmod-ipsec6 +openssl-util +iptables-mod-nat-extra +ip6tables +iptables-mod-ipsec +kmod-ipt-ipsec +luci-proto-relay +relayd +blkid +mount-utils
endef

define Build/Compile

endef

$(eval $(call BuildPackage,ftth-movistar))
