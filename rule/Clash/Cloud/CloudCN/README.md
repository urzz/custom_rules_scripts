# 🧸 国内云计算

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN与DOMAIN--KEYWORD合并-9cf) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

国内云计算规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2025-06-06 09:18:51

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| IP-CIDR | 216  | 
| IP-CIDR6 | 15  | 
| TOTAL | 231  | 


## Clash 

#### 使用说明
- CloudCN.yaml，请使用 behavior: "classical"。
- CloudCN_Resolve.yaml，请使用 behavior: "classical"。

#### 配置建议
- CloudCN.yaml 单独使用。
- CloudCN_Resolve.yaml 单独使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/urzz/custom_rules_scripts/master/rule/Clash/Cloud/CloudCN/CloudCN.yaml

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/urzz/custom_rules_scripts@master/rule/Clash/Cloud/CloudCN/CloudCN.yaml

**MASTER分支 GHProxy (每日更新)**

https://ghproxy.com/https://raw.githubusercontent.com/urzz/custom_rules_scripts/master/rule/Clash/Cloud/CloudCN/CloudCN.yaml

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/urzz/custom_rules_scripts/release/rule/Clash/Cloud/CloudCN/CloudCN.yaml

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/urzz/custom_rules_scripts@release/rule/Clash/Cloud/CloudCN/CloudCN.yaml

**RELEASE分支 GHProxy (不定时更新)**

https://ghproxy.com/https://raw.githubusercontent.com/urzz/custom_rules_scripts/release/rule/Clash/Cloud/CloudCN/CloudCN.yaml

## 子规则/排除规则

当前分流规则，已包含以下子规则，除非特殊需求否则不建议重复引用：
| 子规则  |  |  |  |  | 
| ---- | ---- | ---- | ---- | ----  |
| 360Cloud | BaiduCloud | HuaweiCloud | JingDongCloud | KingsoftCloud  | 
| NeteaseCloud | TencentCloud  |  |  |  | 


## 数据来源

《国内云计算》的数据来自以下链接，如与本项目的《国内云计算》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/360CCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/BaiduCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/HuaweiCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/JingdongCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/KingsoftCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/NeteaseCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN/TencentCCC.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-CN.list


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。