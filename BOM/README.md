# BOM

整机采购与打印清单，暂不含商品链接和价格。建议采购量含备件；待确认项以实物核对为准。

## 整机采购

| 分类 | 名称 | 型号或规格 | 装机数量 | 建议采购数量 | 单位 | 获取方式 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 舵机 | 飞特舵机 | HD1910 / HD-1910-C001 | 15 | 15 | 个 | 外购 | 按本机配置处理主动/从动舵盘；额外备机可选 |
| 主控 | Radxa ZERO 3W | 内存/eMMC/排针配置待最终采购确认 | 1 | 1 | 块 | 外购 | Blender 已装入；摄像头 FPC 需与实际主控接口匹配 |
| 板卡 | HAT | 成品版本待链接；当前装配参考 D1-HD1910 | 1 | 1 | 块 | 外购 | 同时附 D1 与 kissqy AMP2.0 设计，不能视为同一版本 |
| 板卡 | IMU | kissqy AMP2.0 | 1 | 1 | 块 | 外购 | 固件/校准与成品版本待核对；附 KiCad 及制造参考 |
| 板卡 | HUB | V2 成品，具体链接待补 | 1 | 1 | 块 | 外购 | 包含连接器/电容；实际封装高度待核对 |
| 电源 | Banana 裸 PCB | NP-F550 0.5-PPTC / 1.6 mm / 两层 | 1 | 1 | 块 | 自行打样 | 采购数量按平台最小起订量；不需重复购买成品 HAT/IMU 的全部器件 |
| 电源 | 取电针 | U6068，针体及焊接尾规格需核对 | 2 | 4 | 根 | 外购 | 先插 PCB，再焊针；含 2 根备件 |
| 电源 | PPTC 自恢复保险丝 | 计划伯特 BSMD2920-700-12V | 1 | 2 | 颗 | 外购 | 设计参考 Littelfuse 2920L700/12MR；替代规格书待确认 |
| 电源 | 电池 | NP-F550 | 1 | 2 | 块 | 外购 | 1 装机 + 1 可选备用；品牌容量与外形实物核对 |
| 电源 | 电池充电器 | 匹配 NP-F550 | 1 | 1 | 个 | 外购 | 已有兼容充电器可不买 |
| 外设 | 摄像头 | 亚博 IMX219 160° | 1 | 1 | 个 | 外购 | 暂定孔距 21×13.5 mm、柱高 6 mm；等待完整厂家尺寸 |
| 外设 | 摄像头排线 | 匹配所购 IMX219 与 ZERO 3W | 1 | 2 | 根 | 外购 | 针数、触点面、引脚定义待核对；1 根备用 |
| 外设 | ToF 测距 | VL53L5CX V2，8×8，孔距 20 mm | 1 | 1 | 块 | 外购 | 选 kissqy 指定款，非 TOF400C |
| 外设 | 麦克风 | EM4015 类驻极体、橡胶外径 4.6±0.2 mm | 2 | 4 | 个 | 外购 | 左右各 1；2 个备件；Ø4.4 压入座 / Ø1.5 拾音孔 |
| 外设 | 腔体扬声器 | 3525 / 4Ω 3W / 约35×25×6.8 mm | 1 | 1 | 个 | 外购 | 出声朝下；核对 2P 1.25 接头线序 |
| 耗材 | 加厚双面胶 | 约 2.5 mm 厚 | 1 | 1 | 份 | 自备或外购 | 贴扬声器背部；粘贴面积以模型平面和实物为准 |
| 金属结构 | 11 号左腿固定片 | kissqy 同尺寸配套金属件 | 1 | 1 | 件 | 外购 | 不打印 |
| 金属结构 | 12 号右腿固定片 | kissqy 同尺寸配套金属件 | 1 | 1 | 件 | 外购 | 不打印 |
| 金属结构 | 30 号躯干台 | kissqy 同尺寸配套金属件 | 1 | 1 | 件 | 外购 | 不打印 |
| 轴承 | 6700 | 内10×外15×厚3 mm | 3 | 4 | 个 | 外购 | 当前模型 3 个；1 个备用 |
| 轴承 | ET2216 | 内16×外22×厚4 mm | 11 | 12 | 个 | 外购 | 当前模型 11 个；1 个备用 |
| 线材 | 舵机总线线 | AMP2.0 3P 双头 / 8 cm | 估算7 | 10 | 根 | 外购 | 数量含主干链路估算；购买列含余量，未实测走线 |
| 线材 | 舵机总线线 | AMP2.0 3P 双头 / 10 cm | 估算8 | 10 | 根 | 外购 | 核对端子针序；不要仅凭线色接电源 |
| 线材 | 舵机总线线 | AMP2.0 3P 双头 / 20 cm | 估算2 | 4 | 根 | 外购 | 购买列含 2 根备用 |
| 线材 | 音频线束 | 匹配 HAT 的 2P 1.25 mm | 3 | 3 | 组 | 外购或随模块 | 左右麦与扬声器各 1；模块已带线时不重复买 |
| 线材 | ToF I2C 线束 | 匹配实际模块与 HAT | 1 | 2 | 组 | 外购 | 1 根备用；连接器及 GND/VCC/SDA/SCL 针序需核对 |
| 线材 | 电源引线 | Banana 至 HUB 的红黑一对 | 1 | 1 | 组 | 自备 | 长度、线径及焊点固定按实际峰值电流与走线确认 |
| 紧固 | 螺钉套件 | M2×4/5/6/8/12、M2.5、M2.6×8 等 | 待实装 | 1 | 套 | 外购 | 机牙/自攻和逐项数量尚未定稿，不虚填精确根数；先核对外购件是否自带 |
| 紧固 | IMU 隔离垫 / 垫柱 | 2 mm 高参考 | 4 | 6 | 个 | 外购 | 实际螺钉长度与背面焊针需核对 |
| 耗材 | 绝缘与固定 | 热缩管、扎带、绝缘片 | 1 | 1 | 份 | 自备 | 按实际布线裁切 |
| 存储 | microSD 系统卡 | 32 GB 或以上参考 | 按主控 | 1 | 张 | 外购 | 无 eMMC 方案需要；已有卡可不买 |
| 工具 | USB 舵机调试器 | 适配飞特 TTL 总线，如 URT2 | 调试用 | 1 | 个 | 选购 | 已有调试器可不买；软件部署后补 |
| 工具 | 读卡器 | 匹配 microSD | 调试用 | 1 | 个 | 选购 | 已有可不买 |
| 打印 | 9000HE 白色打印件 | 03/04/09/10/25/28/29/32 | 8 | 8 | 件 | 3D打印 | 各编号 1 件 |
| 打印 | JLCBlack 黑色打印件 | 23/27/31 | 3 | 3 | 件 | 3D打印 | 各编号 1 件 |
| 打印 | Grey 灰色打印件 | 05–08/13–22/24/26 | 16 | 16 | 件 | 3D打印 | 各编号 1 件 |
| 打印 | TPU 95A 黑色脚底 | 01/02 | 2 | 2 | 件 | 3D打印 | 各编号 1 件 |

