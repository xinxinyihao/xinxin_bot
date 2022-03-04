# xinxin_bot
基于python-wechaty开发，以mysql作为数据库，主要提供游戏原神相关查询功能的微信机器人
# 说明
不是程序员，只是自己有点兴趣在菜鸟教程看过几天基础的python教程（大概只看到函数部分吧）。python-wechaty的文档我也不怎么能看得懂。所有功能的实现，都是根据我现有能想到的方法想当然的来实现的，可能很难看，可能也很蠢。git还没学会，emm。
# 关于
原神萌新一枚，刚玩没多久，又菜又爱玩那种。苦于到处找攻略，查资料，比较费事。虽然米游社很好用，但是也不是时时刻刻都有条件上米游社。索性想着搞个机器人，一劳永逸。QQ现在使用的越来越少了，大家都选择了wx（虽然我觉得wx功能很辣鸡）。搞了个wx机器人提供给群里的小伙伴使用，提供了一些原神游戏相关的查询功能，附带一些小的娱乐功能。
# 已实现功能
- [x] 帮助
### 原神游戏查询功能
- [x] 基本信息 【人物 | 武器 | 圣遗物】
- [x] 基础面板 【人物 | 武器 | 圣遗物】
- [x] 推荐攻略 【人物 | 武器 | 圣遗物】
- [x] 背景故事 【人物 | 武器 | 圣遗物】
- [x] 其他信息 【人物 | 武器 | 圣遗物】
- [x] 突破材料 【人物 | 武器】
- [x] 天赋材料 【人物】
- [x] 命之座&#160; &#160;    【人物】
- [x] 大世界资源位置查询
- [x] 周x素材
- [ ] 今日运势
- [x] 原神便签【树脂 | 派遣 | 洞天宝钱】
- [x] 玩家信息【宝箱 | 成就 | 神瞳 | 尘歌壶 | 深渊 | 探索】
- [x] UP池子信息 【角色池 | 武器池】
- [x] 活动日历 【游戏内活动】
- [x] 原神官方B站订阅 【文字 | 图片】
- [x] 抽卡记录分析 【角色祈愿 | 武器祈愿 | 常驻祈愿】 
- [x] 抽卡祈愿模拟 【角色祈愿 | 武器祈愿 | 常驻祈愿】
### 日常功能
- [x] 疫情信息【省 | 市】
- [x] 微博热搜
- [x]  pixiv搜图
- [x]  爬 【随机表情包】
- [x]  网易云热评
- [x]  复读机
# 更新记录 
### 20220304
* 添加B站动态自由订阅功能。  
之前的B站动态推送是写死的，只推送【原神】，现在增加了自由订阅功能，可以订阅自己喜欢的用户的B站动态啦。发送命令就可以对订阅进行增、删、查。
### 2022-01-28 
* 添加抽卡祈愿模拟功能
### 2022-01-27 
* 添加抽卡记录分析功能 
# 具体命令及效果（未完成）
[传送门](https://xinx.top/archives/xinxin_bot.html)  

# 一、原神游戏相关功能
## 1、命令：help | 菜单 | 帮助
输入此命令，机器人将回复功能菜单。  
![命令-帮助](https://user-images.githubusercontent.com/41506567/150275927-082eb8a7-6346-447c-af64-9208e0130bc6.png)

## 2、命令：基本信息[人物名 | 武器名 | 圣遗物名]
输入此命令，机器人将回复相关信息图片。（此信息来源于：https://wiki.biligame.com/）  
如：基本信息雷电将军  
如：基本信息薙草之稻光  
如：基本信息绝缘之旗印  
（此处应有，我是雷电将军的狗.jpg）  

![命令-基本信息](https://user-images.githubusercontent.com/41506567/150276002-8ad64f9a-ecf1-451f-8f65-f4a6291f637f.png)
![基本信息人物](https://user-images.githubusercontent.com/41506567/150276012-1e0f2178-ac5d-4305-b397-c2de297a566e.png)
![基本信息武器](https://user-images.githubusercontent.com/41506567/150276019-57fc5ede-3f57-463a-8a93-65f80f583232.png)
![基本信息圣遗物](https://user-images.githubusercontent.com/41506567/150276025-6bb7faab-3a5d-4282-830b-02368182a131.png)

## 3、命令：基础面板[人物名 | 武器名]
输入此命令，机器人将回复相关信息图片。（此信息来源于：https://wiki.biligame.com/）  
如：基本信息雷电将军  
如：基本信息薙草之稻光  
如：基本信息绝缘之旗印  
![命令-基础面板](https://user-images.githubusercontent.com/41506567/150276170-4a195ae0-8847-4ef1-9dba-d511849f2b11.png)
![基础面板人物](https://user-images.githubusercontent.com/41506567/150276183-c3f28447-98e5-44d8-8bdd-06c803533c9e.png)
![基础面板武器](https://user-images.githubusercontent.com/41506567/150276188-1982a3b5-16c3-4d4d-8877-4bbf96f02e32.png)

## 4、其他  
推荐攻略、故事、基础面板、突破材料、其他信息、命之座、天赋材料等查询命令，使用方法和（2）、（3）一样，可参考上面。命令可查询的项目在括号内有注明。  
注：此中所有wiki信息来自于https://wiki.biligame.com/  
## 5、顺便提一句  
如果有哪位攻略大佬的【一图流攻略】可以转载的话。请告诉我一声，我想白嫖一波大佬的攻略，使用【推荐攻略雷电将军2】这种命令，来提供更加友好的图片式攻略。  
## 6、资源 | 查询 | cx[资源名称]  
输入才命令，机器人将回复标记了资源点的大地图截图。可点开图片查看大图（数据来源于米游社wiki）  
如：资源绯樱绣球  
![命令-大世界资源查询](https://user-images.githubusercontent.com/41506567/150276362-bd31ef61-e5e9-447e-bef4-8754e0c4f64b.png)

## 7、周[x]素材
输入此命令，机器人将回复周x可刷取的武器、天赋素材图片  
（数据来源于可莉特调https://genshin.pub/daily）  
如：周六素材  
![命令-周 x素材](https://user-images.githubusercontent.com/41506567/150276404-f4d5a5b5-e808-402e-9d1a-f692c08c4b35.png)

## 8、命令：今日运势
## 9、命令：mrrw | 我的每日  
输入此命令，机器人将回复原神便签文字版。  
注：此功能需要提供账号cookies，emm。  
![命令-mrrw](https://user-images.githubusercontent.com/41506567/150276425-b0973b5d-365b-46c0-9026-05cfd8426e12.png)

## 10、命令：玩家信息[uid]  
输入此命令，机器人将回复玩家卡牌信息的截图。  
如：玩家信息xxx  
![命令-玩家信息xxx](https://user-images.githubusercontent.com/41506567/150276504-1ad2f6af-a81f-4fb5-96bb-59e9cbb41276.png)
![玩家信息](https://user-images.githubusercontent.com/41506567/150276519-28385b02-8a62-4bf4-8e6b-2e9a73aca90d.png)  
注：由于米游社限制了查询其他玩家所有卡牌，只能查看前八个，自娱自乐了，emm。
## 11、命令：深渊信息[uid]  
输入此命令，机器人将回复玩家深渊战斗的相关信息。  
为了防止世界被破坏，为了保护世界和平，emmm，防止pvp，此功能暂未公开。  
## 12、命令：本期up | up池  
输入此命令，机器人将回复正在up的角色池子、武器池子。  
![命令-up池](https://user-images.githubusercontent.com/41506567/150276728-9547a19a-a5c6-49c8-8444-06616dfde14e.png)
![up池](https://user-images.githubusercontent.com/41506567/150276734-84905114-105d-4386-9103-095fb6b8d714.png)

## 13、命令：活动日历 | hdrl  
输入此功能，机器人将回复最近正在进行的游戏相关活动。
![命令-活动日历](https://user-images.githubusercontent.com/41506567/150276753-d2cdbc01-ec84-48b0-bfa4-783c21795088.png)

## 14、命令：更新所有信息  
输入此命令，机器人将后台更新【本期up】,和【活动日历】功能中的信息。正常情况会自动更新。
![命令-更新所有信息](https://user-images.githubusercontent.com/41506567/150276769-e6a81072-4df5-4b14-b334-d1c81c2aadb8.png) 
## 15、命令：抽卡分析[url] 
输入此命令，参数为抽卡记录页的url，机器人将回复玩家抽卡记录的分析情况。 
![image](https://user-images.githubusercontent.com/41506567/151303626-b34033ae-252e-4dfe-88fc-6ecef71a40a2.png)
## 16、命令：[角色 | 武器 | 常驻]十连
输入此命令，可进行角色池、武器池、常驻池的模拟抽卡，机器人加回复抽卡结果图片。数据库将记录所有成员的所有抽卡记录，可进行相关分析。 
注：此功能来自于[Genshin_Impact_bot](https://github.com/GardenHamster/GenshinPray) 模拟抽卡功能。感谢大佬。
![image](https://user-images.githubusercontent.com/41506567/151505634-0c61c627-6436-47aa-9c0f-fd1d48d16b48.png)
![image](https://user-images.githubusercontent.com/41506567/151505686-ea50a2aa-dcb3-487c-a3bc-154b2da79b71.png)

# 二、日常生活功能
## 1、命令：疫情[省份名 | 市名]
输入此命令，加省市名参数，可以查询相关省市的疫情情况，数据来源于网络，真实性个人自行判断，不代表本人立场。  
![命令-疫情](https://user-images.githubusercontent.com/41506567/150276780-1ebae8d6-9d85-4559-a733-ccba5e485381.png)

## 2、命令：热搜 | 微博 | 微博热搜
输入此命令，机器人将回复最近时段的微博热搜前15。
![命令-微博热搜](https://user-images.githubusercontent.com/41506567/150276918-81443070-0274-4478-9aca-cf1e42be2bca.png)


## 3、命令：看图[xx]
输入此命令，加上想看的图片相关参数，机器人将回复一张图片。
![命令-看图xx](https://user-images.githubusercontent.com/41506567/150276843-3d9f23d6-b37e-46ba-a0e1-873d46bf3c10.png)
![看图](https://user-images.githubusercontent.com/41506567/150276854-4299b0a5-2117-40fe-80a2-5eeda29ed313.png)

注：图库为浏览图片时，随手收藏的，仅代表个人xp不喜勿喷。没有18x图片，但是个别图片还是有点……。pid已提供，（pid是什么），图片版权归原作者及相关网站所有，如有侵权请联系删除。
## 4：爬
当机器人检测到语句中含有“爬”时，将会回复一张表情包。
![命令-爬](https://user-images.githubusercontent.com/41506567/150276875-5e92967b-f92f-4f1c-8f09-24d34f513952.png)

## 5、命令：到点了 | 网易云| 网抑云 | 难过
输入此命令后，机器人将随机返回一句网易云歌曲热评  
如：到点了  
![命令-网易云热评](https://user-images.githubusercontent.com/41506567/150276904-fd09a588-4011-4201-b064-bcf50f390c68.png)

# 三、被动技能
## 1、自动推送原神B站官方账号的动态
此命令无输入，当原神B站官方账号发送动态时，机器人将自动推送动态到微信聊天，推送内容包括文字，图片，不包括视频，视频将推送视频链接。让你不错过任何一条官方消息。  

![命令-B站动态推送](https://user-images.githubusercontent.com/41506567/150276938-9e639d97-2131-4e52-bdb6-eeffdc0b4fb2.png)  

注：因为微信不像QQ一样，支持一条消息包含图文，所以当动态中包含很多张图片时，可能会像窜稀一样，发送n多条，不太友好。（所以wx垃圾，qqyyds）
## 2、5%的概率复读
此命令无输入，人类的本质是【复读机】，有百分之五的概率复读消息。
![image](https://user-images.githubusercontent.com/41506567/150279289-1b2ae690-06a2-4174-b5d7-3ac6b901ec57.png)

# 感谢
[python-wechaty](https://github.com/wechaty/python-wechaty)   微信机器人框架  
[Genshin_Impact_bot](https://github.com/H-K-Y/Genshin_Impact_bot)   原神大世界资源查询的实现  
[Genshin_Impact_bot](https://github.com/GardenHamster/GenshinPray)   模拟抽卡功能  
查询到的原神信息大多来自于bilibili原神wiki，和米游社原神wiki，可莉特调
