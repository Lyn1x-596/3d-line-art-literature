# 三维线条艺术相关论文

| 序号 | 论文 | 发表 | 主要工作 | GitHub地址 |
|---|---|---|---|---|
| 1 | [Single-Line Drawing Generation via Semantics-Driven Optimization（SLDgen）](https://tanguymagne.com/publications/sldgen/) | CGF 2026 | 利用扩散模型引导优化单条连续曲线，从图像或文字生成二维单线画。 | [github.com/tanguymagne/SLDgen](https://github.com/tanguymagne/SLDgen) |
| 2 | [Optimizing 4D Wires for Sparse 3D Abstraction](https://arxiv.org/abs/2605.11977) | arXiv 2026 | 用单条连续、粗细可变的三维B样条表示物体，实现图像到三维线条抽象及多视角线雕生成。 | 无 |
| 3 | [Fabricable 3D Wire Art](https://kenji-tojo.github.io/publications/fab3dwire/) | SIGGRAPH 2024 | 从模型、图像或文字生成三维线雕，结合几何约束和打印夹具辅助实体制作。 | [github.com/kenji-tojo/fab3dwire](https://github.com/kenji-tojo/fab3dwire) |
| 4 | [ViewCraft3D: High-Fidelity and View-Consistent 3D Vector Graphics Synthesis](https://homepage.marvolo.top/VC3D_page/) | NeurIPS 2025 | 从单张图像获得三维先验，再通过几何提取、曲线拟合和细化生成多视角一致的三维矢量图。 | 无 |
| 5 | [Diff3DS: Generating View-Consistent 3D Sketch via Differentiable Curve Rendering](https://yiboz2001.github.io/Diff3DS/) | ICLR 2025 | 通过可微曲线渲染，将二维图像监督传回三维曲线，实现图像或文字驱动的三维草图生成。 | [github.com/yiboz2001/Diff3DS](https://github.com/yiboz2001/Diff3DS)¹ |
| 6 | [WIR3D: Visually-Informed and Geometry-Aware 3D Shape Abstraction](https://threedle.github.io/wir3d/) | ICCV 2025 | 结合局部视觉特征、关键点和表面约束，将三维形状抽象为保留几何与细节的稀疏曲线。 | [github.com/threedle/wir3d](https://github.com/threedle/wir3d) |
| 7 | [View-Independent Wire Art Modeling via Manifold Fitting](https://doi.org/10.1111/cgf.70247) | CGF 2025 | 通过流形拟合将三维模型转换为线艺，兼顾结构连接、线条简洁性和不同视角的表达效果。 | [github.com/THLsword/3DWireArt](https://github.com/THLsword/3DWireArt) |
| 8 | [3Doodle: Compact Abstraction of Objects with 3D Strokes](https://changwoonchoi.github.io/3Doodle/) | SIGGRAPH 2024 | 从多视图图像优化三维特征线和视角相关轮廓，生成紧凑的三维草图。 | [github.com/changwoonchoi/3Doodle](https://github.com/changwoonchoi/3Doodle) |
| 9 | [Empowering Vector Graphics with Consistently Arbitrary Viewing and View-dependent Visibility（Dream3DVG）](https://arxiv.org/abs/2505.21377) | CVPR 2025 | 联合三维高斯和矢量图优化，生成支持任意视角观察、能够处理遮挡的三维矢量图形。 | [github.com/chenxinl/Dream3DVG](https://github.com/chenxinl/Dream3DVG) |
| 10 | [Wired Perspectives: Multi-View Wire Art Embraces Generative AI（DreamWire）](https://dreamwireart.github.io/) | CVPR 2024 | 根据各视角的图像或文字提示优化三维曲线，使同一线雕从不同角度呈现不同内容。 | [github.com/WinKawaks/DreamWire](https://github.com/WinKawaks/DreamWire) |
| 11 | [Reconstruction of a 3D Wireframe from a Single Line Drawing via Generative Depth Estimation](https://arxiv.org/abs/2604.13549) | arXiv 2026 | 利用条件生成模型预测二维线稿笔画的深度，在保持原投影的基础上重建三维线框。 | [github.com/eltonc01/sketch-depth-diffusion](https://github.com/eltonc01/sketch-depth-diffusion) |
| 12 | [Lifting Freehand Concept Sketches into 3D](https://github.com/ygryadit/LiftConceptSketches3D) | SIGGRAPH Asia 2020 | 将手绘设计草图中的直线和曲线笔画提升到三维，重建设计对象的空间结构。 | [github.com/ygryadit/LiftConceptSketches3D](https://github.com/ygryadit/LiftConceptSketches3D) |
| 13 | [Layer3D: A 3D Layered Representation for Multiview Vector Graphics](https://doi.org/10.1111/cgf.70375) | CGF 2026 | 使用可分解的三维隐式基元和前后排序渲染，生成具有跨视角对应关系的矢量图层。 | 无 |
| 14 | [3DrawAgent: Teaching LLM to Draw in 3D with Early Contrastive Experience](https://qi-cvlab.github.io/3DrawAgent/) | CVPR 2026 | 利用大语言模型规划三维曲线，并通过多视角评分和候选对比经验改进三维草图生成。 | [github.com/Qi-CVLab/3DrawAgent](https://github.com/Qi-CVLab/3DrawAgent) |

“无”表示截至2026年11月2日核查未找到官方公开GitHub仓库；arXiv表示预印本。本表为已整理的14篇相关文献。

¹ Diff3DS的GitHub仓库目前主要提供README和网盘下载入口，源码包内容尚未核验。
