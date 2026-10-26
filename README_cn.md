# EIT-SP

**One-file, zero-dependency interactive toolkits for teaching and learning physics**

> **半导体物理交互式教学工具箱**
> 中文名：半导体物理交互式教学工具箱（Bàndǎotǐ Wùlǐ Jiāohùshì Jiàoxué Gōngjùxiāng）
> Educational Interactive Toolkit for Semiconductor Physics (EIT-SP)
>
> [English version: README.md](README.md)

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Dependencies: none](https://img.shields.io/badge/dependencies-none-brightgreen.svg)
![Tools: 35](https://img.shields.io/badge/tools-35-orange.svg)
![Build: not required](https://img.shields.io/badge/build-not%20required-lightgrey.svg)
![Version: 0.10](https://img.shields.io/badge/version-0.10-blue.svg)

---

## 这是什么

一系列**单文件**交互式教学工具，覆盖《半导体物理学》从晶格结构、能带、杂质缺陷、统计分布、导电性、非平衡载流子、pn 结，到表面与 MIS 结构，以及光学、热电、磁学效应。

工具集持续增补：成熟一个发布一个，尚未成熟的暂不放出，因此下面清单的内容会随时间变化。

每个工具就是一个 `.html` 文件：**没有构建步骤、没有 npm、没有 CDN、没有外部请求**。双击打开即可运行，可以离线用、可以拷进 U 盘、可以当邮件附件发给学生，十年后依然能打开。

工具按刘恩科《半导体物理学》的章序组织，可直接嵌入课程大纲对应章节。

- 在线索引（本机/中文文件名）：[`index_cn.htm`](index_cn.htm)
- 部署索引（拼音文件名，兼容不支持中文路径的服务器）：[`index_pinyin.htm`](index_pinyin.htm)
- 英文索引：[`index_en.htm`](index_en.htm)（索引本身是英文）

每个工具都是**中英双语**。

本工具集使用 AI 辅助开发（developed with AI assistance）。

## 工具清单

| 章节 | 工具 | English | 文件 |
|---|---|---|---|
| 预备知识 | 一维方形势阱 | One-Dimensional Square Well | [打开](./一维方形势阱交互教学工具.html) |
| 预备知识 | 氢原子三维薛定谔方程 | Hydrogen Atom: 3D Schrödinger Equation | [打开](./氢原子三维薛定谔方程交互教学工具.html) |
| 第一章 半导体中的电子状态 | 半导体晶格结构 | Crystal Lattices | [打开](./半导体晶格交互教学工具.html) |
| 第一章 | 金刚石结构 sp³ 杂化 | sp³ Hybridization | [打开](./sp3杂化交互教学工具.html) |
| 第一章 | 原子间距与能级分裂 | Interatomic Spacing and Level Splitting | [打开](./原子间距与能级分裂交互教学工具.html) |
| 第一章 | Bloch 波与能带 | Bloch Waves and Energy Bands | [打开](./布洛赫波与能带交互教学工具.html) |
| 第一章 | 回旋共振实验 | Cyclotron Resonance | [打开](./回旋共振实验交互教学工具.html) |
| 第一章 | 半导体能带 | Semiconductor Energy Bands | [打开](./半导体能带交互教学工具.html) |
| 第一章 | 直接带隙与间接带隙 | Direct and Indirect Band Gaps | [打开](./直接带隙与间接带隙交互教学工具.html) |
| 第二章 杂质与缺陷 | 掺杂及其对能带的影响 | Doping and Band Structure | [打开](./掺杂及其对能带影响交互教学工具.html) |
| 第二章 | 半导体缺陷可视化 | Defects in Semiconductors | [打开](./半导体缺陷可视化交互教学工具.html) |
| 第二章 | 半导体掺杂的类氢模型 | Hydrogen-like Model of Impurities | [打开](./半导体掺杂的类氢模型交互教学工具.html) |
| 第三章 载流子的统计分布 | k 空间等能面与态密度 | Constant-Energy Surfaces and DOS | [打开](./k空间等能面与态密度交互教学工具.html) |
| 第三章 | 费米分布 | Fermi-Dirac Distribution | [打开](./费米分布交互教学工具.html) |
| 第三章 | 态密度与占据几率计算载流子浓度 | Carrier Concentration from DOS and Occupancy | [打开](./态密度与占据几率计算载流子浓度交互教学工具.html) |
| 第四章 半导体的导电性 | 载流子漂移与扩散运动 | Drift and Diffusion | [打开](./载流子漂移与扩散运动交互教学工具.html) |
| 第四章 | 电离杂质散射 | Ionized Impurity Scattering | [打开](./电离杂质散射对载流子影响交互教学工具.html) |
| 第四章 | 半导体中的声子 | Phonons in Semiconductors | [打开](./半导体中的声子交互教学工具.html) |
| 第四章 | 形变势与压电势散射 | Deformation Potential & Piezoelectric Scattering | [打开](./形变势与压电势散射交互教学工具.html) |
| 第四章 | 外部作用对载流子分布的影响 | External Fields and Carrier Distribution | [打开](./外部作用对载流子分布的影响交互教学工具.html) |
| 第四章 | 玻耳兹曼方程 | Boltzmann Transport Equation | [打开](./玻耳兹曼方程交互教学工具.html) |
| 第五章 非平衡载流子 | 载流子产生与复合 | Generation and Recombination | [打开](./载流子产生与复合交互教学工具.html) |
| 第五章 | 非平衡少子漂移与扩散 | Minority-Carrier Drift and Diffusion | [打开](./非平衡少子漂移与扩散交互教学工具.html) |
| 第六章 pn 结 | pn 结界面载流子输运 | pn-Junction Carrier Transport | [打开](./PN结界面载流子输运交互教学工具.html) |
| 第六章 | pn 结电势、电场与电荷分布 | pn-Junction Electrostatics | [打开](./PN结电势电场与电荷分布交互教学工具.html) |
| 第八章 表面与 MIS | 半导体表面边界条件 | Surface Boundary Conditions | [打开](./半导体表面边界条件交互教学工具.html) |
| 第八章 | MIS 结构：偏压、表面势、电荷与电容 | MIS: Bias, Surface Potential, Charge & Capacitance | [打开](./MIS结构偏压表面势电荷电容交互教学工具.html) |
| 后续：光学 | 半导体光吸收 | Optical Absorption | [打开](./半导体光吸收交互教学工具.html) |
| 后续：光学 | 光生电导效应 | Photoconductivity | [打开](./光生电导效应交互教学工具.html) |
| 后续：热电 | 塞贝克效应 | Seebeck Effect | [打开](./塞贝克效应交互教学工具.html) |
| 后续：磁学 | 霍尔效应 | Hall Effect | [打开](./霍尔效应交互教学工具.html) |
| 扩展包 | 石墨烯：sp² 杂化与 π 键——二维黎明 | Graphene: sp² Hybridization and the π Bond — Dawn of 2D | [打开](./sp2杂化与π键形成交互教学工具.html) |
| 扩展包 | 钙钛矿太阳能电池——世界之光 | Perovskite Solar Cells — Light of the World | [打开](./钙钛矿太阳能电池交互教学工具.html) |
| 扩展包 | 自旋电子学——闹市隐者 | Spintronics — Hidden in Plain Sight | [打开](./自旋电子学交互教学工具.html) |
| 扩展包 | 隧穿场效应管：带间隧穿——禁地捷径 | Tunnel FET: Band-to-Band Tunneling — The Forbidden Shortcut | [打开](./隧穿场效应管交互教学工具.html) |

## 设计原则

1. **教学导向，图像优先。** 目标是帮学生建立物理图像，而不是演示公式推导。因此说明文字、非核心参数与中间展开式可以简化，该固定就固定；但物理核心、量与量之间的关系、守恒与量纲约束，一处也不省。
2. **物理为本，方程现算。** 图上的每条曲线、读数面板的每个数字，都由物理方程在运行时求解，而不是预先算好、写死在页面里的演示数据；凡与代码共用同一来源的结论性数字都现算，避免参数一改文案就腐化。
3. **单文件、零依赖、无需构建。** 所有 HTML、CSS、JavaScript 与绘图代码都在一个文件内，不引用任何外部库或字体文件。这是刻意的取舍：牺牲工程上的模块化，换取「可离线、可归档、可逐字节校验、十年后仍可运行」。
4. **界面自解释，上手即用。** 控件即状态、读数随动、图例与提示就近摆放，一屏之内看得全：学生不看说明书也能凭直觉找到该动哪个旋钮，以及动完之后该看哪里。
5. **公式排版遵循 LaTeX 惯例。** 物理量斜体、描述性下标与单位正体、幂次使用真上标；画布与 DOM 两条渲染路径共用同一套排版常量，保证「图上」与「读数里」的同一个量长得一样。
6. **统一的交互结构。** 每个工具都由右栏控制面板、读数面板、底部「引导探究」与一组挑战题构成，学生跨工具切换时无需重新学习界面。
7. **结果可核对。** 图上读到的量与读数面板同源，是同一份计算结果的两副面孔，学生可以当场核算。
8. **按学科自身的展开次序组织。** 从电子状态、杂质与缺陷、统计分布，到导电性、非平衡载流子、pn 结、表面与 MIS，再到光学、热电与磁学效应——先有能带与统计，才谈得上输运，进而才是结与器件。这条顺序就是半导体物理知识自身的展开次序；章名与编号沿用刘恩科《半导体物理学》只是为了方便挂进课程大纲，换成别的教材，顺序照样成立。

## 快速开始

```bash
git clone https://github.com/eit-toolkit/semiconductor.git
cd semiconductor
```

然后双击任意 `.html` 文件即可（或拖进浏览器）。无需 `npm install`，无需本地服务器。

同样发布在 Gitee（两个站点同步更新，内容一致）：

```bash
git clone https://gitee.com/doctorwanghao/semiconductor.git
```

想在课堂上整站使用，直接把目录挂到任意静态服务器（或 GitHub Pages）上，入口为 `index_en.htm`（英文）或 `index_cn.htm`（中文文件名）；服务器不支持中文路径时改用 `index_pinyin.htm`（拼音文件名）。

## 字体说明

数学公式首选 **Cambria Math**（Windows 与 Microsoft Office 自带），回退链为 `STIX Two Math → Latin Modern Math → Times New Roman`。

- Windows / macOS：通常无需任何设置。
- Linux：建议安装 STIX Two Math，例如 `sudo apt install fonts-stix`（Debian/Ubuntu），或通过 TeX 发行版安装。
- 若上述字体都不存在，公式退化为 Times 衬线体，仍可读，但积分号与根号横线的位置会有细微差异。

## 引用

如果使用本工具，请引用（另见 [`CITATION.cff`](CITATION.cff)）：

```bibtex
@software{eit_sp_2026,
  author       = {Wang, Hao},
  title        = {EIT-SP: Educational Interactive Toolkit for Semiconductor Physics},
  year         = {2026},
  publisher    = {Zenodo},
  institution  = {Wuhan University},
  url          = {https://github.com/eit-toolkit/semiconductor},
  license      = {MIT}
}
```

建议在论文中同时给出所用工具的文件名与访问日期，因为工具会持续迭代。

## 许可

[MIT License](LICENSE) — 可自由使用、复制、修改、合并、出版、分发、再许可与销售，包括商业用途。

唯一的义务是**在副本中保留版权声明与许可声明**。此外我们有一项非强制的请求：使用或转载这些工具时，请保留页面底部的出处行，以便使用者能找到最新版本并反馈问题。

## 联系与致谢

本工具集源于武汉大学物理学院《半导体物理》智慧课程建设。

反馈与协作：doctorwanghao@qq.com
