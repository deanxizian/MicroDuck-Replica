# kissqy HAT AMP2.0 · KiCad 与制造参考

源为 kissqy 2026-10-15 AMP2.0 嘉立创专业版工程，Git blob `21e1d3ad829b4a5dcc0477ee80bbe1a763f694b1`。使用 KiCad 10.99 开发版 20261031 导入。

- [KiCad 工程](kicad/ProPrj_HAT_REVA_SCH_2026-10-15.kicad_pro)
- [Gerber 参考 ZIP](jlc-reference/Gerber-reference.zip) · [原理图 PDF](jlc-reference/schematic.pdf)
- [BOM 参考](jlc-reference/BOM-reference.csv) · [KiCad 坐标参考](jlc-reference/positions-kicad-reference.csv)
- [转换核对](verification/import-verification.json) · [补回过孔记录](verification/restored-footprint-vias.json)

板框约 65 × 30.9 mm，两层板；86 个实际器件，90 个封装（含 4 个独立安装焊盘）、457 段走线、35 个过孔。导入器漏掉的 U2 五个 GND 散热孔已依源工程恢复为板级过孔；后续移动 U2 时必须一并移动这五个孔。

原理图与发布说明的 R33 为 0 Ω，PCB Value / 料号仍对应 150 Ω；实装值未核实。此次有导入一致性检查，但没有完成全面 ERC/DRC 或生产审核。BOM 和坐标是 KiCad 原始参考格式，包含导入图框/安装焊盘记录，不是已审核的 JLC SMT 下单表。

本项目将 HAT 作为外购件。当前 Blender 的 D1-HD1910 与本设计不能互换验证结论；实际购买版本待链接确认。遵循 kissqy 原创硬件的个人非商业许可及相应第三方原许可。

导入 PCB 保留了 23 类元件的原始 3D 路径引用，对应 STEP 未随源工程提供，本目录的 3D 查看不能视为完整。缺失清单见 [missing-3d-models.json](verification/missing-3d-models.json)。符号、封装、原理图和走线均已保存；完整整机 Blender 使用另一个 D1-HD1910 HAT 模型。
