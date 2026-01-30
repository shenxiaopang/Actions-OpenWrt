高通骁龙410云编译immortalwrt

固件主要添加超多 无线网卡驱动为目的!

目前开启usb网络共享驱动

kmod-usb-net-cdc-ether kmod-usb-net-cdc-mbim kmod-usb-net-cdc-ncm kmod-usb-net-huawei-cdc-ncm kmod-usb-net-ipheth 
kmod-usb-net-rndis

目前开启的Realtek系列网卡

kmod-rtw88-8812a

kmod-rtw88-8812au

kmod-rtw88-8814a

kmod-rtw88-8814au

kmod-rtw88-8821a

kmod-rtw88-8821au

kmod-rtw88-8821c

kmod-rtw88-8821cu和rtl8821cu通用

kmod-rtw88-8822b

kmod-rtw88-8822bu

kmod-rtw88-8822c

kmod-rtw88-8822cs

kmod-rtw88-8822cu和rtl8812cu通用

kmod-rtl8188eu


需要其他插件自行通过config_small配置添加，注意同时开启对应依赖选项


## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
