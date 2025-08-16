# 第二章：光刻工艺 | Chapter 2: Photolithography Process

---

## 2.1 光刻的基本流程 | Basic Process Flow

典型的光刻工艺包括以下步骤：
A typical photolithography process includes the following steps:

1. **清洗基底**（Substrate Cleaning）
   去除颗粒、油污、金属残留等污染。
   Remove particles, organics, and metal residues.

2. **脱水烘烤**（Dehydration Bake）
   通常在 120–200 °C 下对晶圆烘烤，去除水分。
   Bake wafer at 120–200 °C to remove moisture.

3. **涂胶**（Spin Coating of Photoresist）
   通过旋涂均匀涂覆光刻胶（PR）。
   Apply photoresist uniformly via spin coating.

4. **软烘烤**（Soft Bake）
   去除光刻胶中的溶剂，改善后续曝光和图形转移效果。
   Remove solvents from the resist to improve patterning.

5. **掩模对准与曝光**（Mask Alignment & Exposure）
   使用紫外光照射晶圆，通过掩模图案进行转印。
   Use UV light to expose the resist through a patterned mask.

6. **显影**（Development）
   用显影液选择性溶解曝光区域（正胶）或未曝光区域（负胶）。
   Use developer to dissolve exposed (positive) or unexposed (negative) regions.

7. **硬烘烤**（Hard Bake）
   固化图案，提高热稳定性。
   Final bake to harden the patterned resist.

8. **图案转移（刻蚀）或金属沉积**
   将图案用于后续刻蚀或金属工艺中。
   Use resist as a mask for etching or deposition.

---

## 2.2 光刻胶类型 | Types of Photoresist

* **正性光刻胶（Positive Photoresist）**：
  曝光区域的化学键被打断 → 显影后曝光区域被去除。
  The exposed areas become soluble and are removed during development.

* **负性光刻胶（Negative Photoresist）**：
  曝光区域发生交联 → 显影后曝光区域保留。
  The exposed areas become cross-linked and remain after development.

### 比较 | Comparison

| 属性    | 正性光刻胶       | 负性光刻胶 |
| ----- | ----------- | ----- |
| 分辨率   | 高（\~0.5 µm） | 相对较低  |
| 耐腐蚀性  | 中等          | 通常较高  |
| 曝光能量  | 高           | 较低    |
| 图形保真度 | 好           | 易变形   |

---

## 2.3 曝光方式 | Exposure Methods

### 1. **接触式（Contact Printing）**

掩模与光刻胶直接接触，分辨率高但损耗大。
Mask contacts resist directly. High resolution, but causes mask wear.

### 2. **近接式（Proximity Printing）**

掩模与光刻胶间有微小间隙，减少掩模损伤但牺牲部分分辨率。
Small gap between mask and resist. Less damage, lower resolution.

### 3. **投影式（Projection Printing）**

光学系统将掩模图案缩小后投射，适用于先进工艺。
Optics project reduced image of mask onto wafer. Used in advanced lithography.

---

## 2.4 分辨率与对比度 | Resolution and Contrast

### 解析度（Resolution）由以下公式近似决定：

$$ R = \frac{k_1 \cdot \lambda}{NA} $$

* $R$：最小特征尺寸（Resolution）
* $\lambda$：曝光波长
* $NA$：数值孔径（Numerical Aperture）
* $k_1$：工艺因子，理论极限为 0.25

### 对比度（Contrast）：

描述曝光后显影区域和未显影区域的明暗差异。
Contrast describes image sharpness between exposed and unexposed areas.

---

## 2.5 曝光光源与系统 | Exposure Source and Optical System

* 常用波长：g-line (436 nm), i-line (365 nm), DUV (248 nm), ArF (193 nm)
* 数值孔径 NA 提高 → 分辨率提升，但景深降低。
* 相位移掩模（Phase-shift mask, PSM）、偏振控制、光源形状工程（off-axis illumination）用于增强分辨率。

---

## 2.6 光刻的极限与新技术 | Limitations and Advanced Techniques

* **深紫外（DUV）光刻**：248 nm KrF 和 193 nm ArF 激光，主流节点
* **浸没光刻（Immersion Lithography）**：在晶圆与透镜间加入液体以提高 NA
* **极紫外（EUV）光刻**：使用 13.5 nm EUV 光源，可实现 <10 nm 特征尺寸
* **多重图案化（Multiple Patterning）**：如LELE、SADP，用于突破分辨率限制

---

## 2.7 小结 | Summary

光刻是微纳制造的核心工艺之一，其关键能力决定了芯片最小线宽和集成密度。

Photolithography is a key step in micro/nanofabrication. It defines critical dimensions and pattern fidelity.

随着工艺尺寸不断缩小，传统光刻面临分辨率和成本瓶颈，激发出诸如浸没、EUV、图案倍增等创新技术的发展。

As feature sizes shrink, lithography faces physical and economic limits, driving innovations like immersion, EUV, and multiple patterning.

---


