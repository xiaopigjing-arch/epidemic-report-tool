# 疫情监测报告助手 v1.0

面向疾控机构及相关专业人员的本地离线疫情监测报告编制工具。

## 发布状态

v1.0已发布。请到 [最新版下载页](https://github.com/xiaopigjing-arch/epidemic-report-tool/releases/latest) 下载 **EpiReport_win_v1.0.zip**（约26.8 MB），完整解压后双击“疫情监测报告助手_v1.0.exe”。保留整个文件夹，无需自行安装Python。

Mac Apple芯片版也已提供：下载 **EpiReport_Mac_arm64_v1.0.zip**（约26.5 MB），完整解压后打开“疫情监测报告助手 v1.0.app”。仅支持M系列芯片，不提供Intel版，无需另装Python。

银河麒麟 V10 ARM64 版已提供：[下载完整包 EpiReport_Kylin_arm64_v1.0_full.tar.xz](https://github.com/xiaopigjing-arch/epidemic-report-tool/releases/download/v1.0/EpiReport_Kylin_arm64_v1.0_full.tar.xz)（约24.3 MB）。完整解压后双击“**双击安装并启动**”，以后使用桌面“疫情监测报告助手”图标打开。系统若提示不可信启动器，按正常提示允许启动。无需旧版、单独补丁、另装Python或输入终端命令。

麒麟版适用本次测试的银河麒麟V10、飞腾/AArch64、glibc2.23、UKUI/X11环境，不适用于x86、龙芯或Windows ARM。首次安装、启动、读取报表、统计及生成Word均可脱网完成；数据保留本机，不上传业务数据、不收集遥测、不自动更新、不联网下载依赖。

Windows/Mac软件内的最新版下载入口指向：

[下载最新发布版本](https://github.com/xiaopigjing-arch/epidemic-report-tool/releases/latest)

GitHub附件使用英文文件名，软件名称仍为“疫情监测报告助手 v1.0”。请勿将GitHub的Source code压缩包当作可运行软件。

## 主要功能

- 支持周、月、旬、季、半年、年六类监测报告。
- 按表内结构识别九份本地Excel报表，支持文件夹读取和逐项选择。
- 提供地区、周期、文件重复等校验，以及病种选择和人工补充。
- 生成可编辑Word报告、图表及独立核对文件。
- 提供离线防控建议、趋势首段预览与人工编辑。

## 使用说明

Windows包面向Windows10/11 Intel/AMD 64位，不适用于32位或Windows ARM64；Mac包仅面向Apple芯片。安装启动方法以各平台包内《使用说明.txt》为准。

已完成Windows Server2022云端源码六类合成报告及编译EXE启动检查。Windows10/11干净机脱网启动、高DPI、Word/WPS分页及编译EXE完整报告流程仍待实机验收，详情见Release说明。

Mac版已完成源码六类合成报告检查；最终ZIP实际解压后的编译应用通过启动、九份合成报表读取、周报及独立核对文件导出。干净Mac首次脱网运行、其他macOS版本和Word/WPS分页仍待验收。Mac包使用ad-hoc签名，未购买Developer ID或经Apple公证；首次启动请按系统正常提示确认来源，保留系统安全保护。

麒麟完整候选已获使用者运行确认；正式编译业务模块已在Linux ARM64环境通过六类合成九表报告、主界面、Noto字体及正常退出检查。公开下载文件与本地成品逐字节一致，SHA256及文件清单核验通过。正式编译包的麒麟实机完整流程、其他系统版本和Word/WPS分页仍待验收。

报表处理和报告生成均在本机完成，不自动检查更新。Windows/Mac版在使用者主动点击下载入口时调用浏览器访问GitHub；麒麟版使用离线更新包。报告使用前须由专业人员核对数据、图表和建议。

## 问题反馈

可通过本仓库Issues反馈系统版本、软件版本、操作步骤及错误提示。请勿上传真实病例数据、患者信息或其他非公开业务资料。

本仓库用于软件介绍、版本下载及反馈；不提供开发源码。版权信息见软件包内《使用说明.txt》。
