# 本文档的命令前缀为 GlobalVars
--------------------
### globalRaw (静态 Map <String, Object> 变量)
#### 应该是存储了所有全局变量
--------------------
### 下文 XXX 为以下类型: [Int, String, Double, Boolean, Object]
### putXXX(name, obj) 返回 XXX
#### 将 XXX 类型的一个变量添加到全局变量，并返回.
* #### name *String*: 名字
* #### obj *XXX*: 值
### getType(name) 返回 String
#### 返回对应名字全局变量的类型.
* #### name *String*: 名字
### getXXX(name) 返回 XXX
#### 返回对应名字全局变量的值.
* #### name *String*: 名字
### remove(key) 返回 void
#### 移除一个全局变量.
* #### key *String*: 名字
### getRaw() 返回 Map <String, Object>
#### 返回 globalRaw.
