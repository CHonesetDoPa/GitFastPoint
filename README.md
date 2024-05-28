# GitFastPoint
GitFastPoint 是一个给像cc一样懒的人类用的怪东西

# 能做什么
1.  给一些不习惯和懒惰的人类提供的方便git功能入口
2.  提供一个叫gfpp的快速push工具，在可能猝死（划掉）的情况下推送代码

# 用法
下载gfp脚本
从[Github Release](https://github.com/CHonesetDoPa/GitFastPoint/releases/download/0.1/gfp)或直接使用git克隆
> git clone https://github.com/CHonesetDoPa/GitFastPoint.git

赋予执行权限
> chmod +x gfp

运行gfp  
> ./gfp  

将gfp添加到/usr/bin内以便快速使用
> 在弹出的对话框中选中命令 "5" "Add GitFastPoint into /usr/bin (need sudo)" 并回车

# 命令

|命令|用途|
|---|---|
|./gfp|运行本目录下的gfp（未写入到/usr/bin时）|
|gfp|运行gfp（写入/usr/bin后）|
|gfpp|快速在当前目录下依次执行 “git add .” 、 “git commit -m "update something"” 和 “git push” |

# gfp界面功能

1. 克隆Repo  
2. 拉取到本地  
3. 自定义commit message 推送到远端  
4. 默认commit message 推送到远端  
5. 添加gfp和gfpp到/usr/bin（使得此脚本可在任何目录下可用）  
6. 移除/usr/bin中的gfp和gfpp（自删除脚本）  