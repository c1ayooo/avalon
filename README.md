# AVALON

> 剑鞘。收纳、归类、随时可取。

fork 的东西按用途分六类，每类一个 GitHub topic：`avalon-recon` / `avalon-poc` / `avalon-c2` / `avalon-cred` / `avalon-fuzz` / `avalon-platform`。
搜索 `topic:avalon-poc` 就是一整筐，不用再翻仓库列表。

GitHub 没有真正的目录，所以这里用「索引仓库 + topic」做归档：仓库名一个都不改，fork 关系与上游同步全部保留。

## 侦察与测绘（17）

<sub>资产发现、指纹识别、目录与域名枚举</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [ENScan_GO](https://github.com/c1ayooo/ENScan_GO) | [aqiMMM/ENScan_GO](https://github.com/aqiMMM/ENScan_GO) | 一款基于各大企业信息API的工具，解决在遇到的各种针对国内企业信息收集难题。一键收集控股公司ICP备案、APP、小程序、微信公众号等信息聚合… |
| [Kunyu](https://github.com/c1ayooo/Kunyu) | [knownsec/Kunyu](https://github.com/knownsec/Kunyu) | Kunyu, more efficient corporate asset collection |
| [TideFinger](https://github.com/c1ayooo/TideFinger) | [TideSec/TideFinger](https://github.com/TideSec/TideFinger) | TideFinger——指纹识别小工具，汲取整合了多个web指纹库，结合了多种指纹检测方法，让指纹检测更快捷、准确。 |
| [WhatWeb](https://github.com/c1ayooo/WhatWeb) | [urbanadventurer/WhatWeb](https://github.com/urbanadventurer/WhatWeb) | Next generation web scanner |
| [ZoomEye-python](https://github.com/c1ayooo/ZoomEye-python) | [knownsec/ZoomEye-python](https://github.com/knownsec/ZoomEye-python) | ZoomEye-python: The official Python library and CLI by Knownsec 404 Te… |
| [dismap](https://github.com/c1ayooo/dismap) | [zhzyker/dismap](https://github.com/zhzyker/dismap) | Asset discovery and identification tools 快速识别 Web 指纹信息，定位资产类型。辅助红队快速定位… |
| [fingerprint](https://github.com/c1ayooo/fingerprint) | [r0eXpeR/fingerprint](https://github.com/r0eXpeR/fingerprint) | 各种工具指纹收集分享 |
| [fingers](https://github.com/c1ayooo/fingers) | [chainreactors/fingers](https://github.com/chainreactors/fingers) | ALLINONE framework and technology detect lib |
| [fscan](https://github.com/c1ayooo/fscan) | [shadow1ng/fscan](https://github.com/shadow1ng/fscan) | 一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。(An intranet comprehensive scanning tool, e… |
| [gogo](https://github.com/c1ayooo/gogo) | [chainreactors/gogo](https://github.com/chainreactors/gogo) | 面向红队的, 高性能高度自由可拓展的自动化扫描引擎 / A highly controllable and extensionable au… |
| [httpx](https://github.com/c1ayooo/httpx) | [projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) | httpx is a fast and multi-purpose HTTP toolkit that allows running mul… |
| [ksubdomain](https://github.com/c1ayooo/ksubdomain) | [boy-hack/ksubdomain](https://github.com/boy-hack/ksubdomain) | Subdomain enumeration tool, asynchronous dns packets, use pcap to scan… |
| [qscan](https://github.com/c1ayooo/qscan) | [qi4L/qscan](https://github.com/qi4L/qscan) | Lightning-fast internal network scanner |
| [srcradar](https://github.com/c1ayooo/srcradar) | [usdagfhjkda/srcradar](https://github.com/usdagfhjkda/srcradar) | SRC 资产测绘编排流水线:企业实体图谱(ENScan) → 主动测绘(subfinder/dnsx/naabu/httpx 4 阶段) →… |
| [urlfounder](https://github.com/c1ayooo/urlfounder) | [chainreactors/urlfounder](https://github.com/chainreactors/urlfounder) | Fast passive URL enumeration tool. |
| [wafw00f](https://github.com/c1ayooo/wafw00f) | [EnableSecurity/wafw00f](https://github.com/EnableSecurity/wafw00f) | WAFW00F allows one to identify and fingerprint Web Application Firewal… |
| [wappalyzergo](https://github.com/c1ayooo/wappalyzergo) | [projectdiscovery/wappalyzergo](https://github.com/projectdiscovery/wappalyzergo) | A high performance go implementation of Wappalyzer Technology Detectio… |

## 漏洞验证与 PoC（25）

<sub>CVE PoC、扫描引擎、模板与漏洞情报</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [CVE-2024-53677-S2-067](https://github.com/c1ayooo/CVE-2024-53677-S2-067) | [TAM-K592/CVE-2024-53677-S2-067](https://github.com/TAM-K592/CVE-2024-53677-S2-067) | A critical vulnerability, CVE-2024-53677, has been identified in the p… |
| [CVE-2026-109618](https://github.com/c1ayooo/CVE-2026-109618) | [zhaoboy9692/CVE-2026-109618](https://github.com/zhaoboy9692/CVE-2026-109618) | PoC CVE-2026-109618 / -109619 (PHP session.upload_progress heap UAF) |
| [CVE-2026-109619](https://github.com/c1ayooo/CVE-2026-109619) | [zhaoboy9692/CVE-2026-109618_](https://github.com/zhaoboy9692/CVE-2026-109618_) |  |
| [CVE-2026-34197](https://github.com/c1ayooo/CVE-2026-34197) | [KONDORDEVSECURITYCORP/CVE-2026-34197](https://github.com/KONDORDEVSECURITYCORP/CVE-2026-34197) | CVE-2026-34197 — Apache ActiveMQ RCE via Jolokia API / PoC Exploit |
| [CVE-2026-34486](https://github.com/c1ayooo/CVE-2026-34486) | [striga-ai/CVE-2026-34486](https://github.com/striga-ai/CVE-2026-34486) | EncryptInterceptor fail-open bypass in Apache Tomcat Tribes clustering… |
| [CVE-2026-42530](https://github.com/c1ayooo/CVE-2026-42530) | [v4ltonn/CVE-2026-42530](https://github.com/v4ltonn/CVE-2026-42530) | Scanner PoC for CVE-2026-42530 -- nginx 1.31.0-1.31.1 HTTP/3 QPACK enc… |
| [CVE-2026-48907](https://github.com/c1ayooo/CVE-2026-48907) | [ywh-jfellus/CVE-2026-48907](https://github.com/ywh-jfellus/CVE-2026-48907) | PoC for CVE-2026-48907 - Joomla! JCE extension < 2.9.99.5 unauthentica… |
| [CVE-2026-48908-PoC](https://github.com/c1ayooo/CVE-2026-48908-PoC) | [papageo75/CVE-2026-48908-PoC](https://github.com/papageo75/CVE-2026-48908-PoC) | Unauthenticated RCE PoC for CVE-2026-48908 — SP Page Builder for Jooml… |
| [CVE-2026-49952](https://github.com/c1ayooo/CVE-2026-49952) | [passwa11/CVE-2026-49952](https://github.com/passwa11/CVE-2026-49952) | Chaining Security Bugs in Discuz! X5.0: from Race Condition to Pre-Aut… |
| [CVE-2026-55200](https://github.com/c1ayooo/CVE-2026-55200) | [0xBlackash/CVE-2026-55200](https://github.com/0xBlackash/CVE-2026-55200) | CVE-2026-55200 |
| [CVE-2026-84645](https://github.com/c1ayooo/CVE-2026-84645) | [mhtsec/CVE-2026-84645](https://github.com/mhtsec/CVE-2026-84645) | Jenkins PersistenceRoot Deserialization RCE (SECURITY-3972) — PoC & an… |
| [JYso](https://github.com/c1ayooo/JYso) | [qi4L/JYso](https://github.com/qi4L/JYso) | JNDIExploit or a ysoserial. |
| [PoC-in-GitHub](https://github.com/c1ayooo/PoC-in-GitHub) | [nomi-sec/PoC-in-GitHub](https://github.com/nomi-sec/PoC-in-GitHub) | 📡 PoC auto collect from GitHub. ⚠️ Be careful Malware. |
| [afrog](https://github.com/c1ayooo/afrog) | [zan8in/afrog](https://github.com/zan8in/afrog) | A Security Tool for Bug Bounty, Pentest and Red Teaming. |
| [ai_bobao](https://github.com/c1ayooo/ai_bobao) | [wr0x00/ai_bobao](https://github.com/wr0x00/ai_bobao) | AI 赋能的漏洞播报系统，AI 根据公开的漏洞思路自动生成 PoC、漏洞简介、漏洞原理、攻击范围，自动落库存储nuclei格式，24 小时监… |
| [kunpeng](https://github.com/c1ayooo/kunpeng) | [opensec-cn/kunpeng](https://github.com/opensec-cn/kunpeng) | kunpeng是一个Golang编写的开源POC框架/库，以动态链接库的形式提供各种语言调用，通过此项目可快速开发漏洞检测类的系统。 |
| [neutron](https://github.com/c1ayooo/neutron) | [chainreactors/neutron](https://github.com/chainreactors/neutron) | nano nuclei engine. no side effect. |
| [next-16.2.4-pocs](https://github.com/c1ayooo/next-16.2.4-pocs) | [dwisiswant0/next-16.2.4-pocs](https://github.com/dwisiswant0/next-16.2.4-pocs) | Next.js v16.2.4 Security PoC Collection (CVE-2026-23870, CVE-2026-4457… |
| [nextssrf](https://github.com/c1ayooo/nextssrf) | [ynsmroztas/nextssrf](https://github.com/ynsmroztas/nextssrf) | NextSSRF — CVE-2026-44578 Scanner & Exploit          ║ ║   Next.js Web… |
| [nuclei](https://github.com/c1ayooo/nuclei) | [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | Nuclei is a fast, customizable vulnerability scanner powered by the gl… |
| [php2shell](https://github.com/c1ayooo/php2shell) | [iQingshan/php2shell](https://github.com/iQingshan/php2shell) |  |
| [pocsuite3](https://github.com/c1ayooo/pocsuite3) | [knownsec/pocsuite3](https://github.com/knownsec/pocsuite3) | pocsuite3 is an open-sourced remote vulnerability testing framework de… |
| [proton](https://github.com/c1ayooo/proton) | [chainreactors/proton](https://github.com/chainreactors/proton) | nuclei file protocol engine |
| [templates](https://github.com/c1ayooo/templates) | [chainreactors/templates](https://github.com/chainreactors/templates) | chainreactors templates |
| [watchTowr-vs-Splunk-CVE-2026-20253](https://github.com/c1ayooo/watchTowr-vs-Splunk-CVE-2026-20253) | [watchtowrlabs/watchTowr-vs-Splunk-CVE-2026-20253](https://github.com/watchtowrlabs/watchTowr-vs-Splunk-CVE-2026-20253) |  |

## 控制与通道（3）

<sub>C2 框架、隧道与多级代理</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [Stowaway](https://github.com/c1ayooo/Stowaway) | [ph4ntonn/Stowaway](https://github.com/ph4ntonn/Stowaway) | 👻Stowaway -- Multi-hop Proxy Tool for pentesters |
| [chisel](https://github.com/c1ayooo/chisel) | [jpillora/chisel](https://github.com/jpillora/chisel) | A fast TCP/UDP tunnel over HTTP |
| [rem](https://github.com/c1ayooo/rem) | [chainreactors/rem](https://github.com/chainreactors/rem) | proxy/tunnel everything for red team! |

## 凭据与口令（4）

<sub>口令恢复、浏览器凭据、验证码识别、数据库利用</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [HackBrowserData](https://github.com/c1ayooo/HackBrowserData) | [moonD4rk/HackBrowserData](https://github.com/moonD4rk/HackBrowserData) | Extract and decrypt browser data, supporting multiple data types, runn… |
| [MDUT](https://github.com/c1ayooo/MDUT) | [SafeGroceryStore/MDUT](https://github.com/SafeGroceryStore/MDUT) | MDUT - Multiple Database Utilization Tools |
| [ddddocr](https://github.com/c1ayooo/ddddocr) | [sml2h3/ddddocr](https://github.com/sml2h3/ddddocr) | 带带弟弟 通用验证码识别OCR pypi版 |
| [hashcat](https://github.com/c1ayooo/hashcat) | [hashcat/hashcat](https://github.com/hashcat/hashcat) | World's fastest and most advanced password recovery utility |

## 模糊测试（2）

<sub>目录与 HTTP Fuzz</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [ffuf](https://github.com/c1ayooo/ffuf) | [ffuf/ffuf](https://github.com/ffuf/ffuf) | Fast web fuzzer written in Go |
| [spray](https://github.com/c1ayooo/spray) | [chainreactors/spray](https://github.com/chainreactors/spray) | 最好用最智能最可控的目录Fuzz工具 / The most powerful, user-friendly, intelligent, an… |

## 平台与 Agent（14）

<sub>AI 安全 agent、前端组件、分析与协作平台</sub>

| 仓库 | 上游 | 说明 |
|---|---|---|
| [BurpCrypto](https://github.com/c1ayooo/BurpCrypto) | [whwlsfb/BurpCrypto](https://github.com/whwlsfb/BurpCrypto) | BurpCrypto is a collection of burpsuite encryption plug-ins, support A… |
| [CDK](https://github.com/c1ayooo/CDK) | [cdk-team/CDK](https://github.com/cdk-team/CDK) | 📦  Make security testing of K8s, Docker, and Containerd easier. |
| [HaE](https://github.com/c1ayooo/HaE) | [overspace-labs/HaE](https://github.com/overspace-labs/HaE) | HaE - Highlighter and Extractor, Empower ethical hacker for efficient … |
| [Honeynet](https://github.com/c1ayooo/Honeynet) | [Ta0ing/Honeynet](https://github.com/Ta0ing/Honeynet) | 蜜网 |
| [arco-design](https://github.com/c1ayooo/arco-design) | [arco-design/arco-design](https://github.com/arco-design/arco-design) | A comprehensive React UI components library based on Arco Design |
| [cyber-agent](https://github.com/c1ayooo/cyber-agent) | [chainreactors/cyber-agent](https://github.com/chainreactors/cyber-agent) | Minimal, modular LLM agent framework — transport/protocol/provider/run… |
| [cyber-harness](https://github.com/c1ayooo/cyber-harness) | [chainreactors/cyber-harness](https://github.com/chainreactors/cyber-harness) | AI-driven pi-like agent for cyber security — single binary for  pentes… |
| [cyber-ui](https://github.com/c1ayooo/cyber-ui) | [chainreactors/cyber-ui](https://github.com/chainreactors/cyber-ui) | Shared frontend UI component library — @aspect/theme, @aspect/ui, @asp… |
| [dsh-our-free-model](https://github.com/c1ayooo/dsh-our-free-model) | [Ebony-Vinyl/dsh-our-free-model](https://github.com/Ebony-Vinyl/dsh-our-free-model) | 在 dsh 里装上这个插件即可，无需登录、注册或填 API Key，就能使用包括 DeepSeek V4.1 Flash、Kimi K3 在… |
| [f8x](https://github.com/c1ayooo/f8x) | [ffffffff0x/f8x](https://github.com/ffffffff0x/f8x) | 红/蓝队环境自动化部署工具 / Red/Blue team environment automation deployment tool |
| [impacket](https://github.com/c1ayooo/impacket) | [fortra/impacket](https://github.com/fortra/impacket) | Impacket is a collection of Python classes for working with network pr… |
| [picker](https://github.com/c1ayooo/picker) | [chainreactors/picker](https://github.com/chainreactors/picker) | 将repo变成RSS订阅,文章整理归档, 讨论的社区 |
| [rea](https://github.com/c1ayooo/rea) | [morluto/rea](https://github.com/morluto/rea) | Reverse engineer anything with agents, from app behavior down to nativ… |
| [taste-skill](https://github.com/c1ayooo/taste-skill) | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Agent skills that give coding agents taste: art direction, reference i… |

## 自有仓库

| 仓库 | 说明 |
|---|---|
| [4zrec](https://github.com/c1ayooo/4zrec) | AI 自主渗透测试系统 —— LLM 多 agent 驱动,eino (ADK) 底座 |
| [4zreco-sliver-fork-old](https://github.com/c1ayooo/4zreco-sliver-fork-old) | 4zreco sliver 二开源码树（构建时由 bootstrap.sh 拉取） |
| [capkit](https://github.com/c1ayooo/capkit) | 通用渗透能力内核库（Go）：工具契约、门禁、证据链 |
| [m0re](https://github.com/c1ayooo/m0re) |  |
| [xs-bigdan-knowledge](https://github.com/c1ayooo/xs-bigdan-knowledge) | xs-bigdan knowledge 目录存档（fork 自 lycheer1126/xs-bigdan，仅 knowledge 子目录） |
| [yakit-send-to-csai](https://github.com/c1ayooo/yakit-send-to-csai) | Yakit 右键插件：把数据包直投 CSAI(4zreco) 平台，agent 自动开测（集成令牌鉴权/项目角色可选/多选批量发送） |
| [yuque-saber](https://github.com/c1ayooo/yuque-saber) | Hermes Skill for Yuque knowledge base automation |

---

`classify.json` 是分类的机器可读版本；新增 fork 后把它加进对应数组，再跑 `gh api -X PUT repos/c1ayooo/<repo>/topics -f names[]=avalon -f names[]=avalon-<cat>` 即可归位。
