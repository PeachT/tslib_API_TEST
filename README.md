# 记录一个tslib 调用API 做个单点测试的demo
  - 测试demo参考 https://www.amobbs.com/thread-5754433-1-1.html
  - 宿主机是 win11 Linux WSL2  
    - Linux DESKTOP-RK66TKO 5.10.102.1-microsoft-standard-WSL2 #1 SMP Wed Mar 2 00:30:59 UTC 2022 x86_64 GNU/Linux
  - 交叉编译的是 树莓派3B 
    - Linux rpi 5.15.32-v8+ #1538 SMP PREEMPT Thu Mar 31 19:40:39 BST 2022 aarch64 GNU/Linux
  - 编译命令
    - aarch64-linux-gnu-gcc -o test test.c -L./ -Llib -lts
# 测试结果没有问题