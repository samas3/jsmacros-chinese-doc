# 本文档的命令前缀为 FS
--------------------
### list(path) 返回 String[]
#### 返回路径文件夹中的所有文件.
* #### path *String*: 路径（如果是相对路径则起始路径为脚本所在文件夹）
### exists(path) 返回 Boolean
#### 检查路径是否存在.
* #### path *String*: 同list
### isDir(path) 返回 Boolean
#### 检查路径是否为文件夹.
* #### path *String*: 同list
### getName(path) 返回 String
#### 返回文件名（不含目录）.
* #### path *String*: 同list
### makeDir(path) 返回 Boolean
#### 创建文件夹（返回值为是否成功）.
* #### path *String*: 同list
### move(from, to) 返回 void
#### 移动文件.
* #### from *String*: 同list的path
* #### to *String*: 同list的path
### copy(from, to) 返回 void
#### 复制文件.
* #### from *String*: 同move
* #### to *String*: 同move
### unlink(path) 返回 Boolean
#### 删除文件（返回值为是否成功）.
* #### path *String*: 同list
### combine(patha, pathb) 返回 String
#### 合并两个路径.
* #### patha *String*: 同list
* #### pathb *String*: 一个路径
### getDir(path) 返回 String
#### 返回文件的目录名，或文件夹的父文件夹名.
* #### path *String*: 同list
### open(path) 返回 FileHandler (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/core/library/impl/classes/FileHandler.html)
#### 在指定路径打开一个 FileHandler（用于读写文件）.
* #### path *String*: 同list
