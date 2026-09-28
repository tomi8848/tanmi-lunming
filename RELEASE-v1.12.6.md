# 坛醚论命 v1.12.6 · Windows 与 Android

本版更新电脑版与安卓版。排盘核心在本机离线运行；可选 AI 解读需要自行配置 API 服务。

## 下载与安装

- [Windows x64 便携 EXE](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.6/tanmi-lunming-1.12.6-windows-x64.exe)：下载后双击运行，无需另装 Python 或 Node.js。
- [Android APK](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.6/tanmi-lunming-1.12.6-android.apk)：支持 Android 8.0 及以上。已有旧版请直接覆盖安装，不要先卸载；本版沿用原包名和发布签名。

## 本版改进

- 电脑版加入“海外／当地时间”出生地区入口。按出生地当地公历和钟表时刻输入，选择海外城市后自动填写 IANA 时区及经度，并按历史时区、夏令时和经度校准真太阳时；支持回拨重复时刻选择。
- 电脑版的国内与海外出生城市都支持关键词模糊搜索，可输入省份、城市中文名或海外城市英文名。
- 电脑版与安卓版的八字、紫微排盘页均增加“新增命例”，清空当前录入资料和盘面，以便直接录入下一份资料；已有历史和手动保存不删除，手机端原“修改排盘资料”按钮保留。

已通过 66 项核心测试、电脑版与手机端界面回归。打包后的 Windows EXE 通过独立启动及完整界面回归；Android APK 通过签名验证，并在 Android 11 隔离模拟器验证从 v1.12.5 覆盖升级、启动及两模块新增命例。

## SHA-256

```text
42BC444000776DDCBB0AC92CDA4D4B752B7CDACFEB48110C8552A5EA9078BDCE  tanmi-lunming-1.12.6-windows-x64.exe
EDF10BA0F428391C48AFE62703E385A8943C71273757F1B8BC5A3A8CD6342817  tanmi-lunming-1.12.6-android.apk
```

此仓库提供公开说明与下载包；个人命例、API 密钥、完整源码备份和安卓签名密钥不上传。排盘及 AI 解读仅供传统文化学习与参考。

图片出处：软件附带的起卦说明图片来自南怀瑾《易经杂说》（维护者提供出处，版本及页码待补充）。相关权利归相应权利人所有，出处标注不等同于公开再分发授权。
