# 硬件

| 板卡 | 获取方式 | 资料 |
| --- | --- | --- |
| Banana NP-F550 | 自行打板、焊接 | [Banana-NP-F550](Banana-NP-F550/) |
| MicroDuck HAT D1 | 外购飞特适配成品 | [HAT-D1-HD1910](HAT-D1-HD1910/) |
| kissqy HAT AMP2.0 | 备用设计资料，本机未采用 | [HAT-AMP2.0](HAT-AMP2.0/) |
| kissqy IMU AMP2.0 | 外购 IMU TO DXL 成品 | [IMU-AMP2.0](IMU-AMP2.0/) |
| kissqy HUB | 外购成品 | [HUB](HUB/) |
| Radxa ZERO 3W | 外购成品 | [Radxa-ZERO-3W](Radxa-ZERO-3W/) |

有设计文件的板卡采用统一目录：

```text
板卡名称/
├── JLC/           嘉立创制造文件、BOM 与贴装坐标
├── KiCad/         工程、符号、封装与模型
├── Verification/  ERC/DRC、导入与模型检查记录
└── README.md      版本、装配与接线说明
```

Banana 的 PTC、取电针和引线需自行焊接。HAT、IMU 的制造文件用于设计参考，尚有审核项；HUB 和 ZERO 3W 未收录制造工程，仅保留说明。`Verification` 无需上传到嘉立创。

Banana、D1 HAT 使用 KiCad 10.0.7；AMP2.0 HAT／IMU 使用 KiCad 10.99 开发版 20261031 导入。完整 Blender 使用 D1-HD1910 HAT，外购成品的连接器和飞特适配配置仍需核对。

采购规格和价格见 [BOM](../BOM/README.md)。
