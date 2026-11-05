# 核对记录

用于追溯检查针对的文件与版本，打印时不需要上传。

| 文件 | 内容 |
| --- | --- |
| [stl-mesh-audit.json](stl-mesh-audit.json) | 29 件 STL 的本地网格检查 |
| [jlc-stl-recheck.json](jlc-stl-recheck.json) | 7 件 STL 的嘉立创复检；25/26 保留易变形提示 |
| [repair-deviation.json](repair-deviation.json) | 网格修复前后的尺寸偏差 |
| [blender-publication.json](blender-publication.json)、[blender-reopen.json](blender-reopen.json) | 初版两份 Blender 的文件与装配核对 |
| [assembly-colors-update.json](assembly-colors-update.json) | 当前板卡与双面胶配色；颜色修改前后几何、位置与父子关系一致 |
| [camera-protection-update.json](camera-protection-update.json) | 当前 23/27 号：相机后移 2 mm、眼圈厚 6 mm，含装配、接地与视场边界 |
| [camera-tof-horizontal-update.json](camera-tof-horizontal-update.json) | 上一版 23 号：相机旋转 90°、ToF 横装等高且焊盘朝下，含间隙与 Blender 核对 |
| [tof-alignment-update.json](tof-alignment-update.json) | 历史版本：ToF 竖装、上移 2 mm |
| [camera-face-update.json](camera-face-update.json) | 相机实测尺寸、23 号修订与局部装配核对；其他薄壁项仍保留 |
| [battery-update.json](battery-update.json) | 铁头电池的尺寸来源、更新范围与局部静态检查 |

这些记录不等于实物验收。STL 文件对应关系见 [manifest](../Print/STL/manifest.json)，完整边界见 [验证状态](../../Docs/VALIDATION.md)。
