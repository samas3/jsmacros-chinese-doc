# 本文档的命令前缀为 Hud（不常用）
# 下文的 ~ 请全部忽略
--------------------
### overlays (静态 不可变 Set (https://docs.oracle.com/javase/8/docs/api/index.html?java/util/Set.html) <IDraw2D (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/sharedinterfaces/IDraw2D.html) <Draw2D (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/Draw2D.html) >> 变量)
#### 千万别动.——原作者
### renders (静态 不可变 Set (https://docs.oracle.com/javase/8/docs/api/index.html?java/util/Set.html) <Draw3D (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/Draw3D.html) > 变量)
#### 千万别动.——原作者
--------------------
### createScreen(title, dirtBG) 返回 ScriptScreen (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/ScriptScreen.html) (IScreen (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/sharedinterfaces/IScreen.html) 接口的实例)
#### 创建一个屏幕.
* #### title *String*: 标题
* #### dirtBG *Boolean*: 是否有泥土背景
### openScreen(s) 返回 void
#### 打开一个屏幕.
* #### s *IScreen*: 要打开的屏幕
### getOpenScreen() 返回 IScreen
#### 获取当前打开的屏幕.
### isContainer() 返回 Boolean
#### 检查当前打开的屏幕是否为容器.
### createDraw2D() 返回 IDraw2D <Draw2D~>
#### 返回一个新的 Draw2D.
### registerDraw2D(overlay) 返回 void
#### 使一个 Draw2D 被渲染.
* #### overlay *IDraw2D <Draw2D~>*: 一个 Draw2D 实例
### unregisterDraw2D(overlay) 返回 void
#### 使一个 Draw2D 停止渲染.
* #### overlay *IDraw2D <Draw2D~>*: 同 registerDraw2D
