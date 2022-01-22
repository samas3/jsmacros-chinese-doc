# 本文档的命令前缀为 Chat
--------------------
### log(message, [await]) 返回 void
#### 在聊天中打印某些东西.
* #### message *Object*: 要打印的对象（可以包含格式字符§）
* #### await *Boolean, 可选*: 是否等待直到信息真的被发送到聊天（？）
### say(message, [await]) 返回 void
#### 直接发送聊天.
* #### message *String*: 同log（不能包含格式字符）
* #### await *Boolean, 可选*: 同log
### open(str, [await]) 返回 void
#### 打开聊天栏, 并自动输入某些内容.
* #### str *String*: 要输入的内容（可以包含格式字符，但不要发出去）
* #### await *Boolean, 可选*: 同log
### title(title, subtitle, fadeIn, remain, fadeOut) 返回 void
#### 发送标题.
* #### title *Object*: 主标题，填null为空
* #### subtitle *Object*: 副标题，填null为空
* #### fadeIn *Integer*: 淡入时间（tick）
* #### remain *Integer*: 展示时间（tick）
* #### fadeOut *Integer*: 淡出时间（tick）
### actionbar(text, tinted) 返回 void
#### 发送（那个在快捷栏上面的东西）.
* #### text *Object": 内容
* #### tinted *Boolean*: 是否变色（唱片机常用）
### toast(title, desc) 返回 void
#### 显示一个提示（类似完成进度）
* #### title *Object*: 标题
* #### desc *Object*: 说明
### createTextHelperFromString(content) 返回 TextHelper (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/helpers/TextHelper.html)
#### 从字符串产生一个 TextHelper.
* #### content *String*: 字符串
（不常用）
### getLogger([name]) 返回 Logger (https://logging.apache.org/log4j/2.x/log4j-api/apidocs/index.html?org/apache/logging/log4j/Logger.html)
#### 返回一个 Logger（记录日志）.
* #### name *String, 可选*: 名字
（不常用）
### createTextHelperFromJSON(json) 返回 TextHelper
#### 从 JSON 字符串产生一个 TextHelper.
* #### json *String*: JSON 字符串
（不常用）
### createTextBuilder() 返回 TextBuilder (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/TextBuilder.html)
#### 返回一个 TextBuilder（带格式的东西）.
（不常用）
### createCommandBuilder(name) 返回 CommandBuilder (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/CommandBuilder.html)
#### 返回一个 CommandBuilder（创建命令）.
* #### name *String*: 名字
（不常用）
### getHistory() 返回 ChatHistoryManager (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/ChatHistoryManager.html)
#### 返回一个 ChatHistoryManager（管理聊天历史记录）.
（不常用）
