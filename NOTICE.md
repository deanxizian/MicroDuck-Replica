# 来源、归属与修改说明

MicroDuck-Replica 是个人非商业复刻整理版，不代表 Pollen Robotics、kissqy、元器件厂商或打印平台的官方发布。

| 内容 | 来源 / 固定版本 | 本版处理 |
| --- | --- | --- |
| MicroDuck 结构及飞特适配 | [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck)，[kissqy/Microduck-kissqy](https://github.com/kissqy/Microduck-kissqy/tree/f6497beb2f4511117f789b885f521c580e5ba490)，后者提交 f6497beb2f4511117f789b885f521c580e5ba490 | 依据实际打印包、网页修正版及社区改件继续修整；详见 CHANGES |
| Banana 取电板 | [jyg9/microduck-community-kit](https://github.com/jyg9/microduck-community-kit/tree/14b6e768a3e97a05e437cf2a17efa3dfd926f648/hardware/banana_pcb)，提交 14b6e768a3e97a05e437cf2a17efa3dfd926f648 | 加 PPTC、出线焊盘与配合；CERN-OHL-P v2 |
| D1 HAT | [pollen-robotics/elec_RPI_Robot_HAT](https://github.com/pollen-robotics/elec_RPI_Robot_HAT/tree/6de86283297e4c49a9da8312cd3395ab83c437e3) | 5 连接器和局部走线适配 HD1910，整理丝印；Apache-2.0 |
| kissqy HAT / IMU AMP2.0 | kissqy 2026-10-15 嘉立创专业版工程，来自上述固定提交 | 转为 KiCad，补回 HAT U2 五个导入缺失过孔、增加 IMU 3D 模型与可移植路径；保留个人非商业及第三方许可 |
| 标准符号、封装与模型 | KiCad Library Team / 社区；[KiCad 库许可](https://www.kicad.org/libraries/license/) | 仅携带项目需要的库文件；CC BY-SA 4.0 与官方设计例外按原范围适用 |
| 连接器、IMU 元件模型 | 嘉立创 EDA / EasyEDA 元件库，相应厂商 | 供设计/装配参考，模型归原作者；IMU 模型来源与哈希见硬件 verification |
| 摄像头、主控与外设 | Radxa ZERO 3W 参考模型、Waveshare D160 镜头参考、厂商尺寸资料及自行建立包络 | 亚博与微雪同尺寸是当前假设；没有赋予第三方原模型新的许可 |

kissqy 原始打印包自身汇集官方和多位社区作者的修改，不将这些原作全部归于本仓库维护者。原许可索引与硬件许可范围在 LICENSES 中原文保留；其中相对路径指原上游仓库结构。本仓库的路径映射以根 LICENSE 为准。

Pollen Robotics 的 microduck_rl 对其特定 STL 路径适用 CC BY-NC-SA 4.0（见 [LICENSE-MODELS](https://github.com/pollen-robotics/microduck_rl/blob/develop/LICENSE-MODELS.md)）；这些原作及派生部分沿用该许可。该说明不自动覆盖所有社区独立模型。

本版几何和安装修改详见 [Docs/CHANGES.md](Docs/CHANGES.md)，验证范围见 [Docs/VALIDATION.md](Docs/VALIDATION.md)。新增整理不移除原作者署名、第三方权利和既有许可条件。商用或组织用途应按具体内容联系对应权利人。

外设规格书及尺寸图按原文归档，来源见 [Peripherals/sources.json](Peripherals/sources.json)，权利归相应厂商和原作者。
