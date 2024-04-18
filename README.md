# shell
self-made shell

## 简介
tsh是一个非常迷你的shell程序，可以通过tsh运行其他程序，例如：
```text
tsh> /bin/ls -a
.		..		.git		.gitignore	LICENSE		README.md	shell.xcodeproj	tsh
Handling chlid proess 71421
waitfg [71421], result:-1
```
如果在后台运行，则在尾部添加`&`

## 功能

tsh内置了4个命令
- jobs：  查看所有运行的程序不
- fg %[jobid]：  将某个子进程挪到前台
- bg %[jobid]：  在后台运行某个子进程
- quit：  退出程序