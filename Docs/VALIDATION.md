# 验证状态 · 2026-11-04

| 项目 | 检查结果 | 待完成 |
| --- | --- | --- |
| 29 件 STL | 单一闭合网格、法线一致，无坏边、非流形、退化面、自交 | 实物公差、强度与寿命测试 |
| 嘉立创 STL 复检 | 09、22、25、26、28、29、31 的网格项通过 | 其他 22 件本轮未重传；25/26 仍为易变形结构 |
| STEP | 29 份 CAD 参考，13/14 解析 BRep，其余分面 BRep | 平台转换仍有告警；不用于当前 JLC 下单 |
| 两份 Blender | 同源几何、位置、父子关系与完整外设装配；保存后重开核对 | 颜色只是显示方案，未校准实物色差 |
| 铁头 TNP-F550-GN | 按官方 70.6×38.6×20.5 mm 外包络更新，两份 Blender 同步 | 曲面和纵槽按照片近似；接口沿用参考尺寸，卡口/接触孔及实物配合待测 |
| 活动嘴部 | 0–35° 采样检查，30° 名义间隙约 0.35 mm | 实物运动与线束测试；网格清理后的整机全关节扫掠 |
| 相机与板卡 | 当前参考尺寸下的安装位置与空间核对；采购 SKU 已列入 BOM | 亚博完整尺寸待客服；外购 D1 HAT／kissqy HUB 的实物改版、连接器和版号待核对；镜头全视场和线缆待验证 |
| Banana | 本地 ERC/DRC 和网络记录；制造文件已导出 | PPTC 替代型号、接触针、公差、温升和保护功能未实测 |
| D1 HAT | KiCad 与 Gerber / BOM / CPL 参考 | 存在 J4 DRC、选料及贴装确认项 |
| kissqy HAT / IMU | 源工程导入一致性检查与制造导出 | 全面生产审核、成品版本核对 |

## 文件追溯

[STL manifest](../Structure/Print/STL/manifest.json) 记录材料、数量与 SHA256；对应 [本地网格检查](../Structure/Verification/stl-mesh-audit.json) 和 [平台复检摘要](../Structure/Verification/jlc-stl-recheck.json)。

[Blender 检查记录](../Structure/Verification/blender-publication.json) 保存装配版本与文件哈希；[SHA256SUMS](../SHA256SUMS) 用于目录完整性校验。
