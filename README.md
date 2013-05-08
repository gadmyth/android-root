android-root
============

adb push Superuser.apk /sdcard/Superuser.apk
adb push su /sdcard/su
adb push rageagainstthecage-arm5.bin /data/local/tmp/rageagainstthecage-arm5.bin
adb push install-root.sh /data/local/tmp/install-root.sh
adb shell
cd /data/local/tmp
chmod 0755 rageagainstthecage-arm5.bin
chmod 0755 install-root.sh