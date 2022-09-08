# empty-for-image-test

初始化命令：
se new base -T vmlc -o 1 -w t98123

## open in smartide

### 本机模式

se start -d

### 本地远程主机模式

se start -r https://github.com/SmartIDE/empty-for-image-test.git -b base-vmlc -o 1 -d

### Server在线版 远程主机模式和k8s模式：

https://dev.smartide.cn/#/layout/smartide/workspace?gitRepoUrl=https://github.com/SmartIDE/empty-for-image-test.git&branch=base-vmlc&configFilePath=.ide/.ide.yaml

选择主机资源时：本地命令行输入se connect，转发至本地，本地打开转发后的服务地址
选择k8s资源时直接网页端打开相关服务地址

### 本地 k8s模式：

se start --k8s smartide-workload-test -r https://github.com/SmartIDE/empty-for-image-test.git -b base-vmlc -f .ide/.ide.yaml -d

