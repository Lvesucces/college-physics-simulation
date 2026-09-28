# 大学物理轻量化虚拟仿真实验：光电效应与普朗克常数测定

> Einstein Photoelectric Effect & Planck Constant Measurement Virtual Lab (Single-file H5)

本实验是为大学物理课程设计的轻量化虚拟仿真实验系统。采用纯原生技术（HTML5 + CSS3 + Canvas 2D + ES6）开发，单文件自洽（~102KB），无需安装任何插件或 App，浏览器秒开（<0.2s），完美适配手机移动端与 PC 大屏。

---

## 🌟 核心特性

- 🔬 **严谨的微观与宏观物理仿真**：
  - 微观粒子动力学：Canvas 2D 60FPS 实时渲染光子波包散射、不同能量光电子逸出、电场受力偏转与减速/加速轨迹。
  - 真实光谱波长映射：预设汞灯特征谱线（365nm、405nm、436nm、546nm、577nm、650nm）与连续色谱联动。
  - 金属材料逸出功库：铯(Cs)、钾(K)、钠(Na)、锌(Zn)、铂(Pt)。
  - 真实伏安特性：包含微弱暗电流、接触电位差与饱和光电流模拟。
- 🤖 **深度 AI 融合与智能评估**：
  - **实时状态机纠错**：无光照调压、波长低于红限盲调光强、遏止电压过冲等违规操作即时弹出物理警示。
  - **最小二乘法线性回归拟合**：实时拟合 $\nu - U_a$ 直线，测定普朗克常数 $h$ 并计算相对误差。
  - **一键生成 AI 综合诊断报告**：多维度（满分100分）量化评价与物理误差归因剖析。
- 🏆 **满分加分项支持**：
  - **完全离线 AI 能力**：默认内置大学物理专家推理引擎（0网络依赖）；支持一键桥接本地电脑部署的 **Ollama** / **LM Studio** 离线大模型。
  - **真实传感器交互**：支持移动端调用陀螺仪与加速度计（DeviceOrientation），倾斜手机微调电压。
  - **多模态交互**：支持 Web Speech API 智能语音解说与语音提问。

---

## 🚀 访问与使用

- **在线访问链接 (GitHub Pages)**: [https://lvesucces.github.io/college-physics-simulation/](https://lvesucces.github.io/college-physics-simulation/)
- **GitHub 开源仓库**: [https://github.com/Lvesucces/college-physics-simulation](https://github.com/Lvesucces/college-physics-simulation)
- **本地直接运行**: 任意现代浏览器双击打开 `index.html` 即可运行。

---

## 📁 项目文件

- `index.html`：项目核心代码（单文件整合全部逻辑与界面）
- `方案文档与用户手册.md`：详细设计报告、用户手册与学术诚信声明
- `content.txt`：课程作业要求与评分规范
