# 苏丹内核映像说明书 精品内核

> 请仔细阅读说明书并在 Google 指导下使用

**【内核名称】**

    通用名称：苏丹内核映像
    英语名称：Sultan Kernel Image
    汉语拼音：سلطان Neihe Yingxiang

**【成分】**

https://github.com/kerneltoast/android_kernel_google_zuma

https://sukisu.org/

**【性状】**

本品为压缩包套压缩包文件，SHA256 检测见下载时旁边注计。

**【适应机型】**

Pixel 8 无印版及 Pro 版

**【不良反应】**

常见：发热。偶见：死机。罕见：黑砖。

**【注意事项】**

本内核安全补丁级别来自 KernelSU workflow 的最新设定。

请在安装此项目的内核前，启动一次官方或者 5ec1cff 的 KernelSU，进入系统后打开 KernelSU 管理器，进入设置，**关闭全局 umount**。这是为了防止 susfs 对 umount 的应用处理导致系统应用出现问题。可能出现的现象包括但不限于：

- 启动后黑屏（SystemUI 无法加载）
- Wi-Fi 无法访问
- 基带有关通讯无法访问

**【核代动力学】**

对 Pixel 8 进行了通用内核映像的核代动力学研究。可以启动。

> **软件相互作用**
>
> mountify: 与 susfs 存在冲突

**【储藏】** 任意条件。

**【包装】** 压缩包文件。
