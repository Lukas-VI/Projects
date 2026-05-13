# Projects Portfolio

面向主页 pin 展示的项目简历。这里按 CV 的方式整理我在 GitHub 与 Gitee 迁移到 GitHub 后的公开项目，突出技术方向、项目职责、工程交付和可展示成果。

> Last updated: 2026-05-13

## Profile

- **方向定位**：应用系统开发、主机监控与边缘设备、计算机视觉工具、机器人/硬件实验。
- **工程特点**：偏向把想法做成可运行、可部署、可交付的项目；重视 README、部署脚本、打包流程和验证链路。
- **主要语言/技术**：JavaScript, Vue, Node.js, MySQL, Rust, Python, OpenCV, YOLOv8, C++, Kotlin, MQTT, Node-RED, Windows/Linux。
- **项目主页**：本仓库作为作品集入口，推荐与 `party-building-system`、`luminitor`、`yolo-tools` 一起 pin。

## Featured Repositories

<table>
  <tr>
    <td>
      <a href="https://github.com/Lukas-VI/party-building-system">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=party-building-system&theme=transparent&hide_border=true" alt="party-building-system repository card" />
      </a>
    </td>
    <td>
      <a href="https://github.com/Lukas-VI/luminitor">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=luminitor&theme=transparent&hide_border=true" alt="luminitor repository card" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lukas-VI/yolo-tools">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=yolo-tools&theme=transparent&hide_border=true" alt="yolo-tools repository card" />
      </a>
    </td>
    <td>
      <a href="https://github.com/Lukas-VI/yolo-basic-preprocesses-predictor">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=yolo-basic-preprocesses-predictor&theme=transparent&hide_border=true" alt="yolo-basic-preprocesses-predictor repository card" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lukas-VI/SteamBigScreenDriverPatch">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=SteamBigScreenDriverPatch&theme=transparent&hide_border=true" alt="SteamBigScreenDriverPatch repository card" />
      </a>
    </td>
    <td>
      <a href="https://github.com/Lukas-VI/small-four-legged">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Lukas-VI&repo=small-four-legged&theme=transparent&hide_border=true" alt="small-four-legged repository card" />
      </a>
    </td>
  </tr>
</table>

## Core Skills

### Full-stack Application

- 前后端分离业务系统设计
- 用户、角色、权限与流程审核建模
- MySQL 数据建模与接口开发
- H5/PC 管理端页面与后台联调

### Systems and Delivery

- Rust workspace 项目组织
- Windows/Ubuntu 安装包与交付目录整理
- MQTT、HTTP、WebSocket 数据链路
- Node-RED 聚合、告警与 dashboard 展示

### Computer Vision

- YOLOv8 训练/推理工具链
- 大图切分、小目标识别与二阶段推理
- OpenCV 图像预处理
- MediaPipe 姿态估计与人体追踪方向探索

### Robotics and Tools

- 小型四足/舵机控制方向实验
- Windows 快捷键与桌面效率工具
- GitHub Actions 自动构建
- 开源项目 fork、阅读、改造和维护

## Project Experience

### 1. 党员发展管理系统

