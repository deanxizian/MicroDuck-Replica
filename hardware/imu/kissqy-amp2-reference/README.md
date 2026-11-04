# kissqy IMU AMP2.0 · KiCad 与制造参考

源为 kissqy 2026-10-15 嘉立创专业版 IMU 工程，源 SHA256：`824bad07b60bbb1680f759c45b1e2bb918757f7f59747d254cb6d0d0c2ec4a25`。

- [KiCad 工程](kicad/IMU-AMP2.0.kicad_pro) / [原理图](kicad/IMU-AMP2.0.kicad_sch) / [PCB](kicad/IMU-AMP2.0.kicad_pcb)
- [Gerber 参考 ZIP](jlc-reference/Gerber-reference.zip) · [原理图 PDF](jlc-reference/schematic.pdf)
- [BOM 参考](jlc-reference/BOM-reference.csv) · [坐标参考](jlc-reference/positions-kicad-reference.csv)
- [导入核对与模型来源](verification/)

使用 KiCad 10.99 开发版 20261031 导入，25 个器件、4 个安装孔封装、196 段走线、16 个过孔、2 个铜区。25 个器件的位置及 93 个焊盘网络已有源工程一致性记录。PCB 包含 11 类 3D 模型；只将这些模型的文件路径改成项目相对路径，没有修改电路。新增 `.kicad_pro` 使用同版 KiCad 默认项目容器，不代表已设定生产验收规则。

本项目采用外购 IMU；固件、烧录/校准状态及具体版本待商家信息确认。本目录没有完成完整 ERC/DRC/生产审核；原理图导入的图框符号 `?` 和坐标中的无位号安装焊盘仍可见，因此 CSV 仅作设计参考。

装配模型孔距 16.51 × 19.812 mm，以四个 2 mm 隔离垫参考件避开板背焊针；实际垫片和螺钉长度待实装。遵循 kissqy 原创硬件个人非商业许可，元件库和第三方模型保留原许可。
