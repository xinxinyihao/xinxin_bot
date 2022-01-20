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
- [x] 原神便签【树脂 | 派遣】
- [x] 玩家信息【宝箱 | 成就 | 神瞳 | 尘歌壶 | 深渊 | 探索】
- [x] UP池子信息 【角色池 | 武器池】
- [x] 活动日历 【游戏内活动】
- [x] 原神官方B站订阅 【文字 | 图片】
### 日常功能
- [x] 疫情信息【省 | 市】
- [x] 微博热搜
- [x]  pixiv搜图
- [x]  爬 【随机表情包】
- [x]  网易云热评
- [x]  复读机
# 具体命令及效果（未完成）
[传送门](https://xinx.top/archives/xinxin_bot.html)
一、原神游戏相关功能
1、命令：help | 菜单 | 帮助
输入此命令，机器人将回复功能菜单。图片: https://uploader.shimo.im/f/Qtwmkd3hFd737kJE.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY

2、命令：基本信息[人物名 | 武器名 | 圣遗物名]
输入此命令，机器人将回复相关信息图片。（此信息来源于：https://wiki.biligame.com/）
如：基本信息雷电将军
如：基本信息薙草之稻光
如：基本信息绝缘之旗印
（此处应有，我是雷电将军的狗.jpg）
图片: https://uploader.shimo.im/f/HzbvCoHg2ojTUa1k.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/mikUNGut02ayhOKl.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/NBquOq98DVf5HyOA.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/5Yrk8owSjOVd2FBr.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
3、命令：基础面板[人物名 | 武器名]
图片: https://uploader.shimo.im/f/h3HwL8F2lJkJdLHq.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/UUGGkJIfK63PylZ0.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/2GXrVGSVTVnZmslz.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
4、推荐攻略、故事、基础面板、突破材料、其他信息、命之座、天赋材料等查询命令，使用方法和（2）、（3）一样，可参考上面。命令可查询的项目在括号内有注明。
注：此中所有wiki信息来自于https://wiki.biligame.com/
5、顺便提一句，如果有哪位攻略大佬的【一图流攻略】可以转载的话。请告诉我一声，我想白嫖一波大佬的攻略，使用【推荐攻略雷电将军2】这种命令，来提供更加友好的图片式攻略。
6、资源 | 查询 | cx[资源名称]
输入才命令，机器人将回复标记了资源点的大地图截图。可点开图片查看大图（数据来源于米游社wiki）
如：资源绯樱绣球
图片: https://uploader.shimo.im/f/g7Q13DcSQZLDzLFz.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
7、周[x]素材
输入此命令，机器人将回复周x可刷取的武器、天赋素材图片
（数据来源于可莉特调https://genshin.pub/daily）
如：周六素材
图片: https://uploader.shimo.im/f/gvowEJfLjGplNGAs.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
8、命令：今日运势
9、命令：mrrw | 我的每日
输入此命令，机器人将回复原神便签文字版。
注：此功能需要提供账号cookies，emm。
图片: https://uploader.shimo.im/f/Ixj5MuHd8LBxiZF5.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
10、命令：玩家信息[uid]
输入此命令，机器人将回复玩家卡牌信息的截图。
如：玩家信息xxx
图片: https://uploader.shimo.im/f/Lt4jY0ObFXwdGALc.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/336nqXgHyBWmGsbx.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY  
注：由于米游社限制了查询其他玩家所有卡牌，只能查看前八个，自娱自乐了，emm。
11、命令：深渊信息[uid]
输入此命令，机器人将回复玩家深渊战斗的相关信息。
为了防止世界被破坏，为了保护世界和平，emmm，防止pvp，此功能还是不公开了吧。
12、命令：本期up | up池
输入此命令，机器人将回复正在up的角色池子、武器池子。
图片: https://uploader.shimo.im/f/HVhfGNRnO6B7dgvz.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/0iDWCAEivykETxBe.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY

13、命令：活动日历 | hdrl
输入此功能，机器人将回复最近正在进行的游戏相关活动。
图片: https://uploader.shimo.im/f/AwtE9y3kZcFFMEee.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
14、命令：更新所有信息
输入此命令，机器人将后台更新【本期up】,和【活动日历】功能中的信息。正常情况会自动更新。
图片: https://uploader.shimo.im/f/Ld5HoRKci1AXZJtS.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
二、日常生活功能
1、命令：疫情[省份名 | 市名]
输入此命令，加省市名参数，可以查询相关省市的疫情情况，数据来源于网络，真实性个人自行判断，不代表本人立场。
图片: https://uploader.shimo.im/f/w1PT87jKtJ0N2zWq.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
2、命令：热搜 | 微博 | 微博热搜
输入此命令，机器人将回复最近时段的微博热搜前15。
图片: https://uploader.shimo.im/f/9mAa25sgOeum6Lsi.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
3、命令：看图[xx]
输入此命令，加上想看的图片相关参数，机器人将回复一张图片。
如：ss雷电将军
图片: https://uploader.shimo.im/f/geqOWUKsbIt40Bnl.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
图片: https://uploader.shimo.im/f/ShcQ52iYrKdmTFwK.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
注：图库为浏览图片时，随手收藏的，仅代表个人xp不喜勿喷。没有18x图片，但是个别图片还是有点，懂的都懂。pid已提供，（pid是什么，懂的都懂），图片版权归原作者及相关网站所有，如有侵权请联系删除。
4：爬
当机器人检测到语句中含有“爬”时，将会回复一张表情包。
图片: https://uploader.shimo.im/f/uZv8W7Nby0rqHFv3.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
5、命令：到点了 | 网易云| 网抑云 | 难过
输入此命令后，机器人将随机返回一句网易云歌曲热评
如：到点了
图片: https://uploader.shimo.im/f/0HE1FtPWqMgtjKP1.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
三、被动技能
1、自动推送原神B站官方账号的动态
此命令无输入，当原神B站官方账号发送动态时，机器人将自动推送动态到微信聊天，推送内容包括文字，图片，不包括视频，视频将推送视频链接。让你不错过任何一条官方消息。
图片: https://uploader.shimo.im/f/IOfM24NhoGrIesOM.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY
注：因为微信不像QQ一样，支持一条消息包含图文，所以当动态中包含很多张图片时，可能会像窜稀一样，发送n多条，不太友好。（所以wx垃圾，qqyyds）
2、5%的概率复读
此命令无输入，人类的本质是【复读机】，有百分之五的概率复读消息。
图片: https://uploader.shimo.im/f/Xlt9InAuZAHJu57c.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJhY2Nlc3NfcmVzb3VyY2UiLCJleHAiOjE2NDI2NTQ2NDMsImciOiJHOFZXcmdramNwSGpxZ0tyIiwiaWF0IjoxNjQyNjU0MzQzLCJ1c2VySWQiOjc1NDQ3NDIyfQ.LFNSKKen7gjLJRpHL3Yzia32F9L5HpLTJwkZlo4RePY


# 感谢
[python-wechaty](https://github.com/wechaty/python-wechaty)   微信机器人框架  
[Genshin_Impact_bot](https://github.com/H-K-Y/Genshin_Impact_bot)   原神大世界资源查询的实现  
查询到的原神信息大多来自于bilibili原神wiki，和米游社原神wiki，可莉特调
