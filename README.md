# SunRun4Shortcut

Sunny Run for Apple Shortcut App

iOS/iPad OS阳光长跑快捷指令

## 说明

**本脚本仅供学习交流使用，请勿过分依赖。开发者对使用或不使用本脚本造成的问题不负任何责任，不对脚本执行效果做出任何担保，原则上不提供任何形式的技术支持。**

## Feature / 特点

Simple, Fast & Automatic

简单、快速、自动化

## How-to / 用法

Import the shortcuts from the links below, then Open *Shortcut* App, enter your `IMEI Code` and run it !

在下方链接中导入快捷指令，随后打开“快捷指令”App，把IMEI Code输入到脚本中即可完成。

See Comments in script for more information.

更多解释可以参见脚本内的注释。

## Required/需求

- IMEI Code

  - By **network data catching** / **抓包**

- Shortcut App / 快捷指令App

  iPhone: iPhone 6s or upper with iOS 13+

  iPad:	iPad Air 2 or upper with iPadOS 13+

  Mac: 	macOS 12.0 +

## IMEI Code

You can get `IMEI Code`  by **NETWORK DATA CATCHING**

抓包获取IMEI Code

Download [Stream](https://apps.apple.com/cn/app/stream/id1312141691) from App Store (iOS)

Tutorial/教程 : [抓包实践](https://www.jianshu.com/p/a34585836b3a)

Capture the package when you login. The package is like:

抓登陆包即可，一般长这样：

```json
{
  "Success": true,
  "Data": {
    "Token": "0d3bf9578beb4*******a9384272a488",
    "UserId": 619***,
    "IMEICode": "03df3a1af37848******7c70a085d55d" # <-IMEICode
  }
}
```

## Download Link / 下载链接

- SunRun / 阳光长跑

  - [链接](https://www.icloud.com/shortcuts/258dd9c0548f4681b843402efefeb618)
  - 标准版本

- SunRun(direct) / 阳光长跑(直达)

  - [链接](https://www.icloud.com/shortcuts/df0c27ae9fb64bdf9e22c96a6a753975)
  - 不会弹出确认框

- SunRun(Clipboard [direct]) / 阳光长跑(剪切板[直达])

  - [剪切板-链接](https://www.icloud.com/shortcuts/c3a31019095348c3824c127720d77e07)

    [剪切板直达-链接](https://www.icloud.com/shortcuts/09d39c1462a24c2d80455819c1d9ab79)

  - 直接从剪切板中读取IMEI Code，如果剪切板为空则要求输入

  - 不会弹出确认框(直达)

- SunRun(in batches) / 阳光长跑(批量)  **Advanced / 高级**

  - [链接](https://www.icloud.com/shortcuts/fe16b6791586444dbc3abb8cf230fbd4)
  - 运行批量需要先导入*阳光长跑(函数)*
  - 批量操作，见脚本内的注释

- SunRun(func) / 阳光长跑(函数)           **Advanced / 高级**

  - [链接](https://www.icloud.com/shortcuts/83050a851be744458b2be12c8b41f315)
  - **不能单独运行！**
  - 输入：单个IMEI Code
  - 输出：无
  - 功能：对输入的IMEI Code运行*阳光长跑(直达)*

## Acknowledgement / 鸣谢

`Run.py` Source Code Reference from [SunnyRunningPy](https://github.com/S-Ex1t/SunnyRunningPy) @ [S-Ex1t](https://github.com/S-Ex1t)

来自 [SunnyRunningPy](https://github.com/S-Ex1t/SunnyRunningPy) @ [S-Ex1t](https://github.com/S-Ex1t) 的`Run.py`源码参考

