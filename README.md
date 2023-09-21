# Adrules
收集了适用于DNS拦截的广告规则（也可以只用插件），同时配合浏览器插件补充部分规则。拦截效果接近100%</br>


**DNS类型只选一个**
AdGuard Home 使用 DNS类型
>其他为补充规则，可选，用于浏览器插件，推荐加个ADgk规则</br>
>ADgk规则里有一些没有被转换为dns类型，所以用浏览器插件加载的方式重复补充

下面写的分数，是DNS+补充的得分

<table> 
<thead>
<tr>
<th align="left">来源</th> 
<th align="left">规则</th>
<th align="left">类型</th>  
<th align="left">备注</th>  
</tr>
</thead>
<tbody>

<tr>
<td align="left">AdBlock DNS Filters</td> 
<td align="left"><a href="https://gcore.jsdelivr.net/gh/217heidai/adblockfilters/rules/adblockdns.txt" rel="nofollow">加速链接</a></td>
<td align="left">dns</td> 
<td align="left">条目多 100分</td> 
</tr>

<tr>
<td align="left">AbBlock List</td> 
<td align="left"><a href="https://gcore.jsdelivr.net/gh/xndeye/adblock_list/rule/dns.txt" rel="nofollow">加速链接</a></td>
<td align="left">dns</td> 
    <td align="left">条目中 95分</td> 
</tr>


<tr>
<td align="left">anti-AD 中文区规则</td> 
<td align="left"><a href="https://anti-ad.net/easylist.txt" rel="nofollow">官网链接</a></td>
<td align="left">dns</td> 
    <td align="left">条目少 95分</td> 
</tr>
</tbody>
<tbody>
<th align="left">补充</th> 

<tr>
<td align="left">AdblockFilters</td> 
<td align="left"><a href="https://gcore.jsdelivr.net/gh/217heidai/adblockfilters/rules/adblockfilters.txt" rel="nofollow">加速链接</a></td>
<td align="left">filter</td>
    <td align="left">模块拦截，建议启用</td> 
</tr>

<tr>
<td align="left">NoAppDownload</td> 
<td align="left"><a href="https://gcore.jsdelivr.net/gh/Noyllopa/NoAppDownload/NoAppDownload.txt" rel="nofollow">加速链接</a></td>
<td align="left">filter</td>
    <td align="left">下载按钮</td> 
</tr>

<tr>
<td align="left">禁止社交媒体图标列表</td>
<td align="left"><a href="https://easylist.to/easylist/fanboy-social.txt" rel="nofollow">加速链接</a></td>  
<td align="left">filter</td>
    <td align="left">社交按钮</td> 
</tr>

<tr>
<td align="left">ADgk 手机适配规则</td>
<td align="left"><a href="https://gcore.jsdelivr.net/gh/banbendalao/ADgk/ADgk.txt" rel="nofollow">加速链接</a></td> 
<td align="left">filter</td>
    <td align="left"></td> 
</tr>

<tr>
<td align="left">I don't care about cookies</td> 
<td align="left"><a href="https://www.i-dont-care-about-cookies.eu/abp/" rel="nofollow">加速链接</a></td>
<td align="left">filter</td>
    <td align="left"></td> 
</tr>

<tr>
<td align="left">乘风广告过滤规则</td>
<td align="left"><a href="https://gcore.jsdelivr.net/gh/xinggsf/Adblock-Plus-Rule/rule.txt" rel="nofollow">加速链接</a></td>
<td align="left">filter</td>
    <td align="left"></td> 
</tr>

<tr>
<td align="left">乘风视频过滤规则</td>
<td align="left"><a href="https://gcore.jsdelivr.net/gh/xinggsf/Adblock-Plus-Rule/mv.txt" rel="nofollow">加速链接</a></td>
<td align="left">filter</td> 
    <td align="left"></td> 
</tr>

<tr>
<td align="left">乘风小众视频规则</td>
<td align="left"><a href="https://gcore.jsdelivr.net/gh/xinggsf/Adblock-Plus-Rule/minority-mv.txt" rel="nofollow">加速链接</a></td>  
<td align="left">filter</td>
    <td align="left"></td> 
</tr>
</tbody>
</table>

# 上游规则
<details>
<summary>点击查看上游规则
<a href="https://github.com/217heidai/adblockfilters" rel="nofollow">[AdBlock DNS Filters]</a>
</summary>

