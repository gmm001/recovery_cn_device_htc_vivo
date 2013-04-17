recovery_cn_device_htc_vivo
===========================

Chinese recovery, Gmm device

Synchronization to the directory device/htc/vivo, also need to synchronize android_bootable_recovery_cn

Method.

Build/envsetup.sh.

Lunch cm_vivo-userdebug

Make -j32 recoveryimage

Individual ROM station: http://gmm.10ml.net

---------------------------------------------------

中文 恢复系统的device，G11专用配置， By 安智 破晓-Gmmつ

同步到目录device/htc/vivo 即可，同时需要同步android_bootable_recovery_cn

方法：
. build/envsetup.sh

lunch cm_vivo-userdebug

make -j32 recoveryimage


个人ROM站：http://gmm.10ml.net
