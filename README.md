QiukuiLive
----------
把秋葵直播开源了，有段时间没玩这个了，看了几个坛子里的直播软件
很简单，但是经常有遇到崩溃的地方。
有段时间，直播查的严，我就把秋葵关掉了。


这段时间我想着**开源**了算了，我自己留着有没有什么用，造福坛友吧。
有能力的修改下，就可以拿它赚钱。
软件已经放在GitHub上了
地址：[https://github.com/Xiaofufufu/QiukuiLive][1]

**已经实现的功能：**

 1. 解析json格式的直播源数据，只支持http://api.hclyz.com:81/mf/json.txt这个一个直播源；
 2. 收藏喜欢的主播，通过抓取主播直播链接实现，云端保存主播直播链接；
 3. 展示其他人收藏的主播，查看别人最近收藏的主播；
 4. 直播页直接翻看其他主播直播，不退出直播页面（这个免费直播都没做）；
 5. 添加会员功能；
 6. 卡盟兑换会员功能；
 7. 金币购买收藏上限，默认是三个；
 8. 磁力搜索，没有做直接播放的功能，我没有好的服务器做；
 9. 增加了两个支付宝红包的地方；
 10. 设置页可以设置是否打开直播页切换控件。

**别的功能自己尝试吧，代码一些重要的地方有注释。**

App使用Apicloud制作的，需要使用mcm模块存放注册和收藏信息。
在apicloud注册账号以后，添加一个新应用，接着把modelClass.json导入mcm数据库中。
使用官方的编辑器，同步下你的应用代码，然后把我的覆盖下，注意要先把config.xml

    <widget id="A000000000000"  version="0.0.1">

修改成你自己的appid，要不然直接替换会出问题。

**再添加如下这几个模块。**
![model][4]

**app首页，其他页面到文件夹里去看吧**
![app首页][2]

*其他的请大家随缘修改吧。*

**臭不要脸的再放一下自己的打赏码。**
![打赏码][3]

**需要帮助修改的，就联系这个邮箱吧，hfsc1314#gmail.com(#号替换成@)**



  [1]: https://github.com/Xiaofufufu/QiukuiLive
  [2]: https://github.com/Xiaofufufu/QiukuiLive/blob/master/screenshots/index.png
  [3]: https://github.com/Xiaofufufu/QiukuiLive/blob/master/screenshots/qrcode.png
  [4]: https://github.com/Xiaofufufu/QiukuiLive/blob/master/screenshots/model.png
