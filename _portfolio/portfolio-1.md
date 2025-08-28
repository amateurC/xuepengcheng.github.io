---
layout: single
title: "作品集"
permalink: /portfolio/
author_profile: true
---

以下是我在三维视觉与人工智能方向的代表性成果，涵盖工程项目、3DGS作品集与科研论文三大模块：

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
*公司：先临三维科技 ｜ 角色：算法实习生*

改进 NAFNet 架构，将 Self-Attention 替换为 Depthwise Convolution，实现去模糊网络的小型化与部署优化。

- ⚙️ 显存占用 <6GB，推理延迟 <1s，成功部署于扫描仪实时处理流水线  
- 🧠 技术栈：PyTorch, ONNX, TensorRT  
- 📅 时间：2024年5月  

💡 以下为真实场景中的去模糊效果展示（左右拖动查看）：

<div style="display: grid; grid-template-columns: 1fr; gap: 24px; max-width: 1224px; margin: 0 auto;">

  <div style="border-radius: 12px; overflow: hidden; box-shadow: 0 4px 16px rgba(0,0,0,0.12);">
    <iframe 
      src="https://imgsli.com/MzM2MDQ2?embed=true" 
      width="100%" 
      height="600" 
      style="border: none;" 
      allowfullscreen>
    </iframe>
  </div>

  <div style="border-radius: 12px; overflow: hidden; box-shadow: 0 4px 16px rgba(0,0,0,0.12);">
    <iframe 
      src="https://imgsli.com/MzM2MDQ1?embed=true" 
      width="100%" 
      height="600" 
      style="border: none;" 
      allowfullscreen>
    </iframe>
  </div>

  <div style="border-radius: 12px; overflow: hidden; box-shadow: 0 4px 16px rgba(0,0,0,0.12);">
    <iframe 
      src="https://imgsli.com/MzM2MDQz?embed=true" 
      width="100%" 
      height="600" 
      style="border: none;" 
      allowfullscreen>
    </iframe>
  </div>

</div>

---

## 🌌 3DGS 作品集（3D Gaussian Splatting Portfolio）

### 📍 全景相机场景重建
基于 **全景相机数据** 实现大规模室内外场景的 3DGS 重建，提升重建精度与完整性（性能提升 20%+）。  

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="//player.bilibili.com/player.html?bvid=BV1wZh1zFEoX&page=1"
          frameborder="0" allowfullscreen
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  </iframe>
</div>

---

### 🏞️ 室外大场景
使用自研管线实现 **≥1km² 城市级场景** 的 无人机3DGS 重建。  

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="//player.bilibili.com/player.html?bvid=BV1BHeXzmErv&page=1"
          frameborder="0" allowfullscreen
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  </iframe>
</div>

---

## 📄 学术成果（Research Papers）

### 3. **SVGS: Single-View to 3D Object Editing via Gaussian Splatting**
*投稿期刊：SCIS（CCF-A）*

提出一种结合单视图深度估计与 3D Gaussian Splatting 的编辑方法，支持从单张图片生成可操作三维对象，显著提升编辑效率与质量。

- 🌐 *研究亮点*：首次将单视图深度引导与3DGS结合用于交互编辑任务  
- 📅 时间：2024年4月  
- 🔗 [论文链接（预留）](#)
<div style="text-align: center; margin-top: 16px;">
  <img src="https://github.com/amateurC/xuepengcheng.github.io/raw/master/images/svgs_result.png" alt="SVGS示意图" style="max-width: 100%; border-radius: 12px; box-shadow: 0 4px 16px rgba(0,0,0,0.1);" />
  <p style="font-size: 14px; color: #555;">图示：由单张输入图像生成并编辑的3D对象</p>
</div>

---

### 4. **A Diffusion Model for Compositional 3D Tooth Generation**
*投稿会议：ACMMM（CCF-A）*

提出用于齿科结构建模的生成扩散框架，引入碰撞检测与形状先验，实现在物理约束下的三维牙齿组合建模。

- 🦷 *创新点*：融合点云表示、碰撞优化与多齿结构建模  
- 📅 时间：2024年4月  
- 🔗 [论文链接（预留）](#)
<div style="text-align: center; margin-top: 16px;">
  <img src="https://github.com/amateurC/xuepengcheng.github.io/raw/master/images/tooth_result.png" alt="3D牙齿生成结果图" style="max-width: 100%; border-radius: 12px; box-shadow: 0 4px 16px rgba(0,0,0,0.1);" />
  <p style="font-size: 14px; color: #555;">图示：在物理约束下生成的多齿三维结构</p>
</div>

---

📄 如需查看完整简历，可点击：[下载简历 PDF](/files/算法实习生.pdf)  
✉️ 如需联系我，请发送邮件至：[1152231696@qq.com](mailto:1152231696@qq.com)
