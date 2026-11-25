# 张恒玮 · Hengwei Zhang

北京理工大学电子信息工程本科（2023–2027）

**嵌入式软件开发 · ARM Linux / 裸机 · 端侧感知**

我喜欢把传感器、算法和设备接起来，在实机上验证结果。做过 C 语言声纹识别、Cortex-A8 裸机显示驱动适配，以及飞腾和树莓派上的视觉模型部署。

[个人博客](https://vivofiftykfc.github.io/) · [作品集](https://github.com/vivofiftykfc/embodied-intelligence-portfolio) · [邮件联系](mailto:zhangdeyou_2023@qq.com)

## 代表项目

### [Sound-Walker · ARM Linux 离线声纹识别](https://github.com/vivofiftykfc/sound-walker)

在同一设备上实现纯 C 的 MFCC + DTW 和基于 sherpa-onnx 的 CAM++ 两版原型，打通录音、注册与本地匹配。项目对比测试中，两版的识别延迟分别约为 **200 ms** 和 **500 ms**。

[对比测试](https://github.com/vivofiftykfc/sound-walker#路线对比) · [演示视频](https://www.bilibili.com/video/BV1HJ7P6oE8r/)

### [火灾救援无人机 · 飞腾平台多模态感知](https://github.com/vivofiftykfc/cicc_9)

担任视觉与感知模块负责人，用 ncnn 将 NanoDet 部署到飞腾嵌入式 Linux 平台，处理红外热阵列数据，并参与视觉、红外与通信模块联调。获**全国大学生集成电路创新创业大赛飞腾赛道华北赛区二等奖**。

### Cortex-A8 裸机图形界面移植

在 S5PV210 上移植 LVGL，适配显示驱动，使用帧缓冲缓存、双缓冲和垂直同步优化图形刷新。

### 电梯智能监控 · 树莓派视觉部署

担任校级大创项目负责人，负责 NanoDet 选型与树莓派 5B 部署，协调检测和语音报警模块联调。完成电动车入梯检测样机，结题演示中的处理速度约 **10 FPS**。

### 独居老人智能家居健康监测

开发毫米波雷达串口采集和基于人体关键点的跌倒检测流程，参与雷达与视觉的数据对齐和融合判据设计。另用示例监测数据验证了建议生成与语音播报流程。[RAG 决策原型](https://github.com/vivofiftykfc/qwen_rag)

## 专利与竞赛

- **发明专利申请**：[基于 ESP32 的独居老人智能家居健康云监测系统（CN121547473A）](https://patents.google.com/patent/CN121547473A/zh)。我是共同发明人，申请人为北京理工大学，申请已于 2026 年 2 月公开。
- **集创赛**：第九届全国大学生集成电路创新创业大赛飞腾赛道华北赛区二等奖。
- **数学建模**：2026 年美国大学生数学建模竞赛（MCM）Honorable Mention（H 奖）。

<details>
<summary>更多项目</summary>

- [StellarVanguard-FPGA](https://github.com/vivofiftykfc/StellarVanguard-FPGA)：用 Verilog 在 Basys3 上实现可交互的游戏，输出 640×480、60 Hz 的 VGA 画面。
- [fpga-busicdc-2025](https://github.com/vivofiftykfc/fpga-busicdc-2025)：AXI-Stream 网络协议解析与 8 位单总线处理器。
- [JudgeBooth](https://github.com/vivofiftykfc/judgebooth)：负责 FastAPI 后端、SSE 实时反馈和多模态评审流程集成。
- [WLAN-0714 ARG](https://github.com/vivofiftykfc/wlan-0714-arg)、[ARG Toolbox](https://github.com/vivofiftykfc/arg-toolbox)、[Contemplation Site](https://github.com/vivofiftykfc/contemplation-site)：交互叙事、故事建模与阅读体验实验。

</details>

<img src="./assets/signal-footer.webp" width="100%" alt="" />
