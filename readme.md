
# imt-devops

![版本1.2](https://img.shields.io/badge/stable-1.2-brightgreen.svg?logo=Pinboard&logoColor=white)
![mutaoinc](https://img.shields.io/badge/author-mutaoinc-blue.svg)
![licence](https://img.shields.io/badge/licence-Apache2.0-lightgrey.svg)

> imt-devops 是`南京慕涛网络科技有限公司`基于`Tortoise SVN`,`BT-Panel`,`Ding-Talk Robot`等工具打造的，适用于50人以内小规模开发团队的开发运维工作流。  

## 愿景，有何不同  

imt-devops定位于小规模开发，致力于协调好产品需求管理、项目管理、技术管理的综合效益，我们的项目具有如下显著特征：  

- 项目周期`30工作日`以内，开发周期`20工作日`以内
- 开发者不多于`4人`，项目主管不多于`2人`，但必须有全职项目主管实施工作流，最低适用2人开发1人需求管理
- `非研发`性质项目，即不适用于开源生态的传统`闭源项目`
- 根据线上需求，对项目文件（设计稿，产品技术文档，源文件）希望进行`精细版本控制`，但只能进行关键审查
- 出于运营需要，你需要对项目进行`自动化运维`，包括自动部署、容灾冷备、数据热备
- 尤其适用于`Web 技术栈`，将更好的发挥日常生产工具潜能

## 构成概述

如果你的团队开发具有上述特征，那么`imt-devops`将是你绝佳的选择，反之你也可以从中参考了解精小团队开发之道。为了实现这一软件开发愿景，imt-devops吸纳了如下工具，如果不够了解你可以快速查看`工具流实用手册`：  

| 工具名称 | 版本要求 | 官网 | 备注 |
| ------ | ------ | ------ | ------ |
| 基准工具 |  |  |  |
| Windows 工作机 | 桌面版windows 7、服务版2012或以上 | --- | 工具链全面、高效 |
| CentOS 服务机 | 7.0或以上 | --- | 稳定、免费 |
| VisualSVN Server | 3.8或以上 | <https://www.visualsvn.com> | 简明、免费商用 |
| Tortoise SVN | 1.10.0或以上 | <https://tortoisesvn.net> | 简明、强大 |
| 钉钉 | ~ | <https://www.dingtalk.com/> | 职场通讯与生产力工具 |
| 宝塔面板 | 5.9.0或以上 | <https://www.bt.cn/> | 强大服务器Web面板 |
| 拓展工具 |  |  |  |
| Yapi | 1.3.19或以上 | <https://yapi.ymfe.org> | 免费、稳定维护 |
| 语雀 | ~ | <https://www.yuque.com> | 企业级知识管理 |
| 磨刀 | ~ | <https://modao.cc/> | 优秀易用原型设计 |  

（附注：`~`标记无法或无需版本声明，`---`标记无需补充说明）

形成如下主体构成：

- 资源管理核心的`工具流`
- 简明可维护的`文档流`
- 集约内外援引的`信息流`  

## 准备去尝试

以项目成功实施，和质量具备保证为目的实施项目，我们认为还应该具备以下条件。如果条件不足，应该视为项目本身不具备在受限资源内完成的可行性，应考虑筹备项目必要条件或增加投入后实施。

- 需求供口

- 产品规划

- 时间资源

- 人力资源

- 维护升级

## 投产即应用  

### [前言](doc/content/c0a_前言.md)  

### [注解规范](doc/content/c0b_注解规范.md)  

### 正文  

1. [文档管理](doc/content/c1_文档管理.md)  
  1.1 [优质需求管理](doc/content/c1_文档管理.md)  
  1.2 [分发协同](doc/content/c1_文档管理.md)  
  1.3 [效用权益](doc/content/c1_文档管理.md)  
  1.4 [组织角色](doc/content/c1_文档管理.md)
2. [版本管理](doc/content/c2_版本管理.md)  
  2.1 [版本工具](doc/content/c2_版本管理.md)  
  2.2 [研发版本](doc/content/c2_版本管理.md)  
  2.3 [冲突处理](doc/content/c2_版本管理.md)  
3. [沟通协同](doc/content/c3_沟通协同.md)  
  3.1 [信息集约](doc/content/c3_沟通协同.md)  
  3.2 [透明公共](doc/content/c3_沟通协同.md)  
4. [项目管理](doc/content/c4_项目管理.md)  
  4.1 [周期管理](doc/content/c4_项目管理.md)  
  4.2 [人力资源](doc/content/c4_项目管理.md)  
  4.3 [风险管理](doc/content/c4_项目管理.md)  
5. [基线与质量管理](doc/content/c5_基线与质量管理.md)  
  5.1 [基线版本](doc/content/c5_基线与质量管理.md)  
  5.2 [备份版本](doc/content/c5_基线与质量管理.md)  
  5.3 [助理测试](doc/content/c5_基线与质量管理.md)
6. [维护升级](doc/content/c6_维护升级.md)  
  6.1 [基础运维](doc/content/c6_维护升级.md)  
  6.2 [安全运维](doc/content/c6_维护升级.md)  
  6.3 [自动化运维](doc/content/c6_维护升级.md)  
  6.4 [开发计划](doc/content/c6_维护升级.md)  
7. [反馈总结](doc/content/c7_反馈总结.md)  
  7.1 [知识管理](doc/content/c7_反馈总结.md)  
8. [再谈软件工作流](doc/content/c8_再谈工作流.md)  
  8.1 [可追溯](doc/content/c8_再谈工作流.md)  
  8.2 [可维护](doc/content/c8_再谈工作流.md)  
  8.3 [可管理](doc/content/c8_再谈工作流.md)  
  8.4 [效能，不可预见](doc/content/c8_再谈工作流.md)  
  8.5 [发展，不可形状](doc/content/c8_再谈工作流.md)  

### 附录

1. 工具流实用手册  
  1.1 [SVN](doc/manual/t1_SVN规范管理.md)  
  1.2 [宝塔面板](doc/manual/t2_宝塔面板精益使用.md)  
  1.3 [Yapi](doc/manual/t3_YApi实用参考.md)  
  1.4 [语雀](doc/manual/t4_语雀实用参考.md)  
  1.5 [墨刀](doc/manual/t5_墨刀实用参考.md)  
2. 文档流实用手册  
  2.1 [文档编制精益](doc/manual/d1_文档编制精益.md)  

## 参考鸣谢

## 随便谈谈

## 权益声明
