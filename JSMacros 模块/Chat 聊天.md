# 本文档的命令前缀为 Chat
--------------------
### log(message, [await]) 返回 空
### 在聊天中打印某些东西.
* #### message *对象*: 要打印的对象（可以包含格式字符§）
* #### await *布尔值, 可选*: 是否等待直到信息真的被发送到聊天（？）
### say(message, [await]) 返回 空
### 直接发送聊天.
* #### message *字符串*: 同log（不能包含格式字符）
* #### await *布尔值, 可选*: 同log
### open(str, [await]) 返回 空
### 打开聊天栏, 并自动输入某些内容.
* #### str *字符串*: 要输入的内容（可以包含格式字符，但不要发出去）
* #### await *布尔值, 可选*: 同log
### title(title, subtitle, fadeIn, remain, fadeOut) 返回 空
### 发送标题.
* #### title *对象*: 主标题，填null为空
* #### subtitle *对象*: 副标题，填null为空
* #### fadeIn *整数*: 淡入时间（tick）
* #### remain *整数*: 展示时间（tick）
* #### fadeOut *整数*: 淡出时间（tick）
### actionbar(text, tinted) 返回 空
### 发送（那个在快捷栏上面的东西）.
* #### text *对象": 内容
* #### tinted *布尔值*: 是否变色（唱片机常用）
### toast(title, desc) 返回 空
### 显示一个提示（类似完成进度）
* #### title *对象*: 标题
* #### desc *对象*: 说明
类似![image](https://user-images.githubusercontent.com/79700349/150628345-55ae98c8-94eb-42ef-803f-4651d79d9517.png)
### createTextHelperFromString(content) 返回 TextHelper (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/helpers/TextHelper.html)
### 从字符串产生一个 TextHelper.
* #### content *字符串*: 字符串
（不常用）
### getLogger([name]) 返回 Logger (https://logging.apache.org/log4j/2.x/log4j-api/apidocs/index.html?org/apache/logging/log4j/Logger.html)
### 返回一个 Logger（记录日志）.
* #### name *字符串，可选*: 名字
（不常用）
### createTextHelperFromJSON(json) 返回 TextHelper
### 从 JSON 字符串产生一个 TextHelper.
* #### json *字符串*: JSON 字符串
（不常用）
### createTextBuilder() 返回 TextBuilder (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/TextBuilder.html)
### 返回一个 TextBuilder（带格式的东西）.
（不常用）
### createCommandBuilder(name) 返回 CommandBuilder (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/CommandBuilder.html)
### 返回一个 CommandBuilder（创建命令）.
* #### name *字符串*: 名字
（不常用）
### getHistory() 返回 ChatHistoryManager (https://jsmacros.wagyourtail.xyz/1.6.4/xyz/wagyourtail/jsmacros/client/api/classes/ChatHistoryManager.html)
### 返回一个 ChatHistoryManager（管理聊天历史记录）.
（不常用）
