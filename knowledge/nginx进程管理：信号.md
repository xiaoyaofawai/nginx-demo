![avatar](image/3.jpg)
* CHLD Worker进程退出时会给Master发送CHLD信号
* TERM,INT 立即停止nginx
* QUIT 优雅停止nginx
* HUP 重载配置
* USR1 重新开启日志文件
* USR2 nginx升级时使用，用来使旧版子进程优雅停止，开启新版子进程
* WINCH nginx升级时使用，用来使旧版主进程退出