# 外设

下表对应当前选型，规格书保留原文件。两份 Blender 已包含这些部件的装配参考模型。

| 部件 | 资料 | 安装说明 |
| --- | --- | --- |
| 铁头 TNP-F550-GN 电池 | [官方说明书](Battery/Tilta-NP-F550-manual.pdf) · [模型依据](Battery/README.md) | 绿色，3500mAh；70.6×38.6×20.5 mm（不含保护盖）；卡口与取电针配合待实测 |
| 双麦克风 EM4015 | [规格书](Microphone/EM4015-specification.doc) · [胶套尺寸图](Microphone/EM4015-rubber-dimensions.png) | 左右各 1；Ø4.4 压入座、Ø1.5 拾音孔 |
| 3525 扬声器 | [4Ω 3W 规格书](Speaker/XHXDZ-3525-4ohm-3W.pdf) | 出声朝下，背部用约 2.5 mm 双面胶固定 |
| 亚博 IMX219 160° | [产品参数](Camera/Yahboom-IMX219-parameters.jpg) · [接口图](Camera/Yahboom-camera-interface.jpg) · [微雪参考 DWG](Camera/Waveshare-RPi-Camera-E-F-G-H.dwg) | 暂按孔距 21×13.5 mm、柱高 6 mm；亚博完整机械图及配套排线待确认 |
| VL53L5CX V2 | [ST 规格书 Rev 5 存档](ToF/VL53L5CX-DS13754-Rev5.pdf) · [官网新版](https://www.st.com/resource/en/datasheet/vl53l5cx.pdf) | 模块孔距按 20 mm；芯片规格书不包含成品模块机械图 |
| 飞特 HD1910 | [厂家规格书](Servo/FEETECH-HD-1910-C001-20260907.pdf) | 配套舵盘与背轴按当前装配方案处理 |

双麦同步采样、相机完整视场、排线兼容性和实物固定仍需验证。板卡见 [硬件](../Hardware/README.md)，数量见 [BOM](../BOM/README.md)。

文件来源与哈希见 [sources.json](sources.json)。厂家资料归原作者所有，不改变其原有许可。
