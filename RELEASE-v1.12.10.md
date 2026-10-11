# 坛醚论命 v1.12.10 · Windows 与 Android

紫微斗数 AI 现在发送**当前所选天／地／人盘式的本命盘 JSON**，并附农历年份、虚岁、流年命宫、小限与大限的推算规则。模型可以在一个大限内比较前后年份，不再只拿所选那一年的流年盘作依据。请求中没有完整逐年流曜、流年四化或大限四化；提示词要求 AI 明示这些资料未核对，不能补造。

紫微排盘页新增“流年／小限”解释窗口，与较小的“中州派选盘”说明入口并列；天地人盘仍是主选择。原先较长的主页面说明已精简。小限一岁起宫和男女顺逆的口径参照[《紫微斗数全书》卷二“安小限诀”](https://zh.wikisource.org/wiki/紫微斗數全書/卷二)及 [iztro 安星诀](https://docs.iztro.com/learn/setup)，本版也按排盘引擎逐年核对。更多限制见[天地人盘与流年规则](licenses/ZIWEI-PLATES-RULES.md)。其他模块和记录功能沿用上版。

## 下载与安装

- [Windows x64 便携 EXE](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.10/tanmi-lunming-1.12.10-windows-x64.exe)：Windows 10/11，下载后双击运行，无需另装 Python 或 Node.js。未做商业代码签名，出现未知发布者提示时请核对校验值。
- [Android APK](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.10/tanmi-lunming-1.12.10-android.apk)：Android 8.0+，旧版请直接覆盖安装以保留本机记录。本版沿用原包名和发布签名。

## 验证

74 项自动测试通过；本命盘资料范围、四组生年支与男女方向的小限宫位均与排盘引擎逐年对照。正式 Windows EXE 的主要排盘、保存和导出界面测试通过；正式 Android APK 在隔离 Android 11 模拟器从 v1.12.9 覆盖升级，并以真实 WebView 检查紫微排盘、两个说明窗口、格局与图片导出。AI 回答质量仍取决于用户选择的服务商和模型，未对所有真实 API 账户或手机品牌逐一验证。

## SHA-256

```text
1C2D498C458DDD1D609FFDB891CF832D2F9E5470CC112E558ECB5397A4742634  tanmi-lunming-1.12.10-windows-x64.exe
682719850661B1E014B1662095F5010BEFA88B22215D89877566F77FC8AB90A2  tanmi-lunming-1.12.10-android.apk
```

此公开仓库提供说明与安装包。个人命例、API 密钥、完整源码备份和安卓签名密钥不上传。排盘及 AI 解读仅供传统文化学习与参考。

图片出处：软件附带的起卦说明图片来自南怀瑾《易经杂说》（维护者提供出处，版本及页码待补充）。相关权利归相应权利人所有，出处标注不等同于公开再分发授权。
