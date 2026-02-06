# batch-picking-tool

嘉立创EDA专业版 批量零件选择工具，让原理图/PCB的零件选择、复制、粘贴操作更丰富、更便捷

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![EDA Compatible](https://img.shields.io/badge/eda-%5E2.3.0-brightgreen.svg)](https://pro.lceda.cn/)

## 工具介绍

**Batch Picking tool** 是为嘉立创EDA专业版开发的专属扩展工具，适配原理图（SCH）和PCB两大核心编辑环境，针对性优化零件的批量选择、复制、粘贴流程，补充原生工具的操作能力，大幅提升硬件设计中的零件操作效率。

### 核心特性

- 双环境支持：同时适配**原理图（SCH）** 和**PCB**编辑场景，操作逻辑统一
- 操作优化：简化零件批量选择逻辑，贴合实际硬件设计的操作习惯
- 功能增强：丰富的批量复制/粘贴能力，保留零件完整属性与关联信息
- 轻量化：无额外依赖扩展，集成后不影响软件原有运行效率

## 适用环境

- 运行平台：嘉立创EDA专业版（版本要求 ≥2.3.0）
- 支持系统：Windows / macOS / Linux（与嘉立创EDA专业版系统兼容）

## 安装使用

### 本地包安装

1. 下载本扩展的 `.lcedaext` 格式压缩包
2. 打开嘉立创EDA专业版，进入「扩展中心」→「本地安装」
3. 选择下载的压缩包完成安装，重启软件后即可使用

## 操作入口

工具按**原理图/PCB环境独立设计入口**，安装完成后在顶部菜单栏直接访问，操作路径如下：

1. **原理图（SCH）环境**：顶部菜单栏 →「SCH Edit」→「Batch Picking tool」
2. **PCB环境**：顶部菜单栏 →「PCB Edit」→「Batch Picking tool」
3. 工具信息：对应环境菜单栏入口 →「About...」可查看工具版本等基础信息

## 核心功能

- 批量选择：支持框选、点选组合方式，快速选中目标零件组
- 批量复制：一键复制选中零件，完整保留零件属性、引脚关联等信息
- 批量粘贴：粘贴适配目标画布，支持零件属性的批量调整与复用

## 问题反馈

使用过程中遇到问题、bug，或有功能优化建议，可通过官方通道反馈：
[嘉立创EDA官方反馈页面](https://lceda.cn/page/feedback?originPage=other)

## 开发者信息

- 发布者：内边
- 联系邮箱：2280support@lceda.cn
- 工具主页：[嘉立创EDA专业版](https://pro.lceda.cn)

## 致谢

> 本扩展工具基于 [LCExtensions](https://github.com/lceda/LCExtensions) 框架开发，感谢 LCExtensions 团队提供的优秀基础开发框架，为工具的快速实现与稳定运行奠定了核心基础。

> 本扩展工具的前端界面基于 [**layui**](https://layui.dev/) 框架进行开发，感谢 layui 团队提供的轻量、易用的前端解决方案。

> 本扩展工具的README文档由 [**豆包AI**](https://www.doubao.com/) 倾情助攻，感谢豆包AI全程陪聊写文档，主打一个摸鱼搭子式高效输出😜。

## 开源许可

本扩展工具基于 **Apache-2.0** 开源协议发布，可遵循协议要求进行二次开发、分发与使用。

## 开源地址

[https://github.com/ugpinout/JLC-batch-picking-tool/](https://github.com/ugpinout/JLC-batch-picking-tool/)
