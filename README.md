

Clash规则碎片
主要文件在clash文件夹下，只是一些规则碎片，可以配合一些订阅转换进行使用。

具体怎么使用需要看对应软件配置是怎么写的，还要请大家阅读你所使用的软件文档，看是否能使用

示例：项目里/Clash/config/目录下存放的是 subconverter的 配置示例

文件	类型	解释
BanAD.list	规则碎片-去广告	只包含常见广告关键字、广告联盟。无副作用，放心使用
BanProgramAD.list	规则碎片-去广告	包含常用应用的各种去广告规则。可能有轻微副作用，可放心使用。（如果网站功能和广告冲突，会删掉去广告规则）
BanEasyListChina.list	规则碎片-去广告	AdblockPlus中的中国所有的屏蔽域名
LocalAreaNetwork.list	规则碎片-直连	本地地址和路由器直连域名啥的
ChinaDomain.list	规则碎片-直连	国内常见域名、直连CDN等。（很全，常用网址都有）
ChinaCompanyIp.list	规则碎片-直连	国内BAT公司及云服务厂商的IP段。所有在该云服务上的网站都可以直连。比如你网站在阿里云香港都可以直连。
ChinaIp.list	规则碎片-直连	IPIP的国内地址段。比GeoIp更好。电脑性能好，可以引入
Download.list	规则碎片-直连	一些下载用的域名
Apple.list	规则碎片	苹果公司的所有域名
Microsoft.list	规则碎片	微软公司的所有域名
OneDrive.list	规则碎片	OneDrive
GoogleCN.list	规则碎片-直连	谷歌在中国能直连的网址列表
Telegram.list	规则碎片-代理	Telegram的所有域名
Netflix.list	规则碎片-代理	Netflix的所有域名
ProxyGFWlist.list	规则碎片-代理	GFW的全量列表
ProxyLite.list	规则碎片-代理	比较精简的代理列表，包含常用的，以及被污染的域名
GeneralClashConfig.yml	clash配置文件	放行一堆国内的常用域名，配合系统代理更牛逼。 配置很全，自带中文注释。可以自行使用
pref.ini	subconverter配置文件	更改了一些基础配置，将规则变成ACL4SSR
