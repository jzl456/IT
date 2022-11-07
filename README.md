# linux学习
## 1、root密码重置
### 
1、重启按e进入内核编辑模式
2、在linux16参数后追加‘rd.break’，Ctrl+X运行
3、输入以下命令完成密码重置
mount
o remount,rw /sysroot
chroot
/sysroot
passwd
touch
/.autorelabel
exit
reboot
## 2、cut命令
