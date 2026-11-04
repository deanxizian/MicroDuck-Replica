# MicroDuck HAT D1-HD1910 · 参考设计

当前完整 Blender 中的 HAT。基于 Pollen Robotics D1 设计，修改扬声器、左右麦克风和 TTL 舵机共 5 个连接器及局部短走线，并整理丝印。保留原 D1 电路拓扑。板上版本文字为 D1-HD1910。

- [KiCad 工程](kicad/elec_RPI_Robot_HAT.kicad_pro)
- [JLC Gerber](jlc-reference/Gerber.zip)
- [BOM](jlc-reference/MicroDuck-HAT-D1-HD1910-BOM.csv) · [CPL](jlc-reference/MicroDuck-HAT-D1-HD1910-CPL.csv) · [待确认项目](jlc-reference/items-to-confirm.csv)
- [DRC 记录](verification/drc.json)

本项目计划外购 HAT；此目录供设计参考，不代表所购 kissqy AMP2.0 成品就是该设计。

J1 / J2 / J9 为 CJT A1251WV-2P（1.25 mm）；J13 / J14 为 A2007WV-3P（2 mm）。扬声器为差分输出，两根线不是信号加地；左右麦克风分别接各自偏置输入。舵机接口按板上位号与原理图核对 GND、电源、DATA。

制造审核未完成：J4 孔与铜间距仍有 DRC 项，C8/C9 的选料信息、C19 的型号/供应编码、测试点和连接器的贴装方式需要继续确认；CPL 旋转和平台匹配也未形成最终生产验收。原工程的 Y1 缺少 3D 模型。不能因成功导出 Gerber 就认为所有这些问题已解决。

源：pollen-robotics/elec_RPI_Robot_HAT，提交 6de86283297e4c49a9da8312cd3395ab83c437e3；Apache-2.0。局部修改详见 [NOTICE](../../../NOTICE.md)。
