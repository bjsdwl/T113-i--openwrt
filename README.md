# T113-i--openwrt
这是一个基于 ImmortalWrt（OpenWrt 的最强分支，对全志 T113 和国产板卡支持最好）的 GitHub Action Workflow。
这个配置自动启用了以下关键功能，无需你手动提供 .config 文件：
目标平台：Allwinner T113-i (Sunxi Cortex-A7)。
硬件解码驱动：启用了 cedrus 驱动（全志[1] SOC 的开源视频解码驱动）。
WiFi 驱动：同时启用了 MQ-R 常见的 RTL8189FS 和 RTL8723DS 驱动。
常用工具：预装了 ffmpeg (用于测试视频)、v4l-utils (用于检测视频设备) [1]和 luci。
