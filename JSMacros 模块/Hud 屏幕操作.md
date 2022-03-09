# 本文档的命令前缀为 Hud（不常用）
# 下文的 ~ 请全部忽略
--------------------
### overlays (静态 不可变 Set <IDraw2D <Draw2D>> 变量)
#### 千万别动.——原作者
### renders (静态 不可变 Set <Draw3D> 变量)
#### 千万别动.——原作者
--------------------
### createScreen(title, dirtBG) 返回 ScriptScreen (IScreen 接口的实例)
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
### listDraw2Ds() 返回 List <IDraw2D <Draw2D>>
#### 返回所有当前显示的 Draw2D.
### createDraw3D() 返回 Draw3D
#### 返回一个新的 Draw3D.
### registerDraw3D(draw) 返回 void
#### 使一个 Draw3D 被渲染.
* #### draw *Draw3D*: 一个 Draw3D 实例
### unregisterDraw3D(draw) 返回 void
#### 使一个 Draw3D 停止渲染.
* #### draw *Draw3D*: 同 registerDraw3D
### listDraw3Ds() 返回 List <Draw3D>
#### 返回所有当前显示的 Draw3D.
### clearDraw3Ds() 返回 void
#### 清除当前的所有 Draw3D.
### getMouseX() 返回 Double
#### 返回当前鼠标 X 坐标.
### getMouseY() 返回 Double
#### 返回当前鼠标 Y 坐标.
