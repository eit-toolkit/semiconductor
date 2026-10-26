# EIT-SP

**One-file, zero-dependency interactive toolkits for teaching and learning physics**

> **Educational Interactive Toolkit for Semiconductor Physics (EIT-SP)**
> 中文版（Chinese version）：[README_cn.md](README_cn.md)

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Dependencies: none](https://img.shields.io/badge/dependencies-none-brightgreen.svg)
![Tools: 35](https://img.shields.io/badge/tools-35-orange.svg)
![Build: not required](https://img.shields.io/badge/build-not%20required-lightgrey.svg)
![Version: 0.20](https://img.shields.io/badge/version-0.20-blue.svg)

---

## What this is

A series of **single-file** interactive teaching tools for semiconductor physics: crystal structure and energy bands, impurities and defects, carrier statistics, conductivity, non-equilibrium carriers, pn junctions, semiconductor surfaces and MIS structures, plus optical, thermoelectric and magnetic effects.

Each tool is one `.html` file: **no build step, no npm, no CDN, no network requests**. Double-click and it runs. It works offline, fits on a USB stick, can be emailed to a student as an attachment, and will still open ten years from now.

The tools follow the chapter order of a standard Chinese semiconductor-physics textbook ( Liu Enke, *The Physics of Semiconductors* ), so they can be dropped straight into the corresponding weeks of a course syllabus.

- Index (Chinese file names): [`index_cn.htm`](index_cn.htm)
- Index (pinyin file names, for servers that do not handle non-ASCII paths): [`index_pinyin.htm`](index_pinyin.htm)
- **English index**: [`index_en.htm`](index_en.htm) — same plain layout as the Chinese one, English tool names grouped by chapter. (No pinyin build is maintained for it — English readers land on hosts where UTF-8 filenames work, unlike course servers that rename non-ASCII files.)

This collection was developed with AI assistance.

> **Languages.** The tools are bilingual (Chinese / English).

## Tools

| Chapter | Tool | Filename |
|---|---|---|
| Preliminaries | One-Dimensional Square Well | [一维方形势阱交互教学工具.html](./一维方形势阱交互教学工具.html) |
| Preliminaries | Hydrogen Atom: 3D Schrödinger Equation | [氢原子三维薛定谔方程交互教学工具.html](./氢原子三维薛定谔方程交互教学工具.html) |
| Ch. 1 Electronic States | Crystal Lattices | [半导体晶格交互教学工具.html](./半导体晶格交互教学工具.html) |
| Ch. 1 | sp³ Hybridization | [sp3杂化交互教学工具.html](./sp3杂化交互教学工具.html) |
| Ch. 1 | Interatomic Spacing and Level Splitting | [原子间距与能级分裂交互教学工具.html](./原子间距与能级分裂交互教学工具.html) |
| Ch. 1 | Bloch Waves and Energy Bands | [布洛赫波与能带交互教学工具.html](./布洛赫波与能带交互教学工具.html) |
| Ch. 1 | Cyclotron Resonance | [回旋共振实验交互教学工具.html](./回旋共振实验交互教学工具.html) |
| Ch. 1 | Semiconductor Energy Bands | [半导体能带交互教学工具.html](./半导体能带交互教学工具.html) |
| Ch. 1 | Direct and Indirect Band Gaps | [直接带隙与间接带隙交互教学工具.html](./直接带隙与间接带隙交互教学工具.html) |
| Ch. 2 Impurities and Defects | Doping and Band Structure | [掺杂及其对能带影响交互教学工具.html](./掺杂及其对能带影响交互教学工具.html) |
| Ch. 2 | Defects in Semiconductors | [半导体缺陷可视化交互教学工具.html](./半导体缺陷可视化交互教学工具.html) |
| Ch. 2 | Hydrogen-like Model of Impurities | [半导体掺杂的类氢模型交互教学工具.html](./半导体掺杂的类氢模型交互教学工具.html) |
| Ch. 3 Carrier Statistics | Constant-Energy Surfaces and DOS | [k空间等能面与态密度交互教学工具.html](./k空间等能面与态密度交互教学工具.html) |
| Ch. 3 | Fermi-Dirac Distribution | [费米分布交互教学工具.html](./费米分布交互教学工具.html) |
| Ch. 3 | Carrier Concentration from DOS and Occupancy | [态密度与占据几率计算载流子浓度交互教学工具.html](./态密度与占据几率计算载流子浓度交互教学工具.html) |
| Ch. 4 Conductivity | Drift and Diffusion | [载流子漂移与扩散运动交互教学工具.html](./载流子漂移与扩散运动交互教学工具.html) |
| Ch. 4 | Ionized Impurity Scattering | [电离杂质散射对载流子影响交互教学工具.html](./电离杂质散射对载流子影响交互教学工具.html) |
| Ch. 4 | Phonons in Semiconductors | [半导体中的声子交互教学工具.html](./半导体中的声子交互教学工具.html) |
| Ch. 4 | Deformation Potential & Piezoelectric Scattering | [形变势与压电势散射交互教学工具.html](./形变势与压电势散射交互教学工具.html) |
| Ch. 4 | External Fields and Carrier Distribution | [外部作用对载流子分布的影响交互教学工具.html](./外部作用对载流子分布的影响交互教学工具.html) |
| Ch. 4 | Boltzmann Transport Equation | [玻耳兹曼方程交互教学工具.html](./玻耳兹曼方程交互教学工具.html) |
| Ch. 5 Non-equilibrium Carriers | Generation and Recombination | [载流子产生与复合交互教学工具.html](./载流子产生与复合交互教学工具.html) |
| Ch. 5 | Minority-Carrier Drift and Diffusion | [非平衡少子漂移与扩散交互教学工具.html](./非平衡少子漂移与扩散交互教学工具.html) |
| Ch. 6 pn Junction | pn-Junction Carrier Transport | [PN结界面载流子输运交互教学工具.html](./PN结界面载流子输运交互教学工具.html) |
| Ch. 6 | pn-Junction Electrostatics | [PN结电势电场与电荷分布交互教学工具.html](./PN结电势电场与电荷分布交互教学工具.html) |
| Ch. 8 Surfaces and MIS | Surface Boundary Conditions | [半导体表面边界条件交互教学工具.html](./半导体表面边界条件交互教学工具.html) |
| Ch. 8 | MIS: Bias, Surface Potential, Charge & Capacitance | [MIS结构偏压表面势电荷电容交互教学工具.html](./MIS结构偏压表面势电荷电容交互教学工具.html) |
| Beyond: optics | Optical Absorption | [半导体光吸收交互教学工具.html](./半导体光吸收交互教学工具.html) |
| Beyond: optics | Photoconductivity | [光生电导效应交互教学工具.html](./光生电导效应交互教学工具.html) |
| Beyond: thermoelectric | Seebeck Effect | [塞贝克效应交互教学工具.html](./塞贝克效应交互教学工具.html) |
| Beyond: magnetic | Hall Effect | [霍尔效应交互教学工具.html](./霍尔效应交互教学工具.html) |
| Expansions | Graphene: sp² Hybridization and the π Bond — Dawn of 2D | [sp2杂化与π键形成交互教学工具.html](./sp2杂化与π键形成交互教学工具.html) |
| Expansions | Perovskite Solar Cells — Light of the World | [钙钛矿太阳能电池交互教学工具.html](./钙钛矿太阳能电池交互教学工具.html) |
| Expansions | Spintronics — Hidden in Plain Sight | [自旋电子学交互教学工具.html](./自旋电子学交互教学工具.html) |
| Expansions | Tunnel FET: Band-to-Band Tunneling — The Forbidden Shortcut | [隧穿场效应管交互教学工具.html](./隧穿场效应管交互教学工具.html) |

## Design principles

1. **Education-oriented, image-first.** The aim is to help students develop physical intuition through a clear physical picture, not to display a derivation. Explanatory text, non-essential parameters and intermediate algebra are deliberately simplified, and quantities that do not matter are simply held fixed — but the physical core, the relations between quantities, and the conservation and dimensional constraints are never trimmed.
2. **Physics-based: solved from equations, never hard-coded.** Every curve on the canvas and every number in the readout panel is obtained by solving the governing equations at run time, not from pre-computed demo data baked into the page. Any conclusive number that shares a source with the code is recomputed at run time, so changing a parameter can never leave the prose stale.
3. **Single file, zero dependencies, no build step.** All HTML, CSS, JavaScript and drawing code live in one file, with no external libraries and no font files. This is a deliberate trade: modularity is sacrificed for "works offline, can be archived, byte-for-byte checkable, still runs in ten years".
4. **Intuitive navigation.** The controls *are* the state, readouts follow along, legends and hints sit next to what they describe, and everything fits on one screen — a student can tell which knob to turn and where to look afterwards without reading a manual.
5. **LaTeX-style formula typography.** Physical quantities in italics, descriptive subscripts and units upright, exponents as real superscripts; the canvas and DOM rendering paths share one set of typesetting constants, so the same quantity looks identical on the plot and in the readout.
6. **A uniform interaction structure.** Every tool is built from a control panel, a readout panel, a guided-inquiry section and a set of challenge questions, so switching between tools requires no new learning.
7. **Results can be checked.** What you read off the plot and what the readout panel shows come from the same source — one computation in two forms — so a number can be verified on the spot.
8. **Organized in the order the subject itself unfolds.** Electronic states, impurities and defects, carrier statistics, then conductivity, non-equilibrium carriers, pn junctions, surfaces and MIS, and finally the optical, thermoelectric and magnetic effects: bands and statistics first, because transport only makes sense once they are in place, and junctions and devices only after that. This is the logical order of semiconductor physics rather than the idiosyncrasy of one book. Chapter names and numbers follow Liu Enke's *The Physics of Semiconductors* only so that the set can be dropped straight into an existing syllabus; with a different textbook the same sequence still holds.

## Quick start

**Try it in your browser:** [eit-toolkit.github.io/semiconductor/index_en.htm](https://eit-toolkit.github.io/semiconductor/index_en.htm)

To keep a local copy:

```bash
git clone https://github.com/eit-toolkit/semiconductor.git
cd semiconductor
```

Then double-click any `.html` file (or drag it into a browser). No `npm install`, no local server.

Also with Gitee (the two sites are published and kept in sync):

```bash
git clone https://gitee.com/doctorwanghao/semiconductor.git
```

To use the whole set in class, serve the directory from any static host (or GitHub Pages); the entry page is `index_en.htm` (English) or `index_cn.htm` (Chinese file names); use `index_pinyin.htm` (pinyin file names) when the server does not support non-ASCII paths.

## Fonts

Formulas prefer **Cambria Math** (shipped with Windows and Microsoft Office), falling back to `STIX Two Math → Latin Modern Math → Times New Roman`.

- Windows / macOS: usually nothing to do.
- Linux: install STIX Two Math, e.g. `sudo apt install fonts-stix` (Debian/Ubuntu), or via a TeX distribution.
- If none of these are present, formulas degrade to a Times-like serif: still readable, with minor differences in the placement of integral signs and radical bars.

## Citing

If you use these tools, please cite them (see also [`CITATION.cff`](CITATION.cff)):

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

Please also give the filename of the tool you used and the date you accessed it, since the tools keep evolving.

## License

[MIT License](LICENSE) — free to use, copy, modify, merge, publish, distribute, sublicense and sell, including for commercial purposes.

The only obligation is to **keep the copyright and license notice in copies**. One non-binding request: if you use or redistribute the tools, please keep the attribution line at the bottom of each page, so users can find the latest version and report problems.

## Contact and acknowledgements

The collection grew out of the smart-course program for *Semiconductor Physics* at the School of Physics and Technology, Wuhan University.

Feedback and collaboration: doctorwanghao@qq.com
