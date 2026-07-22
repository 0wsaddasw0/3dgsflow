<p align="center">
  <a href="https://3dgsflow.com">
    <img src="https://3dgsflow.com/image/mascot-mark.png" alt="3DGSFlow Logo 高斯溅射工作流" width="96" />
  </a>
</p>

<h1 align="center">3DGSFlow · 3DGS 工作流</h1>

<p align="center">
  <b>从拍摄、训练到编辑与多场景交付的 3D Gaussian Splatting（高斯溅射 / 3DGS）流水线</b>
</p>

<p align="center">
  <a href="https://3dgsflow.com"><img src="https://img.shields.io/badge/官网-3dgsflow.com-0ea5e9?style=for-the-badge" alt="3DGSFlow Website" /></a>
  <a href="https://3dgsflow.com/editor"><img src="https://img.shields.io/badge/编辑工作台-现已开放-22c55e?style=for-the-badge" alt="3DGS Editor" /></a>
  <a href="https://3dgsflow.com/guide"><img src="https://img.shields.io/badge/高斯溅射指南-SEO%20Guide-111827?style=for-the-badge" alt="3DGS Guide" /></a>
</p>

<p align="center">
  <a href="https://3dgsflow.com">
    <img src="https://3dgsflow.com/image/mascot-hero.png" alt="3DGSFlow 吉祥物：水獭手持相机与三维展示窗，代表高斯溅射采集与交付" width="520" />
  </a>
</p>

---

**3DGSFlow** 把 **高斯溅射（3D Gaussian Splatting / 3DGS）** 串成一条闭环流水线：采集 → 重建 → 精修 → 交付。  
今天可在浏览器完成**编辑**与**物品展览网页导出**（所见即所得）；拍摄设备与本地训练工具将陆续接入同一工作流。支持 **PLY / SPLAT / SPZ**，无需注册，数据不出本机。

> 官网：**[https://3dgsflow.com](https://3dgsflow.com)** · 编辑器：**[https://3dgsflow.com/editor](https://3dgsflow.com/editor)**  
> 本仓库用于产品介绍与搜索引擎收录，**不开放源代码**。

---

## 一条流水线，四个站点

采集、重建、精修与交付串成闭环。高亮站点今天就能用，其余按进度推进。

| 站点 | 状态 | 说明 | 入口 |
|------|------|------|------|
| **01 拍摄** | 规划中 | 采集现场与物体影像，未来支持设备租赁 | 暂未开放 |
| **02 训练** | 内测中 | 本地训练工具将影像重建为 3DGS 模型，全程本机完成，无需上传 | 暂未开放 |
| **03 编辑** | **现已开放** | 浏览器清洗、校准、标注，数据不出本机 | [打开工作台](https://3dgsflow.com/editor) |
| **04 交付** | **部分可用** | 物品展览网页包已可用；VR 与 GIS 场景持续接入 | 见下方三种交付 |

---

## 三种交付方向

导出不止一种终点。展览今天就能出包；漫游与 GIS 正在接入同一体系。

| 方向 | 状态 | 说明 | 入口 |
|------|------|------|------|
| **物品展览** | **现已支持** | 展台配置页所见即所得，导出静态网页包，适合展品、商品与官网嵌入 | [去编辑并导出](https://3dgsflow.com/editor) |
| **VR 漫游** | 规划中 | 空间漫游与沉浸浏览，面向场馆与空间叙事 | 路线规划中 |
| **GIS 融合** | 规划中 | 与地图、规划场景叠加，服务空间与城市场景 | 路线规划中 |

---

## 编辑工作台（现已开放）

在本地浏览器完成 **3DGS / 高斯溅射** 模型精修与交付准备：

- 导入 **PLY、SPLAT、SPZ**；多模型图层融合
- 空间去噪、框选 / 体积裁剪、模型瘦身
- **一键校准**（朝向、中心、贴地）
- 测量、热点标注、场景背景色与 HDR 环境
- 项目包续做、原始模型导出
- 一键导出可部署的静态网页包（通用网页包 / 物品展览）

所有解析与处理在浏览器本地完成，不上传用户模型文件。建议使用**电脑端** Chrome / Edge 打开工作台。

---

## 物品展览导出（现已支持）

从编辑器进入**物品展览**配置页，左侧预览与最终导出网页对齐：

- 展台自转、旋转中心、拉近 / 推远距离、锁定平移
- 文案、强调色、暗角与导出页 UI 主题
- 背景：**纯色 / HDR / 图片**（可从编辑器带入已选背景色与 HDR）
- 渲染引擎与球谐阶数可选；导出 ZIP 可独立托管

配置页拖拽视角即写入导出包，尽量做到**所见即所得**。

---

## 了解高斯溅射（指南）

| 页面 | 说明 | 链接 |
|------|------|------|
| 指南中心 | 目录与入门导览 | [https://3dgsflow.com/guide](https://3dgsflow.com/guide) |
| 什么是高斯溅射（3DGS） | 概念与点云 / 网格对比 | […/guide/gaussian-splatting](https://3dgsflow.com/guide/gaussian-splatting) |
| 在线 3DGS 编辑器能做什么 | 多模型融合、一键校准、项目续做 | […/guide/editor](https://3dgsflow.com/guide/editor) |
| PLY / SPLAT / SPZ 格式说明 | 格式差异与导入导出建议 | […/guide/formats](https://3dgsflow.com/guide/formats) |
| 如何导出可部署的 3DGS 网页 | 交付选型、展览页、引擎与球谐 | […/guide/export](https://3dgsflow.com/guide/export) |

---

## 关键词

`高斯溅射` · `高斯泼溅` · `3DGS` · `3D Gaussian Splatting` · `3DGS 工作流` · `Gaussian Splatting editor` · `3DGS 编辑器` · `3DGS 训练` · `PLY` · `SPLAT` · `SPZ` · `点云清洗` · `一键校准` · `3DGS 导出网页` · `物品展览` · `HDR 背景` · `3DGSFlow`

---

## 版本与路线

| 节点 | 说明 |
|------|------|
| **v0.2.0**（2026-07-23） | 多模型融合编辑、一键校准、体积裁剪优化；导出选型与物品展览页（所见即所得：视角 / 自转对齐预览；背景纯色 / HDR / 图片可从编辑器带入）；引擎三选一与球谐阶数；项目保存导出续做、原始模型导出；暗黑 / 浅色主题与指南页 |
| **v0.1.0**（2026-07-01） | 编辑工作台首发：清洗、校准、通用网页包导出 |
| **后续** | VR 漫游、GIS 融合、拍摄采集、本地训练并入同一流水线 |

---

## 版权声明

Copyright © 3DGSFlow. All rights reserved.

本仓库用于产品介绍与 SEO 收录，**源代码不对外开源**。吉祥物与品牌标识归 3DGSFlow 所有。

官网：[https://3dgsflow.com](https://3dgsflow.com)
