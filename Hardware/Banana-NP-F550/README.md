# Banana NP-F550

NP-F550 电池取电板，版本 0.5-PPTC。基于 jyg9 Banana 设计，增加串联 PPTC 和右侧出线焊盘。采用自行制板、手工焊接方式。

| 资料 | 文件 |
| --- | --- |
| KiCad | [工程](KiCad/banana_pptc.kicad_pro) |
| 嘉立创 | [Gerber](JLC/Gerber.zip) · [BOM](JLC/Banana-PPTC-BOM.csv) · [原理图](JLC/Banana-PPTC-schematic.pdf) |
| SMT 参考 | [BOM](JLC/Banana-PPTC-SMT-BOM.csv) · [贴装坐标](JLC/Banana-PPTC-SMT-position.csv) |
| 接线与检查 | [接线表](JLC/Banana-PPTC-wiring.csv) · [Verification](Verification/) |

板框约 39.19×6.79 mm，FR4 1.6 mm、2 层、1 oz、绿油 OSP。电池仓定位卡槽净高 1.70 mm，入口 1.80 mm。

## 焊接与安装

**PCB 为裸板。F1（PTC）、J1／J2 两根香蕉取电针和 J3 电源引线均需自行焊接。**

1. 焊接 F1 贴片 PTC。
2. 将 PCB 卡入 31 号电池仓。
3. 焊接 U6068 取电针与电源引线，检查焊点和极性后接电池。

电池正极 J1 → F1 → J3.1 → HUB VIN；电池负极 J2 → J3.2 → HUB GND。安装方向为 F1 在左、出线焊盘在右。

F1 设计参考为 Littelfuse 2920L700/12MR，采购型号为伯特 BSMD2920-700-12V；替代型号的电气与热特性待规格书核对。现有 ERC/DRC 记录为零错误、零未连接，实物温升、保护动作及取电针配合待测试。

采用 [CERN-OHL-P v2](../../LICENSES/CERN-OHL-P-2.0.txt)。采购明细见 [BOM](../../BOM/README.md)。
