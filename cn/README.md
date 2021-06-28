# 应用开放模型（OAM）规范

[![Gitter](https://badges.gitter.im/oam-dev/community.svg)](https://gitter.im/oam-devcommunity?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![License: MIT](https://img.shields.io/badge/License-OWF-yellow)](https://github.com/oam-dev/spec/blob/master/LICENSE)
[![TODOs](https://badgen.net/https/api.tickgit.com/badgen/github.com/oam-dev/spec)](https://www.tickgit.com/browse?repo=github.com/oam-dev/spec)
[![Follow on Twitter](https://img.shields.io/twitter/follow/oam_dev.svg?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=oam_dev)

应用开放模型 (OAM) 是一个与运行时无关的云原生应用定义模型。

应用开放模型专注于**应用**而不是容器或编排，基于一致的高阶API为应用部署模型带来模块化、 可扩展和可移植的特性。这是在包括Kubernetes、云乃至IoT设备的混合云环境中启用简单但可靠的应用交付工作流的关键.

## 简介

_"开发者是从应用架构角度考虑问题，而不是基础设施。"_

![如何工作](../assets/how-it-works.png)

### 为什么要使用应用开放模型？

脱离应用上下文环境来管理应用很困难：

- 开发者需要在基础设施细节而不是在应用上花时间，如ingress、标签、DNS等, 并且学习基础设施如何实现。
- 不可扩展 - 上层平台可能引入，但几乎可以肯定都是，应用的需求很快就会超出平台的能力。
- 运行时锁定 - 应用描述语言与运行时基础设施紧耦合，这对如何在混合云环境下配置、开发、运维应用影响重大。

通过应用开放模型，我们提出一种以应用为中心的方法：

- 应用优先 - 使用独立的模型定义应用，运维行为也作为应用定义的部分，而不包括基础设施。
- 清晰度和可扩展度 - 与其他方式不同，采用开放标准使基础设施能力模块化为适配需求的、可重用的部件。
- 运行时无关 - 无论在自建集群、云服务商还是边缘设备，均提供部署、运维应用的一致体验。

## 阅读规范

|                                | 上一版发布 | 最新发布|    草案                  |
| :----------------------------: | :-----------------: | :------------: |:--------------------------------: |
| OAM规范              | [v0.1.0](https://github.com/oam-dev/spec/releases/tag/v0.1.0), [v0.2.1](https://github.com/oam-dev/spec/releases/tag/v0.2.1) | [v0.3.0](SPEC.md) |  --  |

## 实战参考

最新版规范适用(推荐):
- [KubeVela](https://github.com/oam-dev/kubevela): 基于OAM的应用部署系统，提供Kubernetes控制面。

`v0.1.x` 版规范适用:
- [Rudr](https://github.com/oam-dev/rudr): Kubernetes上的OAM参考实现。

## 社区

### 里程碑

访问[里程碑页面](https://github.com/oam-dev/spec/里程碑) 获取里程碑概况和描述。

### 问题分拣

问题分类排入里程碑主要通过社区双周电话会议的方式进行。在电话会议上，问题可能排入、移出或者变更里程碑。

### 贡献

修订本规范请参见[贡献](CONTRIBUTING.md)指南.

最简单的贡献方式即参与社区讨论，有多种方式可以参与：

| 项目        | 取值  |
|---------------------|---|
| 邮件列表| https://groups.google.com/forum/#!forum/oam-dev |
| OAM社区双周在线会议 (英语) | [Zoom](https://us02web.zoom.us/j/88638962723?pwd=MVhCZnNub2t0R3BmMUNEWE9vendLUT09), [Meeting Notes](https://docs.google.com/document/d/1nqdFEyULekyksFHtFvgvFAYE-0AMHKoS3RMnaKsarjs), [Records (YouTube)](https://www.youtube.com/channel/UCSCTHhGI5XJ0SEhDHVakPAA/)  |
| OAM亚太社区双周在线会议 (中文)| [Zoom](https://us02web.zoom.us/j/2804785490?pwd=ZTN4ZU03UTlBZzlmVHIwTndINGM3UT09), [Meeting Notes](https://shimo.im/docs/w8CgdyYGWjtYJ3XP), [Records (BiliBili)](https://space.bilibili.com/180074935?spm_id_from=333.788.b_765f7570696e666f.2) |
| 实时通讯频道      | https://gitter.im/oam-dev/ |
| Twitter      | [@oam_dev](https://twitter.com/oam_dev) |

