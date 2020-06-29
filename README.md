说明

软件不定期同步大神库更新，适合一键下载到package目录下，用于openwrt编译


食用方法一、

在feeds.conf.default加入：
src-git mypackages https://github.com/siropboy/mypackages

食用方法二、
git clone https://github.com/siropboy/mypackages package/mypackages


openwrt 固件编译说明
luci-app-autopoweroff ------------------openclash图形
luci-app-advancedsetting ------------------系统高级设置
luci-app-control-mia ------------------时间控制一
luci-app-control-timewol ------------------定时唤醒
luci-app-control-webrestriction ------------------访问控制
luci-app-control-weburl -----------------网址过滤
luci-app-cpulimit ------------------CPU限制
luci-app-eqos ------------------EQS网速控制
luci-app-flowoffload-leo -----------------ACC加速工具
luci-app-koolddns ------------------KOOL域名DNS解析工具
luci-app-koolproxyR ------------------经典去广告
luci-theme-opentomcat ------------------仿LEDE主题（适配18.06）

感谢LEAN大，感谢LEO大，感谢SIRPDBOY等大神分享源码，你可以随意使用其中的源码，但请注明出处。
