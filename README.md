# Skipping-the-Fucking-GFW
本文旨在如何运用翻墙软件绕过GFW自由访问国际互联网

**声明**：本文所提到的软件和其他的内容均来自互联网，与本人均无关。本文仅交流学习的用途，请在阅读、下载使用后的24小时内尽快将软件删除。同时请遵守中华人民共和国的相关法律法规，不可将其运用于非法的事情，仅可运用于对国家科研相关等有益的事情。谢谢。

不多说废话直接介绍。

---

## 背景介绍

​	在中华人民共和国（大陆）中存在一种技术叫做**GFW**(**防火长城**（英语：**G**reat **F**ire**w**all））是中国政府用来控制和过滤互联网内容的一套技术和法律体系。它的主要目的是限制中国大陆用户访问某些外国网站、应用及服务，并过滤掉政府认为不合适或敏感的内容。

​	GFW的主要功能包括：

> 1. **域名封锁**：屏蔽特定域名，使用户无法访问这些网站，例如 Facebook、Twitter、Google 等。
>
> 2. **IP地址封锁**：通过封锁 IP 地址来限制用户访问目标服务。即使用户尝试通过其他方式访问受限网站，但只要 IP 被封锁，就无法连接。
>
> 3. **关键词过滤**：通过检测请求中的关键词来过滤敏感内容，尤其是在中文的搜索引擎和社交媒体平台中。
>
> 4. **内容检查和流量分析**：GFW 可以分析和检查用户的流量，如果发现异常或加密的流量，会采取干预措施，有时甚至会主动阻断 VPN 连接。
>
> 5. **DNS污染**：在用户请求访问某些被限制网站时，返回错误的 DNS 结果，以阻止正常访问。

​	GFW限制了中国用户访问国际互联网的某些部分，因此很多人会使用VPN或其他方式绕过GFW，但中国也在不断加强对于这些工具的监控和封锁。

​	要想自由访问国际互联网需要**VPN**（**虚拟专用网**（英语：**V**irtual **P**rivate **N**etwork））技术，用于在公共网络（如互联网）上创建一个安全的加密连接，使用户能够私密地访问网络资源和浏览互联网。通过 VPN，用户的互联网流量被加密，并通过一个位于其他地点的服务器路由，从而保护用户的隐私、提升数据安全并允许用户绕过地理限制。

## 方法

​	主流使用VPN绕过GFW的方法主要有两种：

1. 使用提供代理的服务商定制的VPN，如：蓝灯（Lantern）、快连VPN、1.1.1.1、ExpressVPN等

2. 使用代理客户端搭配提供代理服务服务商提供的订阅，如：CFW，V2rayN，Sing-Box等

   第一种因全平台覆盖率低、质量差、价格昂贵，本文只介绍第二种方法

   ### 代理客户端

   全平台推荐使用的代理客户端：
   |                           Windows                            |         备注&评级          |                            Linux                             |              | Linux |      |                       iOS (需外服账号)                       |                          |                           Android                            |                            |                   HarmonyOS NEXT (需侧载)                    |
   | :----------------------------------------------------------: | :------------------------: | :----------------------------------------------------------: | :----------: | :---: | :--: | :----------------------------------------------------------: | :----------------------: | :----------------------------------------------------------: | :------------------------: | :----------------------------------------------------------: |
   | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) |        (free) ★★★★★        | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) | (free) ★★★★★ |       |      | [shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | ($2.99)           ★★★★★  | [NekoBox For Android](https://github.com/MatsuriDayo/NekoBoxForAndroid) |        (free) ★★★★★        | [Clash Meta for Android](https://github.com/likuai2010/ClashMeta) (不评级) |
   |      [NekoRay](https://github.com/MatsuriDayo/nekoray)       |        (free) ★★★★☆        |      [NekoRay](https://github.com/MatsuriDayo/nekoray)       | (free) ★★★★☆ |       |      |   [Loon](https://apps.apple.com/us/app/loon/id1373567447)    | ($5.99)           ★★★★★  |    [SurfBord](https://github.com/getsurfboard/surfboard)     |        (free) ★★★★☆        |                                                              |
   |          [v2rayN](https://github.com/2dust/v2rayN)           |        (free) ★★★★☆        |          [v2rayN](https://github.com/2dust/v2rayN)           | (free) ★★★★☆ |       |      | [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) | ($7.99)            ★★★★☆ |         [v2rayNG](https://github.com/2dust/v2rayNG)          |        (free) ★★★★☆        |                                                              |
   |          [ClashN](https://github.com/2dust/clashN)           |        (free) ★★★☆☆        |       [sing-box](https://github.com/SagerNet/sing-box)       | (free) ★★★★☆ |       |      | [Surge 5](https://apps.apple.com/us/app/surge-5/id1442620678) |       (订阅) ★★★☆☆       |                 Clash For Android（已删库）                  | (free)      过时产品 ★★☆☆☆ |                                                              |
   |       [sing-box](https://github.com/SagerNet/sing-box)       |        (free) ★★★☆☆        |          [V2rayU](https://github.com/yanue/V2rayU)           | (free) ★★★☆☆ |       |      |  [Stash](https://apps.apple.com/us/app/stash/id1596063349)   |     ($120.00) ★★★☆☆      |                                                              |                            |                                                              |
   |          [Qv2ray](https://github.com/Qv2ray/Qv2ray)          |        (free) ★★★☆☆        |          [Qv2ray](https://github.com/Qv2ray/Qv2ray)          | (free) ★★★☆☆ |       |      | [Potatso](https://apps.apple.com/us/app/potatso/id1239860606) |     (free)    ★★☆☆☆      |                                                              |                            |                                                              |
   |                 Clash For Windows（已删库）                  | (free)      过时产品 ★★☆☆☆ |                                                              |              |       |      | [sing-box](https://apps.apple.com/us/app/sing-box-vt/id6673731168) |      (free)  ★★☆☆☆       |                                                              |                            |                                                              |
   | [Clash Verge](https://github.com/zzzgydi/clash-verge) （已归档） | (free)      过时产品 ★★☆☆☆ |                                                              |              |       |      | [streisand](https://apps.apple.com/us/app/streisand/id6450534064) |       (free) ★★☆☆☆       |                                                              |                            |                                                              |
   |                                                              |                            |                                                              |              |       |      |                                                              |                          |                                                              |                            |                                                              |
