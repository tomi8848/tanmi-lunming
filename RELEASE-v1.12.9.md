# 坛醚论命 v1.12.9 · Windows 与 Android

紫微斗数格局页改为完整调用 [Renhuai123/ziwei-doushu 原项目的 41 个判定函数](https://github.com/Renhuai123/ziwei-doushu/blob/main/lib/ziwei/patterns.ts)。天盘、地盘、人盘分别按当前本命盘计算，逐项展示原项目的成立条件、等级、加分与破格警示；可回命盘定位，亦可导出图片。41 是函数数量，不是每张盘的命中数量；大限和流年不参与这套本命格局规则。

传统倾向文字参考[《紫微斗数全书》公版转录](https://zh.wikisource.org/wiki/紫微斗數全書/卷一)及 [iztro 格局说明](https://docs.iztro.com/learn/pattern)重新编写，避免将传统象义当作确定预测，也不把原项目概括性 `source` 字段误写为已校勘的古籍篇名。规则、差异与资料说明见[紫微格局规则](licenses/ZIWEI-PATTERNS.md)。其余起卦、八字、历史和手动保存功能沿用上版。

## 下载与安装

- [Windows x64 便携 EXE](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.9/tanmi-lunming-1.12.9-windows-x64.exe)：Windows 10/11，下载后双击运行，无需另装 Python 或 Node.js。未做商业代码签名，若有未知发布者提示，请核对校验值。
- [Android APK](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.9/tanmi-lunming-1.12.9-android.apk)：Android 8.0+；旧版请直接覆盖安装，保留本机记录。本版沿用原包名及发布签名。

## 验证

73 项自动测试全部通过，包含三盘 90 份盘例与原项目格局判定的逐项比对。Windows 成品启动、格局、图片导出及主要模块回归通过；Android 已签名 APK 在隔离 Android 11 模拟器中从 v1.12.8 覆盖升级，真实 WebView 验证格局、竖屏、导出及宫位定位。

## SHA-256

```text
5809E357EEF6B80C3CE6390BC85D7822D9C7F0BC8087E6E8A22645B3251CC6D3  tanmi-lunming-1.12.9-windows-x64.exe
24C60455C065068A073B745ECD160F80EDB0D51E450EAC2592B23E38D39F2B01  tanmi-lunming-1.12.9-android.apk
```

此仓库提供公开说明与安装包；个人命例、API 密钥、完整源码备份和安卓签名密钥不上传。排盘及 AI 解读仅供传统文化学习与参考。

图片出处：软件附带的起卦说明图片来自南怀瑾《易经杂说》（维护者提供出处，版本及页码待补充）。相关权利归相应权利人所有，出处标注不等同于公开再分发授权。
