# 第三章：电子束光刻（EBL）| Chapter 3: Electron Beam Lithography

## 3.1 原理概述 | Basic Principle

>电子束光刻是一种使用聚焦电子束在抗蚀剂上直接写图的技术，不依赖掩模。<br/>
>Electron Beam Lithography (EBL) is a maskless lithography method that uses a focused beam of electrons to write patterns directly on a resist-coated substrate.

特点 | Features
* 高分辨率（<10 nm）
* 灵活性强，适合科研与原型开发
* 曝光速度慢，吞吐率低
* 系统复杂、成本高

---

## 3.2 扫描方式 | Scanning Strategies

1. 栅格扫描（Raster Scan）

逐点扫描整个图形区域。适用于大面积或图像式写入。

Beam scans pixel by pixel across the area. Suitable for bitmap-like patterning.

2. 矢量扫描（Vector Scan）

仅扫描实际需要写入的区域，减少空白区域曝光。

Beam is directed only to regions with features. Faster and more efficient.

3. 区块曝光（Shape-Based / Block Exposure）

将图形分割为矩形区域进行曝光。

Pattern is decomposed into rectangles and exposed block by block.

---


## 3.3 抗蚀剂材料 | Resists for EBL

1. PMMA（聚甲基丙烯酸甲酯）
	•	最常用正性电子束抗蚀剂
	•	分辨率高（可达5 nm），显影后为负像

Most widely used positive-tone resist; high resolution, develops as negative image.

2. ZEP520, ZEP7000
* 分辨率略低于PMMA，但感光性更强、显影更快

Improved sensitivity and faster development over PMMA.

3. HSQ（氢硅氧烷）
	•	无机负性抗蚀剂，分辨率极高（~2 nm）
	•	显影后为SiOx类材料，可作为掩模

Inorganic negative resist; extremely high resolution, turns into SiOx upon exposure.

---

### 3.4 曝光参数与剂量控制 | Exposure Dose and Parameters
	•	剂量（Dose）：单位面积接受的电子数量，单位为 µC/cm²。
Dose = beam current × exposure time / area
	•	加速电压：常为 20–100 kV，影响穿透深度和散射范围。
	•	束流强度：影响写入速度与剂量控制。
	•	步进尺寸（Step Size）：扫描的空间精度。

适当剂量控制是图形保真与分辨率的关键。

Proper dose ensures pattern fidelity and resolution.

---

### 3.5 近邻效应与校正 | Proximity Effect and Correction

电子在抗蚀剂中传播时，会发生弹性与非弹性散射，导致电子扩散至邻近区域，使得图形边缘变宽，称为“近邻效应”。

Proximity effect arises from forward and backscattering of electrons, broadening features beyond intended exposure areas.

校正方法 | Correction Techniques
	•	剂量调制（dose modulation）
	•	区域填充（background correction）
	•	模拟与软件辅助校正（Monte Carlo simulation）

---

## 3.6 应用与局限 | Applications and Limitations

应用 | Applications
* 高分辨率纳米结构制造
* 光子晶体、纳米光子器件
* 单电子器件、量子点阵列
* 探针头、MEMS结构精细加工

局限 | Limitations
* 写入速度慢（低吞吐）
* 设备昂贵、维护复杂
* 抗蚀剂稳定性与工艺窗口小

---

## 3.7 小结 | Summary

电子束光刻以其极高的分辨率和灵活性，在科研和先进纳米器件开发中具有不可替代的作用。

EBL provides unmatched resolution and flexibility, making it essential for advanced research and prototyping in nanofabrication.

然而，其低吞吐、高成本限制了其在大规模生产中的应用。

However, its low throughput and high cost limit its use in high-volume manufacturing.

---
