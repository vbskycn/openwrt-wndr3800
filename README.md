自用固件,网件路由器
wndr3800
wndr4300v1
r619ac (竞斗云2.0)

目标平台	ath79/generic
固件版本	OpenWrt 21.02-SNAPSHOT / LuCI 21.02 Lienol git-1ff9cf7
内核版本	5.4.194

加入了usb打印服务器，发挥余热


加入了adguard home 过滤广告
广告拦截 / 隐私保护
```
RULE-SET,https://ruleset.skk.moe/List/non_ip/reject.conf,reject-drop
DOMAIN-SET,https://ruleset.skk.moe/List/domainset/reject.conf,reject-tinygif
RULE-SET,https://ruleset.skk.moe/List/ip/reject.conf,reject-drop
```
自动生成
数据来源、白名单域名列表和生成方式，请参考 build-reject-domainset.js
仅建议在 Surge for Mac 上使用，移动平台请使用专门的工具（如 ADGuard for Android/iOS）以获得更好的性能
不能替代浏览器广告屏蔽扩展（如 uBlock Origin）


**English** | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)



## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
