# MicroDuck HAT D1-HD1910

本机采用外购 D1 飞特适配成品。此处保留基于 Pollen Robotics D1 的本地设计：调整扬声器、双麦和 TTL 舵机共 5 个连接器及局部走线，整理丝印。完整 Blender 使用该版参考模型。

| 资料 | 文件 |
| --- | --- |
| KiCad | [工程](KiCad/elec_RPI_Robot_HAT.kicad_pro) |
| 嘉立创 | [Gerber](JLC/Gerber.zip) · [BOM](JLC/MicroDuck-HAT-D1-HD1910-BOM.csv) · [CPL](JLC/MicroDuck-HAT-D1-HD1910-CPL.csv) |
| 检查记录 | [DRC](Verification/drc.json) · [制造待确认项](JLC/items-to-confirm.csv) |

J1／J2／J9 为 1.25 mm 音频接口，J13／J14 为 2 mm 舵机接口。扬声器使用差分输出，双麦分别连接独立偏置输入。接线按原理图及实板位号核对。

制造资料尚有 J4 孔铜间距、C8/C9 与 C19 选料、连接器贴装及 CPL 旋转审核项；Y1 缺少 3D 模型。外购成品的连接器和飞特短接配置需与本地设计对照。

源工程：Pollen Robotics `elec_RPI_Robot_HAT`，提交 `6de86283297e4c49a9da8312cd3395ab83c437e3`，Apache-2.0。见 [来源说明](../../NOTICE.md)。
