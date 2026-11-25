<p align="center">
  <img src="./assets/perception-to-silicon.webp" width="100%" alt="从环境感知到嵌入式芯片的信号链路" />
</p>

<h1 align="center">张恒玮 · Hengwei Zhang</h1>

<p align="center">
  北京理工大学 · 电子信息工程<br />
  <strong>嵌入式软件开发 · ARM Linux / 裸机 · 端侧感知</strong>
</p>

<p align="center">
  <a href="#端侧感知">端侧感知</a> ·
  <a href="#底层与数字系统">底层与数字系统</a> ·
  <a href="#应用与交互">应用与交互</a> ·
  <a href="#专利与竞赛">专利与竞赛</a>
  <br />
  <a href="https://vivofiftykfc.github.io/">个人博客</a> ·
  <a href="https://github.com/vivofiftykfc/embodied-intelligence-portfolio">作品集</a> ·
  <a href="mailto:zhangdeyou_2023@qq.com">邮件联系</a>
</p>

> 我喜欢把传感器、算法和设备接起来，在实机上看结果。从采集声音、视觉与雷达信号，到在板端运行算法，再到把结果呈现给人，这是我做项目最感兴趣的部分。

## 端侧感知

<table width="100%">
<tr>
<td colspan="2">
<h3><a href="https://github.com/vivofiftykfc/cicc_9">火灾救援无人机</a></h3>
<p><strong>飞腾嵌入式 Linux · 视觉与感知模块负责人</strong></p>
<p>用 ncnn 部署 NanoDet，处理红外热阵列数据，参与视觉、红外和通信模块联调。获集创赛飞腾赛道华北赛区二等奖。</p>
<a href="./assets/thermal-demo.jpg"><img src="./assets/thermal-demo.jpg" width="100%" alt="飞腾平台调试现场，屏幕实时显示红外热像" /></a>
<br />
<sub>红外热阵列采集与热像显示 · <a href="./assets/phytium-prototype.jpg">硬件接线实拍</a> · <a href="https://github.com/vivofiftykfc/cicc_9">项目仓库</a></sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/sound-walker">Sound-Walker</a></h3>
<p><strong>ARM Linux · 离线声纹识别</strong></p>
<p>在同一设备上实现录音、注册与本地匹配，对比纯 C 的 MFCC + DTW 与 CAM++ 两种方案。项目测试中，两版识别延迟分别约为 <strong>200 ms</strong> 和 <strong>500 ms</strong>。</p>
<p><a href="https://github.com/vivofiftykfc/sound-walker#路线对比">对比测试</a> · <a href="https://www.bilibili.com/video/BV1HJ7P6oE8r/">演示视频</a></p>
</td>
<td width="50%" valign="top">
<h3>电梯智能监控</h3>
<p><strong>树莓派 5B · 校级大创项目负责人</strong></p>
<p>负责 NanoDet 选型和部署，协调检测与语音报警模块联调。完成电动车入梯检测样机，结题演示中的处理速度约为 <strong>10 FPS</strong>。</p>
</td>
</tr>
<tr>
<td colspan="2">
<h3>独居老人智能家居健康监测</h3>
<p><strong>毫米波雷达与视觉 · 市级创新项目核心开发成员</strong></p>
<p>开发雷达串口采集和人体关键点跌倒检测流程，参与两路数据对齐与融合判据设计。另用示例监测数据验证建议生成与语音播报流程。</p>
<p><a href="https://github.com/vivofiftykfc/qwen_rag">RAG 决策原型</a> · <a href="https://patents.google.com/patent/CN121547473A/zh">发明专利公开页</a></p>
</td>
</tr>
</table>

## 底层与数字系统

<table width="100%">
<tr>
<td colspan="2">
<h3>Cortex-A8 裸机图形界面</h3>
<p><strong>S5PV210 · LVGL 移植与显示驱动</strong></p>
<p>在无操作系统的环境下移植 LVGL，适配显示驱动，并使用帧缓冲缓存、双缓冲和垂直同步优化图形刷新。</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/StellarVanguard-FPGA">StellarVanguard</a></h3>
<p><strong>Basys3 · Verilog</strong></p>
<p>在 FPGA 上实现 VGA 时序、图层渲染、按键交互和游戏逻辑，输出 <strong>640×480、60 Hz</strong> 画面。</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/fpga-busicdc-2025">FPGA 数字系统设计</a></h3>
<p><strong>AXI-Stream · 数字逻辑</strong></p>
<p>实现网络协议解析电路与 8 位单总线处理器，覆盖数据流处理和处理器控制逻辑。</p>
</td>
</tr>
</table>

## 应用与交互

<table width="100%">
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/judgebooth">JudgeBooth</a></h3>
<p><strong>多模态路演评审</strong></p>
<p>负责 FastAPI 后端与 AI 流程，整合语音转写、面部分析和模型评审，通过 SSE 返回实时进度与反馈。</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/wlan-0714-arg">WLAN-0714 ARG</a></h3>
<p><strong>可游玩的中文互联网解谜</strong></p>
<p>围绕异常登录展开故事，用时间线、线索和解谜进度把叙事做成可交互的 Web 体验。</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/arg-toolbox">ARG Toolbox</a></h3>
<p><strong>互动叙事工具</strong></p>
<p>用结构化数据表示故事真相、角色知识和玩家知识，便于检查线索与叙事逻辑。</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/vivofiftykfc/contemplation-site">Contemplation Site</a></h3>
<p><strong>交互式阅读网站生成器</strong></p>
<p>把长文主题组织成可浏览的交互阅读页面，探索适合知识内容的呈现方式。</p>
</td>
</tr>
</table>

## 专利与竞赛

> **[基于 ESP32 的独居老人智能家居健康云监测系统（CN121547473A）](https://patents.google.com/patent/CN121547473A/zh)**
> 共同发明人 · 申请人为北京理工大学 · 发明专利申请于 2026 年 2 月公开

- 第九届全国大学生集成电路创新创业大赛 · 飞腾赛道华北赛区二等奖
- 2026 年美国大学生数学建模竞赛（MCM）· Honorable Mention（H 奖）

<p align="center">
  <img src="./assets/signal-footer.webp" width="100%" alt="" />
</p>