| 规则                   |  类型  |                           原始链接                           |                           加速链接                           |
| :--------------------- | :----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| ADgk                   | filter | [原始链接](https://raw.githubusercontent.com/banbendalao/ADgk/master/ADgk.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/ADgk.txt) |
| AdGuard Base filter    | filter | [原始链接](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/AdGuard_Base_filter.txt) |
| AdGuard Chinese filter | filter | [原始链接](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/AdGuard_Chinese_filter.txt) |
| AdGuard DNS filter     | filter | [原始链接](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/AdGuard_DNS_filter.txt) |
| EasyList               | filter | [原始链接](https://easylist-downloads.adblockplus.org/easylist.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/EasyList.txt) |
| EasyList China         | filter | [原始链接](https://easylist-downloads.adblockplus.org/easylistchina.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/EasyList_China.txt) |
| EasyPrivacy            | filter | [原始链接](https://easylist-downloads.adblockplus.org/easyprivacy.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/EasyPrivacy.txt) |
| CJX's Annoyance List   | filter | [原始链接](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/CJX's_Annoyance_List.txt) |
| xinggsf rule           | filter | [原始链接](https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/rule.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/xinggsf_rule.txt) | 
| xinggsf mv             | filter | [原始链接](https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/mv.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/xinggsf_mv.txt) |
| 1Hosts (Lite)          |  dns   | [原始链接](https://raw.githubusercontent.com/badmojr/1Hosts/master/Lite/adblock.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/1Hosts_(Lite).txt) | 
| AdRules DNS List       |  dns   | [原始链接](https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/AdRules_DNS_List.txt) |
| Hblock                 |  dns   |  [原始链接](https://hblock.molinero.dev/hosts_adblock.txt)   | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/Hblock.txt) |
| NEO DEV HOST           |  dns   | [原始链接](https://raw.githubusercontent.com/neodevpro/neodevhost/master/lite_adblocker) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/NEO_DEV_HOST.txt) |
| OISD Basic             |  dns   |            [原始链接](https://abp.oisd.nl/basic/)            | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/OISD_Basic.txt) | 
| SmartTV Blocklist      |  dns   | [原始链接](https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/SmartTV_Blocklist.txt) |
| 1024 hosts             |  host  | [原始链接](https://raw.githubusercontent.com/Goooler/1024_hosts/master/hosts) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/1024_hosts.txt) |
| ad-wars hosts          |  host  | [原始链接](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/ad-wars_hosts.txt) |
| StevenBlack hosts      |  host  | [原始链接](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) | [加速链接](https://ghproxy.com/https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/StevenBlack_hosts.txt) |

</details>
<details>
<summary>点击查看上游规则
<a href="https://github.com/xndeye/adblock_list" rel="nofollow">[AbBlock List]</a>
    </summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard 基础过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard 移动广告过滤器</a></li>
    <li><a href="https://adguard.com/kb/zh-CN/general/ad-filtering/adguard-filters/">AdGuard 防跟踪保护过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL跟踪过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard 恼人广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard 解除搜索广告和自我推销过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard 中文过滤器</a></li>
    <li><a href="https://adaway.org/hosts.txt">AdAway Default Blocklist</a></li>
    <li><a href="https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt">WindowsSpyBlocker</a></li>
    <li><a href="https://github.com/jdlingyu/ad-wars">ad-wars(大圣净化)</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://github.com/sbwml/halflife-list">halflife-list</a></li>
    <li><a href="https://raw.githubusercontent.com/Goooler/1024_hosts/master/hosts">1024_hosts</a></li>
    <li><a href="https://filters.adavoid.org/ultimate-ad-filter.txt">AdBlocker Ultimate</a></li>
    <li><a href="https://raw.githubusercontent.com/damengzhu/banad/main/jiekouAD.txt">damengzhu/banad</a></li>
    <li><a href="https://raw.githubusercontent.com/Noyllopa/NoAppDownload/master/NoAppDownload.txt">NoAppDownload</a></li>
    <li><a href="https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt">CJX's Annoyance List</a></li>

</ul>
</details>
<details>
<summary>点击查看上游规则
<a href="https://github.com/privacy-protection-tools/anti-AD" rel="nofollow">[anti-AD]</a>
    </summary>
  
- [AdguardTeam/AdguardFilters](https://github.com/AdguardTeam/AdguardFilters) - AdGuard Content Blocking Filters
- [fanboy-annoyance](https://easylist.to/easylist/fanboy-annoyance.txt) - 优秀的easylist列表
- [notracking/hosts-blocklists-scripts](https://github.com/notracking/hosts-blocklists-scripts) - 提供无效域名和无效hosts列表
- [Adblock Plus](https://adblockplus.org/) - 畅游清爽洁净的网络！
- [neoFelhz/neohosts](https://github.com/neoFelhz/neohosts) - 自由·负责·克制 去广告 Hosts 项目
- [vokins/yhosts](https://github.com/vokins/yhosts) - yhosts（该源已停止维护）
- [cjx82630/cjxlist](https://github.com/cjx82630/cjxlist) - Adblock Plus EasyList Lite与CJX's Annoyance List
- _[@rufengsuixing](https://github.com/rufengsuixing) 提出的jsDelivr加速过滤列表下载的建议_
- _[@xlighting2017](https://github.com/xlighting2017) 提供的[surge格式建议](https://github.com/privacy-protection-tools/anti-AD/issues/29)_
- [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) - 一些常见APP的广告 @[wchqybs](https://github.com/wchqybs) in [#79](https://github.com/privacy-protection-tools/anti-AD/issues/79)
- [ADgk.txt](https://github.com/banbendalao/ADgk) - 鸣谢 坂本dalao
- [jdlingyu/ad-wars](https://github.com/jdlingyu/ad-wars) - 只是 ad-wars 的帮助文档
- [hoshsadiq/adblock-nocoin-list](https://github.com/hoshsadiq/adblock-nocoin-list) - 恶意挖矿屏蔽列表
- [easylist.to](https://easylist.to/) - 感谢提供出色的easylist
- [ZeroDot1/CoinBlockerLists](https://gitlab.com/ZeroDot1/CoinBlockerLists) - 屏蔽恶意劫持挖矿
- [crazy-max/WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker/) - to block spying and tracking on Windows systems.
</details>
