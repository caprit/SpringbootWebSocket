#SpringbootWebSocket

SpringBoot整合Websocket，实现广播式和给特定用户发送消息，不需要登录即可发送消息。

# 示例

## 主页

> 访问http://localhost:82进入主页,主要提供两个不同的用户ricky和rickyt2,以及发送公共消息功能。

 ![](/src/main/resources/static/image/index.png) 
 
## ricky用户 
> 进入之后，先点击连接connect，输入sendName即可发送消息 

 ![](/src/main/resources/static/image/ricky.png)
 
  
## rickyt2用户 
> 进入之后，先点击连接connect，输入sendName即可发送消息 

 ![](/src/main/resources/static/image/rickyt2.png)
 
## 发送公共消息
 
 点击主页的公共消息按钮，即可发送公共消息，如果想重新发送，刷新公共消息页面即可。