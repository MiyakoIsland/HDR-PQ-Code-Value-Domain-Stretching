# HDR PQ Code-Value-Domain Stretching

**A public technical disclosure of HDR luminance up-mapping based on PQ code-value-domain stretching.**

本仓库用于公开记录一种基于 PQ 编码值域拉伸的 HDR 亮度向上映射通用技术方案。

This repository provides a public technical disclosure of a general method for HDR luminance up-mapping based on stretching values directly in the PQ-encoded domain.

---

## Technical Disclosure / 技术公开说明书

本技术公开说明书分为中文版和英文版。两份文档描述的是同一项核心技术方案。

This technical disclosure is available in Chinese and English. Both documents describe the same core technical method.

### 中文版

[HDR PQ 编码值域拉伸技术公开说明书（PDF）](HDR_PQ_Code_Value_Domain_Stretching_Technical_Disclosure_CN.pdf)

### English Version

[HDR PQ Code-Value-Domain Stretching Technical Disclosure (PDF)](HDR_PQ_Code_Value_Domain_Stretching_Technical_Disclosure_EN.pdf)

---

## Core Concept / 核心思想

本技术的核心是直接在 PQ 编码值域中进行亮度向上映射，而不是仅在线性物理亮度域中完成映射后再转换回 PQ。

The core concept is to perform luminance up-mapping directly in the PQ code-value domain, rather than performing the entire mapping only in the linear physical-light domain and converting the result back to PQ afterward.

核心映射关系：

\[
P_{\mathrm{mapped}} = P + \Delta P \cdot F(x)
\]

具体定义、映射函数构造、处理顺序、物理亮度重建以及辅助实现方式，请以本仓库中的正式技术公开说明书为准。

For the precise definitions, mapping-function construction, processing order, physical luminance reconstruction, and auxiliary implementation methods, please refer to the formal technical disclosure PDFs in this repository.

---

## Scope of This Repository / 本仓库范围

本仓库用于保存和公开这项通用技术方案及其技术说明文档。

This repository is intended to preserve and publicly disclose the general technical method and its documentation.

本仓库不是着色器软件的源代码仓库。具体的软件实现与应用示例应以各自对应的项目为准。

This is not a shader software source-code repository. Software implementations and application examples should be consulted in their respective projects.

---

## Public Record / 公开记录

本仓库通过公开的 GitHub 页面及文件提交历史，记录本技术说明文档的公开内容。

The public GitHub repository and its file history provide a record of the disclosed technical documentation.

