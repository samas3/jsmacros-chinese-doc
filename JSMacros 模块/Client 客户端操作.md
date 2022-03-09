# 本文档的命令前缀为 Client
--------------------
### tickSynchronizer (静态 TickSync 变量)
### 千万别动. ——原作者
--------------------
### getMinecraft() 返回 MinecraftClient
#### 返回当前 MC 客户端（可以瞎搞了！好耶！）.
### runOnMainThread(runnable) 返回 void
#### 使你的任务在主进程上运行（？).
* #### runnable *MethodWrapper <Object, Object, Object, ?>*: 要运行的任务
（不常用）
### getGameOptions() 返回 OptionsHelper
#### 返回当前客户端的设置.
（不常用）
### mcVersion() 返回 String
#### 返回当前运行的 MC 版本（版本文件夹的名字）.
### getFPS() 返回 String
#### 返回 F3 菜单中的 FPS 那一行.
### connect(ip, [port]) 返回 void
#### 连接到指定服务器（为什么我用的时候游戏退出了？所以别用）.
* #### ip *String*: IP
* #### port *Integer, 可选*: 端口
### disconnect([callback]) 返回 void
#### 退出服务器.
* #### callback *MethodWrapper <Boolean, Object, Object, ?>, 可选*: 退出时执行的方法（不常用）
### shutdown() 返回 void
#### 关闭客户端.
### waitTick([i]) 返回 void
#### 等待 1（i 未给出）或 i tick（不要在主进程上使用）.
* #### i *Integer, 可选*: 等待的 tick 数
