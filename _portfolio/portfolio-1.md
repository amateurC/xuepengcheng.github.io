---
layout: single
title: "作品集"
permalink: /portfolio/
author_profile: true
---

以下是我在三维视觉与人工智能方向的代表性成果，涵盖工程项目与科研论文两大模块：

---

## 🛠️ 工程项目（Engineering Projects）

### 1. 工业级三维重建系统优化  
*公司：先临三维科技 | 角色：算法实习生*

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="//player.bilibili.com/player.html?bvid=BV1a9doYbEB7&page=1"
          frameborder="0" allowfullscreen
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  </iframe>
</div>

该项目对深度图生成与位姿对齐模块进行结构优化，提升工业场景下稠密点云重建质量，PSNR 与 SSIM 指标提升 20%+。

- ✅ 引入多视图一致性策略，解决 3D Gaussian Splatting 重建中常见的漂浮物问题  
- 🧠 技术栈：PyTorch, Open3D, Colmap, TensorRT  
- 📅 时间：2024年4月  

---

### 2. **轻量级图像去模糊系统**
*公司：先临三维科技 | 角色：算法实习生*

改进 NAFNet 架构，将 Self-Attention 替换为 Depthwise Convolution，实现去模糊网络的小型化与部署优化。

- ⚙️ 显存占用 <6GB，推理延迟 <1s，成功部署于扫描仪实时处理流水线  
- 🧠 技术栈：PyTorch, ONNX, TensorRT  
- 📅 时间：2024年5月  
- 🔗 [部署演示链接（预留）](#)

---

## 📄 学术成果（Research Papers）

### 3. **SVGS: Single-View to 3D Object Editing via Gaussian Splatting**
*投稿期刊：SCIS（CCF-A）*

提出一种结合单视图深度估计与 3D Gaussian Splatting 的编辑方法，支持从单张图片生成可操作三维对象，显著提升编辑效率与质量。

- 🌐 *研究亮点*：首次将单视图深度引导与3DGS结合用于交互编辑任务  
- 📅 时间：2024年4月  
- 🔗 [论文链接（预留）](#)

---

### 4. **A Diffusion Model for Compositional 3D Tooth Generation**
*投稿会议：ACMMM（CCF-A）*

提出用于齿科结构建模的生成扩散框架，引入碰撞检测与形状先验，实现在物理约束下的三维牙齿组合建模。

- 🦷 *创新点*：融合点云表示、碰撞优化与多齿结构建模  
- 📅 时间：2024年4月  
- 🔗 [论文链接（预留）](#)

---

📄 如需查看完整简历，可点击：[下载简历 PDF](/files/算法实习生.pdf)  
✉️ 如需联系我，请发送邮件至：[1152231696@qq.com](mailto:1152231696@qq.com)
