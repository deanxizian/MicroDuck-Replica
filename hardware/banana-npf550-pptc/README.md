# Banana NP-F550 · 0.5-PPTC

本项目自行打样的细长取电板。基于 jyg9 的 Banana 设计，加串联 PPTC、右侧出线焊盘和对应机械配合。源许可为 CERN-OHL-P v2，见 [许可](../../LICENSES/CERN-OHL-P-2.0.txt)。

- [KiCad 工程](kicad/banana_pptc.kicad_pro)：原理图、PCB、本地库与 3D 参考模型。
- [Gerber.zip](jlc/Gerber.zip)：与本地用于嘉立创上传的丝印版本一致；ZIP 内含铜层、阻焊、丝印和钻孔。
- [BOM](jlc/Banana-PPTC-BOM.csv) · [SMT BOM](jlc/Banana-PPTC-SMT-BOM.csv) · [贴装位置](jlc/Banana-PPTC-SMT-position.csv) · [接线表](jlc/Banana-PPTC-wiring.csv) · [原理图 PDF](jlc/Banana-PPTC-schematic.pdf)。

板框约 39.19 × 6.79 mm；FR4 1.6 mm、2 层、1 oz；预选绿油白字、OSP。31 号电池仓定位卡槽净高 1.70 mm，入口 1.80 mm；与 1.6 mm PCB 对应的总名义余量分别为 0.10 / 0.20 mm，仍受实际板厚和打印公差影响。

接线：电池正极 J1 → F1 → J3.1 → HUB VIN；电池负极 J2 → J3.2 → HUB GND。F1 在左、输出焊盘在右；以原理图和板上标记确认正负极。先焊贴片件、插入板，再焊取电针与引线。

F1 设计参考为 Littelfuse 2920L700/12MR；计划使用伯特 BSMD2920-700-12V，替代器件的封装、电气及热特性尚待规格书确认。不要把参考 MPN 当作已验证替代。两根 U6068 针在 Blender 中的插入深度仍是装配参考。

保留的 ERC/DRC 记录为零错误、零未连接；这不包含实物温升、短路保护和接触可靠性测试。见 [verification](verification/)。
