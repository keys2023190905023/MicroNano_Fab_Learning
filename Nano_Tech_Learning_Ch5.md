# 第五章：刻蚀工艺（Etching）| Chapter 5: Etching Techniques

---

## 5.1 刻蚀简介 | Introduction to Etching

刻蚀是将图形从掩模转移到材料上的关键工艺。通过去除暴露区域的材料，形成所需结构。

Etching is a key step in pattern transfer, removing exposed material to define desired structures.

---

## 5.2 湿法刻蚀 | Wet Etching

使用液态化学溶液实现材料选择性去除。

Uses liquid chemicals to selectively dissolve exposed materials.

### 类型 | Types

* **各向同性刻蚀（Isotropic）**：所有方向速率相同，产生圆弧边缘。
* **各向异性刻蚀（Anisotropic）**：速率方向相关，产生垂直边缘。

### 示例 | Examples

* **HF**：蚀刻SiO₂，反应：SiO₂ + HF → H₂SiF₆
* **KOH**：蚀刻Si，选择性强，依赖晶向 (100 vs 111)

### 优缺点 | Pros & Cons

| 属性  | 优点 | 缺点              |
| --- | -- | --------------- |
| 成本  | 低  | 结构控制性差          |
| 设备  | 简单 | 易产生下切(undercut) |
| 选择性 | 高  | 分辨率有限           |

---

## 5.3 干法刻蚀 | Dry Etching

通过等离子体或离子束去除材料，常用于微纳结构。

Dry etching removes material via plasma or ion bombardment. Common for micro/nanofabrication.

### 类型 | Types

* **等离子体刻蚀（Plasma Etching）**：中性自由基主导，化学反应为主
* **反应离子刻蚀（RIE）**：化学 + 物理刻蚀耦合，方向性强
* **深反应离子刻蚀（DRIE）**：如Bosch工艺，适用于高深宽比结构

---

## 5.4 反应离子刻蚀原理 | Principles of RIE

RIE结合等离子体化学反应与离子加速撞击：

RIE combines chemical etching from plasma radicals with directional ion bombardment.

* 产生等离子体（常用气体：CHF₃、SF₆、Cl₂、O₂ 等）
* 电场将离子加速至基底表面 → 加速反应速率并引导方向性

### 优势 | Advantages

* 垂直方向控制强（高各向异性）
* 分辨率高
* 与光刻图形精确对齐

---

## 5.5 刻蚀关键参数 | Key Etching Parameters

| 参数                   | 描述             |
| -------------------- | -------------- |
| **选择性**（Selectivity） | 掩模/材料之间的刻蚀速率比  |
| **刻蚀速率**（Etch Rate）  | nm/min，影响加工效率  |
| **均匀性**（Uniformity）  | 晶圆表面刻蚀一致性      |
| **各向异性**（Anisotropy） | 方向选择性，决定侧壁垂直程度 |
| **残留物**（Residue）     | 副产物或聚合物残留，需清洗  |

---

## 5.6 等离子体刻蚀设备组成 | Etching System Components

* **真空腔体**（Chamber）：提供稳定反应环境
* **RF 电源**：用于激发等离子体（13.56 MHz 常见）
* **气体流量控制系统**：调节反应气体比例
* **冷却系统**：控制晶圆温度，防止热损伤
* **抽气系统**：维持低压环境，排出副产物

---

## 5.7 工艺效应与缺陷 | Etch Effects and Issues

* **微加载效应（Microloading Effect）**：图形密度变化导致刻蚀速率差异
* **ARDE（Aspect Ratio Dependent Etching）**：高深宽比结构刻蚀变慢
* **侧壁粗糙度（Sidewall Roughness）**：影响后续工艺质量
* **反沉积/残留层**：需后清洗（O₂ plasma、wet clean）

---

## 5.8 小结 | Summary

刻蚀作为图形转移的核心工艺之一，影响最终结构的形貌、尺寸与性能。

Etching critically impacts final structure profile, dimensions, and device performance.

干法刻蚀在分辨率、方向控制方面优于湿法，但设备复杂、控制参数多。

Dry etching offers better resolution and control, while being more complex and sensitive to parameters.

---
