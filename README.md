HyperOS GMS Sync Patch (Google 服务同步补丁)
这是一个为 Xiaomi HyperOS (基于 Android 15) 提取的 Google 服务同步适配器补丁。主要用于修复国内版 ROM 在使用 Google 服务时，联系人、日历无法同步以及位置记录缺失的问题。

📂 包含组件 (Included Components)
本模块提取自 Redmi K60 Pro 的EU发布版本，包含以下系统应用 (位于 /system/product/app/)：

GoogleContactsSyncAdapter: 用于同步 Google 通讯录。

GoogleCalendarSyncAdapter: 用于同步 Google 日历。

GoogleLocationHistory: 用于启用 Google 位置记录功能。

✅ 兼容性 (Compatibility)
提取机型: Redmi K60 Pro

测试环境: HyperOS 3.0 (Android 15)

测试结果: 功能正常，同步服务可用。

🛠️ 安装方法 (Installation)
下载本模块的压缩包 (Zip)。

打开 Magisk Manager (或 KernelSU/APatch)。

选择“从本地安装”并选择本模块。

安装完成后，重启手机。

🚀 激活方式 (Activation) [重要/Important]
重启后，如果发现同步未立即生效，请按照以下步骤激活：

前往 Google Play 商店下载 Google 日历 (Google Calendar) App。

打开 Google 日历并登录你的 Google 账号，确保日历内容已加载。

卸载 刚刚下载的 Google 日历 App。

此时系统层面的同步适配器已被激活，进入系统设置 -> 账号与同步 -> Google，检查联系人和日历同步开关是否已开启。

⚠️ 免责声明 (Disclaimer)
本补丁仅供学习交流使用。

请在刷入前备份重要数据，本人不对刷入后可能导致的任何系统问题负责。
