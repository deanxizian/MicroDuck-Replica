# kissqy HAT AMP2.0

由 kissqy 2026-10-15 嘉立创专业版工程导入 KiCad 10.99。本目录保留备用设计资料；本机采用 D1 HAT。

| 资料 | 文件 |
| --- | --- |
| KiCad | [工程](KiCad/ProPrj_HAT_REVA_SCH_2026-10-15.kicad_pro) |
| 嘉立创 | [Gerber](JLC/Gerber-reference.zip) · [原理图](JLC/schematic.pdf) · [BOM](JLC/BOM-reference.csv) · [坐标](JLC/positions-kicad-reference.csv) |
| 检查记录 | [导入检查](Verification/import-verification.json) · [过孔恢复](Verification/restored-footprint-vias.json) · [缺失模型](Verification/missing-3d-models.json) |

板框约 65×30.9 mm，两层板。U2 的五个 GND 散热孔已恢复为板级过孔，移动 U2 时需同步移动。

待核对：R33 原理图为 0 Ω、PCB 为 150 Ω；23 类元件的 STEP 模型未随源工程提供。制造输出保留 KiCad 原始 BOM／坐标格式，完整 ERC/DRC 与 SMT 审核尚未完成。

源 Git blob：`21e1d3ad829b4a5dcc0477ee80bbe1a763f694b1`。遵循 kissqy 个人非商业许可及第三方原许可，见 [来源说明](../../NOTICE.md)。
