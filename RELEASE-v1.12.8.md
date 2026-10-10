# 坛醚论命 v1.12.8 · Windows 与 Android

本版在双端紫微斗数排盘中增加“格局”页，按当前天盘、地盘或人盘识别已核验的本命结构。每项会列出实际星曜与宫位、简要传统象义和需要合看的条件；可点回命盘定位宫位，也可直接导出格局结果 PNG。

## 下载与安装

- [Windows x64 便携 EXE](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.8/tanmi-lunming-1.12.8-windows-x64.exe)：下载后双击运行，无需另外安装 Python 或 Node.js。
- [Android APK](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.8/tanmi-lunming-1.12.8-android.apk)：支持 Android 8.0 及以上；已有旧版请直接覆盖安装，不要先卸载。本版沿用原包名与发布签名。

本版收录 13 种可逐宫核对的规则，其中“辅弼拱主”与严格口径的“君臣庆会”分开判断；没有命中时会明确说明收录范围有限。简要倾向是传统文化中的可能解释，不是确定的人生预测。规则与资料来源见[紫微格局说明](licenses/ZIWEI-PATTERNS.md)及 [iztro 格局资料](https://docs.iztro.com/learn/pattern)。紫微 AI 提示词同步附上已核验的本命格局依据，并要求区分本命与运限。六爻、梅花易数、八字、历史和手动保存方式沿用上版。

## 验证

74 项规则与功能测试全部通过；Windows 便携 EXE 直接启动并完成格局、导出图片与原有模块回归。Android 正式签名 APK 在隔离 Android 11 模拟器中从 v1.12.7 覆盖升级、启动，并在真实 WebView 验证格局空态、匹配、竖屏、图片导出和宫位定位；新旧 APK 的签名证书指纹一致。

## SHA-256

```text
8B0AACE0D570ADC720FBD2C8568BDBD1704B0950F39A850311885D4E3B3A7F05  tanmi-lunming-1.12.8-windows-x64.exe
80D3A6BE7EF6012A3B55B0A678B985A5D65FF7A1300E0C1EEB47053ACFC9314E  tanmi-lunming-1.12.8-android.apk
```

此仓库提供公开说明与下载包；个人命例、API 密钥、完整源码备份和安卓签名密钥不上传。排盘及 AI 解读仅供传统文化学习与参考。

图片出处：软件附带的起卦说明图片来自南怀瑾《易经杂说》（维护者提供出处，版本及页码待补充）。相关权利归相应权利人所有，出处标注不等同于公开再分发授权。
