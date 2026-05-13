# Projects

这里整理了我在 GitHub 与 Gitee 上的公开项目，用作主页 pin 展示。项目覆盖业务系统、主机监控、计算机视觉、机器人/硬件、效率工具与课程练习。

> Updated: 2026-05-13

## 精选项目

| 项目 | 类型 | 技术/方向 | 简介 |
| --- | --- | --- | --- |
| [party-building-system](https://github.com/Lukas-VI/party-building-system) | 业务系统 | JavaScript, Node.js, MySQL, Vue/H5 | 高校党员发展管理系统，覆盖服务号 H5、PC 后台、角色权限、流程审核、材料上传、统计分析与消息提醒。 |
| [luminitor](https://github.com/Lukas-VI/luminitor) | 主机监控 | Rust, MQTT, HTTP/WS, Node-RED | 轻量主机监视器，采用 Agent + Broker + Consumer 架构，面向 Windows、Ubuntu、虚拟机、边缘设备与工控场景。 |
| [yolo-tools](https://github.com/Lukas-VI/yolo-tools) | 计算机视觉工具 | Python, OpenCV, YOLOv8 | 面向 YOLOv8 训练与推理的工具集，包含大图切分/合并思路，用于提升远距离小目标识别能力。 |
| [yolo-basic-preprocesses-predictor](https://github.com/Lukas-VI/yolo-basic-preprocesses-predictor) | 计算机视觉实验 | Python, YOLOv8 | 两阶段 YOLO 推理流程：先检测大图目标框，再裁剪小图做预处理与分类，最后合并预测结果。 |
| [SteamBigScreenDriverPatch](https://github.com/Lukas-VI/SteamBigScreenDriverPatch) | 桌面效率工具 | Python, Windows hotkey | 将 ThinkBook 2022 的 Fn+F9 从售后服务快捷键改为 Steam 大屏幕启动/切换键。 |
| [small-four-legged](https://github.com/Lukas-VI/small-four-legged) | 机器人/硬件 | C++ | 小型四足项目代码，偏硬件控制与机器人实验方向。 |

## 项目方向

### 业务系统与工程交付

- [party-building-system](https://github.com/Lukas-VI/party-building-system)：从需求流程、权限角色、前后端分离到部署文档的完整业务系统实践。
- [luminitor](https://github.com/Lukas-VI/luminitor)：从 Agent 采集、MQTT 上报、Node-RED 聚合到 Hub 展示的监控链路，包含安装包与客户交付思路。
- [2025-database-project](https://github.com/Lukas-VI/2025-database-project)：数据库课程/小组项目，侧重数据建模、后端逻辑和应用落地。

### 计算机视觉与智能感知

- [yolo-tools](https://github.com/Lukas-VI/yolo-tools)：YOLOv8 训练与推理辅助工具，关注大图、小目标与远距离识别场景。
- [yolo-basic-preprocesses-predictor](https://github.com/Lukas-VI/yolo-basic-preprocesses-predictor)：检测 + 分类的组合式推理流程实验。
- [Mediapipe-Tracking-Universal](https://github.com/Lukas-VI/Mediapipe-Tracking-Universal)：基于 MediaPipe 的全身追踪项目 fork，用于理解人体姿态估计和 VR tracking 链路。

### 机器人、硬件与桌面工具

- [small-four-legged](https://github.com/Lukas-VI/small-four-legged)：小型四足项目代码。
- [servo-dog](https://github.com/Lukas-VI/servo-dog)：舵机/四足方向的实验仓库。
- [ska-next](https://github.com/Lukas-VI/ska-next)：机器人服务项目。
- [SteamBigScreenDriverPatch](https://github.com/Lukas-VI/SteamBigScreenDriverPatch)：把闲置快捷键改造成游戏/桌面工作流入口。

### 工具链、开源维护与学习

- [claw-code](https://github.com/Lukas-VI/claw-code)：Rust CLI agent harness 方向的 fork/维护学习。
- [htu-toolbox](https://github.com/Lukas-VI/htu-toolbox)：河师大工具箱 fork，包含校园网登录等实用功能。
- [NzHelper](https://github.com/Lukas-VI/NzHelper)：Android/Kotlin 项目 fork，关注更友好的 UI 与实用特性。
- [aseprite-builder](https://github.com/Lukas-VI/aseprite-builder)：通过 GitHub Actions 构建 Aseprite 的自动化工作流。
- [aseprite-build](https://github.com/Lukas-VI/aseprite-build)：Aseprite 上游 fork，用于像素动画工具构建与源码学习。
- [Python-study-notes](https://github.com/Lukas-VI/Python-study-notes)：Python 学习笔记。
- [The-exercise-of-Programming-in-C](https://github.com/Lukas-VI/The-exercise-of-Programming-in-C)：C 语言编程练习与题解整理。
- [test-mod-template-1.20](https://github.com/Lukas-VI/test-mod-template-1.20)：Minecraft mod template 相关实验。
- [MOT_SysMonitor](https://github.com/Lukas-VI/MOT_SysMonitor)：系统监控方向的早期项目。
- [suminosim](https://github.com/Lukas-VI/suminosim)：Python 仿真/实验仓库。

## 技术标签

`JavaScript` `Vue` `Node.js` `MySQL` `Rust` `MQTT` `Node-RED` `Python` `OpenCV` `YOLOv8` `C++` `Kotlin` `Makefile` `Windows` `Linux` `机器人` `主机监控` `计算机视觉`

## 推荐主页 Pin 叙事

如果只 pin 一个仓库，推荐 pin 当前 `Projects`，作为项目总览入口。

如果主页还要搭配其他仓库，推荐顺序：

1. `Projects`：总览入口。
2. `party-building-system`：完整业务系统能力。
3. `luminitor`：监控/边缘设备/交付能力。
4. `yolo-tools`：计算机视觉工具能力。
5. `yolo-basic-preprocesses-predictor`：算法实验和推理流程设计。
6. `SteamBigScreenDriverPatch` 或 `small-four-legged`：展示实用工具或机器人硬件方向。

## 账号入口

- GitHub: [Lukas-VI](https://github.com/Lukas-VI?tab=repositories)
- Gitee: [Yanhe06](https://gitee.com/Yanhe06)
