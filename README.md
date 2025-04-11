# oneplus8t-nethunter-pro
适用于oneplus8t(kebab)的kali** nethuntr pro,目前手机内置硬件支持 屏幕、wifi、bluetooth驱动。
刷写此boot和rootfs 的分区固件得是Oxygenos11/HydrogenOS11
刷写步骤:刷写此系统前请备份好手机数据，刷写任何固件都有手机成砖的风险，刷写前请慎重
1.fastboot erase dtbo
2.fastboot flash boot boot_kebab.img
3.fastboot flash userdata oneplus8t-nethunter-pro-rootfs.img
4.fastboot reboot
5.也可以安卓/nethunter pro双系统 这需要自己去实验
