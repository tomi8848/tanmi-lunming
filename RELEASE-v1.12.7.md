# 坛醚论命 v1.12.7 · Windows 与 Android

本版将起卦区的第二种方式改为梅花易数。电脑和手机均可离线排卦；AI 解读为可选功能，需要自行配置服务。

## 下载与安装

- [Windows x64 便携 EXE](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.7/tanmi-lunming-1.12.7-windows-x64.exe)：下载后双击运行，无需另装 Python 或 Node.js。
- [Android APK](https://github.com/tomi8848/tanmi-lunming/releases/download/v1.12.7/tanmi-lunming-1.12.7-android.apk)：支持 Android 8.0 及以上。已有旧版请直接覆盖安装，不要先卸载；本版沿用原包名和发布签名。

## 本版改进

- 梅花易数在点击起卦时读取设备当前瞬时与系统时区，换算当地农历年月日时。按年支、农历月日和时支取数定上卦、下卦及唯一动爻；子初 23:00 按次日农历日取数。
- 梅花结果使用独立版式，显示取数过程、本卦、互卦、变卦、体用五行，以及相应卦辞、《象》曰和动爻爻辞。图片、文本导出和 AI 提示词也使用梅花专用口径，不混入六爻纳甲的六亲、世应或旬空。
- 随机铜钱及手动录爻仍为六爻纳甲；旧“系统时间种子模拟铜钱”历史记录可按原结果回看。历史、手动保存及其他模块保持原有数据目录和结构。

梅花年月日时取例参照 [GitHub 上的《梅花易数》起卦方法整理](https://github.com/mhynbnb/meihua/blob/master/%E8%B5%B7%E5%8D%A6%E6%96%B9%E6%B3%95.md)；本软件只参考传统规则，计算和版面自行实现。

已通过 71 项规则与功能测试、电脑版与手机端界面及梅花图片预览；最终 Windows EXE 独立启动回归通过。Android APK 已验证签名，并在 Android 11 隔离模拟器完成 v1.12.6 覆盖升级、启动、梅花与其他模块操作；最终包重新覆盖安装后正常启动。

## SHA-256

```text
9B18DDFA69A649B84AD6C2D8FF35AFBA325AEC753D9FA9AEF98604AAEE0FE240  tanmi-lunming-1.12.7-windows-x64.exe
29D407FCFE7581B8D8D566ED4C39E926EB745FA5392967E36F5E061E2E8005AB  tanmi-lunming-1.12.7-android.apk
```

此仓库提供公开说明与下载包；个人命例、API 密钥、完整源码备份和安卓签名密钥不上传。排盘及 AI 解读仅供传统文化学习与参考。

图片出处：软件附带的起卦说明图片来自南怀瑾《易经杂说》（维护者提供出处，版本及页码待补充）。相关权利归相应权利人所有，出处标注不等同于公开再分发授权。
