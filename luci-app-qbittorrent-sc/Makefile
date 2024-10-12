# SPDX-License-Identifier: Apache-2.0
#
# Copyright (C) 2023 ImmortalWrt.org

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-qbittorrent-sc
PKG_VERSION:=1.0.1
PKG_RELEASE:=1

LUCI_TITLE:=LuCI support for qbittorrent-sc
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+qbittorrent-sc

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
