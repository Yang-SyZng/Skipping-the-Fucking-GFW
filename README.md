# Skipping-the-Fucking-GFW
本文旨在如何运用翻墙软件绕过GFW自由访问国际互联网

**声明**：本文所提到的软件和其他的内容均来自互联网，与本人均无关。本文仅交流学习的用途，请在阅读、下载使用后的24小时内尽快将软件删除。同时请遵守中华人民共和国的相关法律法规，不可将其运用于非法的事情，仅可运用于对国家科研相关等有益的事情。谢谢。

不多说废话直接介绍。

---
## 目录
- [背景介绍](#背景介绍)
- [推荐内容](#方法)
  - [代理客户端推荐](#代理客户端推荐)
  - [机场推荐（没有推荐机场！！）](#机场推荐)
    - [⚠忠告⚠](#忠告)
    - [选择机场的经验](#选择机场的经验)
 - [使用方法](#使用方法) 

      
      
   
...... 之后慢慢更新

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

2. 使用**代理客户端**搭配提供代理服务服务商（**机场**）提供的订阅，如：CFW，V2rayN，Sing-Box等

   第一种因全平台覆盖率低、质量差、价格昂贵，本文只介绍第二种方法

   ### 代理客户端推荐

   全平台推荐使用的代理客户端：
   
   (仅代表个人在使用过程中的体验所给出的评价)
   
   | Windows | 备注&评级|   Linux  |  备注&评级   | MacOS |  备注&评级 |iOS (需外服账号)|    备注&评级  |    Android   |  备注&评级     |                   HarmonyOS NEXT (需侧载)                    |
   | :----------------------------------------------------------: | :------------------------: | :----------------------------------------------------------: | :----------: | ----- | :--: | :----------------------------------------------------------: | :----------------------: | :----------------------------------------------------------: | :------------------------: | :----------------------------------------------------------: |
   | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) |        (free)★★★★★        | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) | (free)★★★★★ |       | (free)★★★★★ | [shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | ($2.99)★★★★★  | [NekoBox For Android](https://github.com/MatsuriDayo/NekoBoxForAndroid) |        (free)★★★★★        | [Clash Meta for Android](https://github.com/likuai2010/ClashMeta) (不评级) |
   |      [NekoRay](https://github.com/MatsuriDayo/nekoray)       |        (free)★★★★☆        |      [NekoRay](https://github.com/MatsuriDayo/nekoray)       | (free)★★★★☆ |       |      |   [Loon](https://apps.apple.com/us/app/loon/id1373567447)    | ($5.99)★★★★★  |    [SurfBord](https://github.com/getsurfboard/surfboard)     |        (free)★★★★☆        |                                                              |
   |          [v2rayN](https://github.com/2dust/v2rayN)           |        (free) ★★★★☆        |          [v2rayN](https://github.com/2dust/v2rayN)           | (free)★★★★☆ |       |      | [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) | ($7.99)            ★★★★☆ |         [v2rayNG](https://github.com/2dust/v2rayNG)          |        (free)★★★★☆        |                                                              |
   |          [ClashN](https://github.com/2dust/clashN)           |        (free)★★★☆☆        |       [sing-box](https://github.com/SagerNet/sing-box)       | (free)★★★★☆ |       |      | [Surge 5](https://apps.apple.com/us/app/surge-5/id1442620678) |       (订阅)★★★☆☆       |                 Clash For Android（已删库）                  | (free)过时产品 ★★☆☆☆ |                                                              |
   |       [sing-box](https://github.com/SagerNet/sing-box)       |        (free)★★★☆☆        |          [V2rayU](https://github.com/yanue/V2rayU)           | (free)★★★☆☆ |       |      |  [Stash](https://apps.apple.com/us/app/stash/id1596063349)   |     ($120.00)★★★☆☆      |                                                              |                            |                                                              |
   |          [Qv2ray](https://github.com/Qv2ray/Qv2ray)          |        (free)★★★☆☆        |          [Qv2ray](https://github.com/Qv2ray/Qv2ray)          | (free)★★★☆☆ |       |      | [Potatso](https://apps.apple.com/us/app/potatso/id1239860606) |     (free)★★☆☆☆      |                                                              |                            |                                                              |
   |                 Clash For Windows（已删库）                  | (free)过时产品★★☆☆☆ |                                                              |              |       |      | [sing-box](https://apps.apple.com/us/app/sing-box-vt/id6673731168) |      (free)★★☆☆☆       |                                                              |                            |                                                              |
   | [Clash Verge](https://github.com/zzzgydi/clash-verge) （已归档） | (free)过时产品★★☆☆☆ |                                                              |              |       |      | [streisand](https://apps.apple.com/us/app/streisand/id6450534064) |       (free)★★☆☆☆       |                                                              |                            |                                                              |
   |                                                              |                            |                                                              |              |       |      |                                                              |                          |                                                              |                            |                                                              |

### 机场推荐

---

#### ⚠忠告⚠
*本文不推荐任何**机场**，也不引流到任何机场，因为这个Repository是Public的，传播核心用法违反了中华人民共和国的相关的法律法规。*

***可以通过Github站内或其他地方搜索机场的相关推荐***

----

**说在前面的话**

#### 选择机场的经验

选择机场的核心原则是：**一分钱一分货**。

![三色图](https://raw.githubusercontent.com/Yang-SyZng/Skipping-the-Fucking-GFW/refs/heads/main/Pictures/1.webp)

不熟悉这类服务的人可能容易被推荐一些质量不高的机场，所以在选择时多参考口碑和用户体验。机场服务通常分为高端付费和便宜的按量付费等多种方案，支持的协议种类（如 SS/SSR、V2Ray、Trojan 等）和客户端（例如 Clash）也各有不同。以下几点可以帮助大家更好地理解和选择合适的机场：

1. **优先考虑付费机场**：付费机场通常稳定性更高，因为服务商能够投入资源来维持节点的速度和质量。而且老板一般在墙外，相对安全，跑路风险较小。
2. **选择经验丰富的服务商**：推荐选择已经有一定用户群体和良好口碑的机场，避免质量差和频繁断连的服务。相较于自己搭建，使用成熟的机场可以省去大量时间和维护成本。
3. **让专业的服务商提供服务**：机场维护涉及复杂的技术和调优，尤其是晚上高峰期的速度保障。花费一点成本交给专业人士，可以让你把时间精力花在更重要的事情上。

一句话总结：**花钱买的是更快的速度、更好的体验、更少的麻烦**，而自建往往无法达到专业服务的效果。

----

选择机场的关键在于**线路质量**、**稳定性**、**跑路概率**和**备用机制**：

1. **线路质量和中转类型**：
   线路的中转方式对机场的速度、延迟、稳定性影响显著。IEPL专线 > 隧道公网中转 > 直连线路。**专线机场**通常表现更优，因为它们不会绕路，延迟低、速度稳定。高质量的中转线路（尤其是多中转）和足够的带宽是好机场的基础。小机场多用便宜转发，虽然价格低但稳定性差，可能无力应对高流量和网络攻击。

   ![线路区别](https://raw.githubusercontent.com/Yang-SyZng/Skipping-the-Fucking-GFW/refs/heads/main/Pictures/2.webp)

2. **避免跑路风险**：
   **优先选择老牌大机场**，因为大机场有更多资金维护好的线路，且常常有高防御来应对DDoS攻击。小机场跑路的风险更高，尤其是刚起步、以低价吸引用户的。推荐初期以月付为主，观察服务的稳定性。注意那些在 Telegram 上过于高调宣传的机场，因为容易引起攻击和监管的关注。

3. **协议与兼容性**：
   选择机场时，协议类型（SS、SSR、Vmess、Trojan等）并非决定性因素，主流机场都支持常见协议。只需确认常用代理软件兼容的协议即可。如果要自建线路，建议用更适合直连的 Reality 和 Hy2 协议。

4. **备用机场**：
   **没有机场能做到永远稳定**，因此准备备用机场至关重要。选择不同线路和不同转发方式的两家稳定机场，能有效应对单一机场的短时波动。按量付费或小流量套餐的备用机场会是较佳选择。

5. **便宜机场的常见套路**：
   低价机场的策略通常包括吸引新用户、捞一笔跑路，或采用不稳定的月抛线路、复用多条线路（导致一旦被攻击会大范围断网）。尽管低价吸引人，但机场的核心仍然是一分钱一分货。便宜的机场通常无法提供足够带宽和稳定线路，最终效果差且体验不佳。

6. **不适合打游戏**：
   机场并不适合用于延迟敏感的场景，比如网络游戏。此类用途下推荐使用 UU 加速器等专门为游戏优化的加速服务。

**机场质量靠“钞能力”，贵有贵的道理**。选用经验丰富、信誉良好的机场，配置足够的备用方案，避免将时间和精力浪费在不必要的网络问题上。

----

### 使用方法
**以 Clash_Verge_Rev为例**

1. **复制订阅链接**：常见机场的dashboard一般如下：

   ![截图](https://raw.githubusercontent.com/Yang-SyZng/Skipping-the-Fucking-GFW/refs/heads/main/Pictures/3.png)

可以通过一键订阅，复制订阅链接。