- **Repository**: [party-building-system](https://github.com/Lukas-VI/party-building-system)
- **Role**: Full-stack developer / product implementer
- **Stack**: JavaScript, Node.js, MySQL, Vue, Vant, JWT
- **Scenario**: 面向高校党员发展流程的信息化管理系统。
- **Work Highlights**:
  - 设计服务号 H5、PC 后台和 Node.js 服务端的前后端分离结构。
  - 覆盖申请人、党支部书记、组织员、二级党委、组织部、超级管理员等多角色权限。
  - 实现流程审核、材料上传、统计分析、台账导出、消息提醒等核心模块。
  - README 和 docs 中沉淀部署、调试、流程说明和维护记录。
- **Value**: 展示完整业务系统从需求拆解、数据建模、接口实现到部署交付的能力。

### 2. Luminitor 主机监视器

- **Repository**: [luminitor](https://github.com/Lukas-VI/luminitor)
- **Role**: System developer / release workflow maintainer
- **Stack**: Rust, MQTT, Axum, WebSocket, Node-RED, PowerShell, Linux shell
- **Scenario**: 面向 Windows、Ubuntu、虚拟机、边缘设备和工控场景的轻量主机监控。
- **Work Highlights**:
  - 采用 `Agent + Broker + Consumer` 架构，设备侧 Agent 主动采集并推送状态。
  - 提供 HTTP/WS 本地接口，支持健康检查、快照和实时查看。
  - 通过 MQTT、Node-RED 与 Hub 形成聚合、告警和展示链路。
  - 整理 Windows/Ubuntu 试点安装包、校验脚本、客户交付目录和 release 产物。
- **Value**: 展示系统级 Rust 项目、监控链路、跨平台打包与交付工程能力。

### 3. YOLO 工具集

- **Repository**: [yolo-tools](https://github.com/Lukas-VI/yolo-tools)
- **Role**: CV tooling developer
- **Stack**: Python, OpenCV, YOLOv8
- **Scenario**: 为 YOLOv8 训练与推理提供辅助工具。
- **Work Highlights**:
  - 设计大图切分与合并流程，缓解高分辨率图像直接推理时的小目标识别问题。
  - 面向远距离目标识别场景，提供更实用的训练/推理辅助脚本。
  - 以工具集方式沉淀可复用的 CV 工作流。
- **Value**: 展示计算机视觉工程化思路，而不是只停留在模型调用。

### 4. YOLO 二阶段预处理推理实验

- **Repository**: [yolo-basic-preprocesses-predictor](https://github.com/Lukas-VI/yolo-basic-preprocesses-predictor)
- **Role**: CV experiment developer
- **Stack**: Python, YOLOv8, image preprocessing
- **Scenario**: 探索“检测 + 裁剪 + 预处理 + 分类 + 合并”的组合式推理流程。
- **Work Highlights**:
  - 使用大模型先定位目标框，再裁剪局部图像。
  - 对局部图像进行预处理后交给分类模型识别。
  - 合并 bbox 与 class 信息，输出最终预测结果。
- **Value**: 展示对推理流程拆解、模型协作和数据后处理的理解。

### 5. ThinkBook Fn+F9 DriverPatch

- **Repository**: [SteamBigScreenDriverPatch](https://github.com/Lukas-VI/SteamBigScreenDriverPatch)
- **Role**: Desktop utility developer
- **Stack**: Python, Windows hotkey workflow
- **Scenario**: 将 ThinkBook 2022 的 Fn+F9 从闲置售后服务入口改造为 Steam 大屏幕快捷键。
- **Work Highlights**:
  - 为特定设备快捷键重新赋予实用动作。
  - 支持 Steam Big Picture 启动/切换，提高桌面和游戏工作流体验。
  - 已迁移到 GitHub 并保留 `v1.0.0` tag。
- **Value**: 展示把个人痛点快速变成可用工具的执行力。

### 6. 机器人与硬件方向实验

- **Repositories**:
  - [small-four-legged](https://github.com/Lukas-VI/small-four-legged)
  - [servo-dog](https://github.com/Lukas-VI/servo-dog)
  - [ska-next](https://github.com/Lukas-VI/ska-next)
- **Stack**: C++, Python, Makefile
- **Scenario**: 小型四足、舵机控制与机器人服务方向实验。
- **Work Highlights**:
  - `small-four-legged` 保留 `develop` 与 `master` 分支，适合继续演进硬件控制代码。
  - `ska-next` 迁移时已完成历史脱敏，保留 `main` 与 `master` 分支。
  - `servo-dog` 作为舵机/四足方向早期探索仓库。
- **Value**: 展示软件与硬件结合方向的持续探索。

## Additional Projects

### Tooling and Open-source Reading

- [claw-code](https://github.com/Lukas-VI/claw-code)：Rust CLI agent harness 方向的 fork/维护学习。
- [htu-toolbox](https://github.com/Lukas-VI/htu-toolbox)：河师大工具箱 fork，包含校园网登录等实用功能。
- [NzHelper](https://github.com/Lukas-VI/NzHelper)：Android/Kotlin 项目 fork，关注更友好的 UI 与实用特性。
- [aseprite-builder](https://github.com/Lukas-VI/aseprite-builder)：通过 GitHub Actions 构建 Aseprite 的自动化工作流。
- [aseprite-build](https://github.com/Lukas-VI/aseprite-build)：Aseprite 上游 fork，用于像素动画工具构建与源码学习。

### Learning and Coursework

- [2025-database-project](https://github.com/Lukas-VI/2025-database-project)：数据库课程/小组项目。
- [Python-study-notes](https://github.com/Lukas-VI/Python-study-notes)：Python 学习笔记。
- [The-exercise-of-Programming-in-C](https://github.com/Lukas-VI/The-exercise-of-Programming-in-C)：C 语言编程练习与题解整理。
- [test-mod-template-1.20](https://github.com/Lukas-VI/test-mod-template-1.20)：Minecraft mod template 相关实验。
- [MOT_SysMonitor](https://github.com/Lukas-VI/MOT_SysMonitor)：系统监控方向早期项目。
- [suminosim](https://github.com/Lukas-VI/suminosim)：Python 仿真/实验仓库。

## Migration Notes

以下 Gitee 项目已迁移到 GitHub，并保留 Git 历史、分支和标签：

| Repository | Branches | Tags |
| --- | --- | --- |
| [SteamBigScreenDriverPatch](https://github.com/Lukas-VI/SteamBigScreenDriverPatch) | `master` | `v1.0.0` |
| [luminitor](https://github.com/Lukas-VI/luminitor) | `master` | - |
| [2025-database-project](https://github.com/Lukas-VI/2025-database-project) | `master` | - |
| [ska-next](https://github.com/Lukas-VI/ska-next) | `main`, `master` | - |
| [suminosim](https://github.com/Lukas-VI/suminosim) | `master` | - |
| [small-four-legged](https://github.com/Lukas-VI/small-four-legged) | `develop`, `master` | - |

### Commit History

- `SteamBigScreenDriverPatch`、`luminitor`、`2025-database-project`、`suminosim`、`small-four-legged` 使用 mirror 方式迁移，commit 历史随分支和标签一起迁移到 GitHub。
- `ska-next` 在迁移时触发 GitHub Push Protection，历史提交中包含 xAI API Key；迁移版已做历史脱敏，因此保留了提交脉络，但相关提交 SHA 会与 Gitee 原历史不同。
- GitHub 个人贡献图是否计入这些 commit，还取决于 commit email 是否绑定到 `Lukas-VI` 账号，以及 commit 是否位于默认分支或符合 GitHub 贡献统计规则。

## Recommended Pins

1. [Projects](https://github.com/Lukas-VI/Projects)：作品集入口。
2. [party-building-system](https://github.com/Lukas-VI/party-building-system)：完整业务系统。
3. [luminitor](https://github.com/Lukas-VI/luminitor)：Rust 监控与交付工程。
4. [yolo-tools](https://github.com/Lukas-VI/yolo-tools)：计算机视觉工具链。
5. [yolo-basic-preprocesses-predictor](https://github.com/Lukas-VI/yolo-basic-preprocesses-predictor)：CV 推理流程实验。
6. [SteamBigScreenDriverPatch](https://github.com/Lukas-VI/SteamBigScreenDriverPatch) 或 [small-four-legged](https://github.com/Lukas-VI/small-four-legged)：实用工具/机器人方向。
