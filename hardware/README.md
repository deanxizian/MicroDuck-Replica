# 硬件

| 板卡 | 本项目获取方式 | 文件 |
| --- | --- | --- |
| Banana NP-F550 0.5-PPTC 取电板 | 自行制板、焊接 | [KiCad、Gerber、BOM 与接线](banana-npf550-pptc/) |
| HAT | 外购；具体商品版本待补 | [D1-HD1910 参考设计](hat/d1-hd1910-reference/)；[kissqy AMP2.0 参考设计](hat/kissqy-amp2-reference/) |
| IMU AMP2.0 | 外购，保留设计参考 | [KiCad 与 Gerber 参考](imu/kissqy-amp2-reference/) |
| HUB V2 | 外购；具体商品版本待补 | [装配与来源说明](hub/) |
| Radxa ZERO 3W | 外购主控 | [主控说明](zero3w/) |

完整 Blender 当前使用 **D1-HD1910 HAT**。kissqy AMP2.0 是另一个硬件版本，不能仅凭同为 HAT 就视为布局、连接器高度和固定关系完全相同。等外购链接确定后，应核对实物版本再完成板卡装配确认。

`jlc/` 是自制 Banana 的制造资料；`jlc-reference/` 是外购板卡的设计参考输出。后者保留未完成的审核项，不作为直接批量生产批准。没有向采购清单添加商品链接。

## KiCad 版本

- Banana / D1-HD1910：原项目使用 KiCad 10.0.7。
- kissqy HAT / IMU AMP2.0：由 KiCad **10.99 开发版 20261031（113c71d59d）** 导入嘉立创专业版工程，需使用兼容该格式的 KiCad。不可假定 KiCad 10.0.7 能打开。
- 项目封装、符号和已有 3D 模型已随相应目录保存，使用项目相对路径。外购 HUB 没有完整可制造 KiCad 设计，本仓库不创建假定电路替代它。