## 3D 打印件

共 29 件，各 1 个。11、12、30 号使用外购金属件。下单使用 STL；STEP 供 CAD 参考，平台转换告警尚未解决。

| 编号 | 零件 | 数量 | 材料 | 颜色 | 文件 |
| --- | --- | ---: | --- | --- | --- |
| 01 | 左脚底 | 1 | TPU 95A | 黑色 | [STL](../structure/print/STL/04_TPU95A_黑色_2件/01_左脚底_TPU95A_黑色.stl) · [STEP](../structure/print/STEP/04_TPU95A_黑色_2件/01_左脚底_TPU95A_黑色.step) |
| 02 | 右脚底 | 1 | TPU 95A | 黑色 | [STL](../structure/print/STL/04_TPU95A_黑色_2件/02_右脚底_TPU95A_黑色.stl) · [STEP](../structure/print/STEP/04_TPU95A_黑色_2件/02_右脚底_TPU95A_黑色.step) |
| 03 | 左脚掌 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/03_左脚掌_9000HE_白色.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/03_左脚掌_9000HE_白色.step) |
| 04 | 右脚掌 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/04_右脚掌_9000HE_白色.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/04_右脚掌_9000HE_白色.step) |
| 05 | 左脚 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/05_左脚_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/05_左脚_Grey_灰色.step) |
| 06 | 右脚 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/06_右脚_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/06_右脚_Grey_灰色.step) |
| 07 | 左膝支撑 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/07_左膝支撑_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/07_左膝支撑_Grey_灰色.step) |
| 08 | 右膝支撑 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/08_右膝支撑_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/08_右膝支撑_Grey_灰色.step) |
| 09 | 左胯外盖 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/09_左胯外盖_深装柱_9000HE_白色_v3.1.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/09_左胯外盖_深装柱_9000HE_白色_v3.1.step) |
| 10 | 右胯外壳 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/10_右胯外壳_深装柱_9000HE_白色.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/10_右胯外壳_深装柱_9000HE_白色.step) |
| 13 | 左胯侧摆 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/13_左胯侧摆_连续实体_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/13_左胯侧摆_连续实体_Grey_灰色.step) |
| 14 | 右胯侧摆 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/14_右胯侧摆_连续实体_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/14_右胯侧摆_连续实体_Grey_灰色.step) |
| 15 | 左胯旋转 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/15_左胯旋转_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/15_左胯旋转_Grey_灰色.step) |
| 16 | 右胯旋转 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/16_右胯旋转_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/16_右胯旋转_Grey_灰色.step) |
| 17 | 左胯固定片 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/17_左胯固定片_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/17_左胯固定片_Grey_灰色.step) |
| 18 | 右胯固定片 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/18_右胯固定片_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/18_右胯固定片_Grey_灰色.step) |
| 19 | 颈部固定左 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/19_颈部固定左_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/19_颈部固定左_Grey_灰色.step) |
| 20 | 颈部固定右 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/20_颈部固定右_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/20_颈部固定右_Grey_灰色.step) |
| 21 | 头部旋转 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/21_头部旋转_叉架29.2_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/21_头部旋转_叉架29.2_Grey_灰色.step) |
| 22 | 头部侧倾 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/22_头部侧倾_Grey_灰色_v3.1.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/22_头部侧倾_Grey_灰色_v3.1.step) |
| 23 | 脸板 | 1 | JLC Black | 黑色 | [STL](../structure/print/STL/02_JLCBlack_黑色_3件/23_脸板_IMX219孔距21x13.5_Zero柱下移1.5_JLCBlack_黑色.stl) · [STEP](../structure/print/STEP/02_JLCBlack_黑色_3件/23_脸板_IMX219孔距21x13.5_Zero柱下移1.5_JLCBlack_黑色.step) |
| 24 | 嘴巴 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/24_嘴巴_Grey_灰色.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/24_嘴巴_Grey_灰色.step) |
| 25 | 头盖 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/25_头盖_双麦_短扬声器粘贴面_9000HE_白色_v3.1.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/25_头盖_双麦_短扬声器粘贴面_9000HE_白色_v3.1.step) |
| 26 | 头部集成板 | 1 | Grey | 灰色 | [STL](../structure/print/STL/03_Grey_灰色_16件/26_头部集成板_张嘴让位端缘修整_Grey_灰色_v3.1.stl) · [STEP](../structure/print/STEP/03_Grey_灰色_16件/26_头部集成板_张嘴让位端缘修整_Grey_灰色_v3.1.step) |
| 27 | 眼睛 | 1 | JLC Black | 黑色 | [STL](../structure/print/STL/02_JLCBlack_黑色_3件/27_眼睛_JLCBlack_黑色.stl) · [STEP](../structure/print/STEP/02_JLCBlack_黑色_3件/27_眼睛_JLCBlack_黑色.step) |
| 28 | 左壳 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/28_左壳_连续孔口_9000HE_白色_v3.1.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/28_左壳_连续孔口_9000HE_白色_v3.1.step) |
| 29 | 右壳 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/29_右壳_连续孔口_9000HE_白色_v3.1.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/29_右壳_连续孔口_9000HE_白色_v3.1.step) |
| 31 | 电池仓 | 1 | JLC Black | 黑色 | [STL](../structure/print/STL/02_JLCBlack_黑色_3件/31_电池仓_右侧出线缺口_JLCBlack_黑色_v3.1.stl) · [STEP](../structure/print/STEP/02_JLCBlack_黑色_3件/31_电池仓_右侧出线缺口_JLCBlack_黑色_v3.1.step) |
| 32 | 头部集成盖 | 1 | 9000HE | 白色 | [STL](../structure/print/STL/01_9000HE_白色_8件/32_头部集成盖_兼容hat插口_9000HE_白色.stl) · [STEP](../structure/print/STEP/01_9000HE_白色_8件/32_头部集成盖_兼容hat插口_9000HE_白色.step) |

## 线缆说明

舵机之间共估算 12 根：8 cm × 3、10 cm × 7、20 cm × 2。连同 HAT／HUB／IMU 共估算 17 根：8 cm × 7、10 cm × 8、20 cm × 2；保守采购量已列在上表。数量尚未经过实物走线验证，不含外设线和电源线。
