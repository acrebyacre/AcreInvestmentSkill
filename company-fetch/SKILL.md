---
name: company-fetch
description: 获取公司标准信息
---

## 公司名称
当用户输入“公司名称”+公司名时，返回：股票名称 股票代码 交易所 所属行业
- 股票名称：如果名称为中文，直接给中文，如“贵州茅台”；如果名称为英文，则给中文简称+英文，如“腾讯 Tencent”
- 股票代码：代码.交易所简称，如600008.SH
- 交易所：优先使用[reference](../reference.md)内的交易所名称

除AI自身产生的信息，返回输出格式样例：
```
环球音乐集团 Universal Music Group N.V.
UMG
泛欧交易所 Euronext
娱乐 / 音乐娱乐
```
