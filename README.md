# L4D2_Pugins_Player_GameTime
玩家Steam个人资料/成就中的游戏时间获取
# 本插件依赖ErikMinekus的ripext扩展库，详见 [ErikMinekus/sm-ripext](https://github.com/ErikMinekus/sm-ripext)

### 插件原理及说明:
1、VALVEKEY 需要前往 [Valve开发者中心申请](http://steamcommunity.com/dev)<br> 
2、如果玩家个人资料设置为隐藏，则无法获取资料<br> 
3、原理是通过ripext库发起get请求，来获取玩家数据，URL说明见[Valve WebApi](https://developer.valvesoftware.com/wiki/Steam_Web_API)<br> 
4、玩家时间有两个，一个是个人资料中的游戏时间，只要进入了游戏就已经开始计算了，另外一个是成就中的游戏时间，该时间只计算在房间内的时间，单位为秒
