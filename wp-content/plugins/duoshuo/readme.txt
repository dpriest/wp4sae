﻿=== 多说评论框插件 ===
Contributors: shen2
Donate link: http://duoshuo.com/
Tags: comments, social, share, spam, weibo, qzone, widget, 评论, 社会化, 分享, 微博, QQ, 腾讯, 新浪微博, 垃圾评论 
Requires at least: 2.8
Tested up to: 3.3.1
Stable tag: 0.5

追求最佳用户体验的社会化评论框，为中小网站提供新浪微博、QQ、人人、开心网、豆瓣等多帐号登录并评论功能

== Description ==

追求最佳用户体验的社会化评论框，为中小网站提供新浪微博、QQ、人人、开心网、豆瓣、网易微博、搜狐微博、百度等多帐号登录并评论功能。
“多说”帮你搭建更活跃，互动性更强的评论平台。它还有众多实用特性，功能强大且永久免费。

== Installation ==

1. 在Wordpress 插件库中搜索"duoshuo", 下载并启用
2. 在Wordpress “设置 -> 多说”中，设置二级域名并一键注册
3. 同步评论到多说，并进行其他设置

= 建议后续操作 =

4. 在Wordpress “用户 -> 多说用户设置”中，为当前登录账号绑定新浪微博等社交账号。
   - 这样以后用该Wordpress账号发文章时，可以选择同时发一条微博。
   - 在设置时，也可以允许站点内其他用户发文章时同步发到绑定的微博。建议绑定的是官方微博时，选择允许其他用户（如管理员、编辑、作者）使用此微博进行发文章同步。
   - **【特别注意】如果你之前登录过多说评论框并发表过评论，会导致绑定失败，请联系QQ 2310391001**
   
== Frequently Asked Questions ==

= 垃圾评论怎么办？ =

多说不仅会利用akismet，还会有一套自主开发的智能垃圾评论过滤系统帮助你消灭垃圾评论。

= 需要注册吗 =

无需注册，只需用微博、QQ、人人帐号登录即可使用

= 在WordPress后台“用户 -> 多说用户设置"中，绑定新浪微博等账号没反应，怎么办？ = 

这是由于需要绑定的账号登录过多说的原因，请联系QQ 2310391001 帮忙解决

== Screenshots ==
1. 文章/页面下的评论框，支持用新浪微博、QQ、人人、豆瓣、网易微博、搜狐微博、开心网、百度账号帐号登录
2. 评论列表多级回复样式
3. 集成在WordPress后台的多说评论管理界面
4. 多说帮助你和社交网站紧密相连，提升用户黏性，带来更多流量

== Changelog ==

= 0.5.1 (2012-02-09) =
* [改进]同步数据时更人性化的提示信息
* [修正]保存评论到本地时丢失层级关系的问题
* [修正]升级插件时要求重新同步数据的问题

= 0.5 (2012-02-07) =
* [新增]显示文章相关微博
* [新增]插入表情功能
* [新增]喜欢文章功能
* [新增]回复提醒功能
* [新增]自定义评论框CSS功能(感谢“DNSpod团队博客”的反馈)
* [新增]采用Akismet过滤垃圾评论
* [改进]安装流程，避免出现多个帐号的现象
* [改进]启用多说时拒绝垃圾广告机器人利用WP接口发布评论(感谢“绿色精品软件”的反馈)
* [改进]同步文章到微博的模版
* [改进]站点信息更新时，同时更新多说的站点设置
* [改进]关闭文章评论功能(感谢“鸸鹋动物园”的反馈)
* [修正]同步数据慢的问题(感谢“懂得”、“十万个为什么”、“UbuntuSoft”、“前端集合”的反馈)
* [修正]重复同步文章导致部分评论看不到的问题(感谢“UbuntuSoft”的反馈)
* [修正]网易微博头像显示不正常的问题(感谢“动漫X档案”的反馈)
* [修正]和Prototype不兼容的问题(感谢“小权”的反馈)
* [修正]管理后台IE6识别错误的问题(感谢“朋朋”的反馈)
* [修正]WordPress2.8-2.9版本中数据同步不正常的问题(感谢“豆果美食”的反馈)
* [修正]几个安全性漏洞

= 0.4.3 (2012-01-17) =
* [新增]全面支持开心网、搜狐微博、网易微博、百度帐号登陆
* [新增]焕然一新的评论管理后台
* [改进]链接增加nofollow
* [修正]WordPress 3.2以前版本的同步数据兼容性问题
* [修正]部分特殊主题的评论框加载
* [修正]部分用户gravatar头像不显示的问题

= 0.4.2 (2012-01-10) =
* [新增]同步数据时支持断点续传
* [改进]SEO优化，避免和SuperCache类冲突
* [修正]ipad上日期显示不正确的问题

= 0.4.1 (2011-12-26) =
* [新增]高级自定义，可以设置评论框嵌套标签
* [新增]SEO功能/本地评论导入功能的开关
* [修正]同步评论到多说的bug
* [修正]低版本php的兼容性问题
* [修正]网速不快的情况下同步数据超时的问题

= 0.4 (2011-12-25) =
* [新增]支持多说评论反向写回本地数据库(实时的哟)
* [新增]SEO支持，搜索引擎能够爬到评论内容
* [新增]支持HTML解析(白名单制)
* [新增]支持插入视频、图片、表情
* [改进]即使没有curl支持，也可以使用其他方式连接多说服务器
* [改进]安装流程
* [改进]管理界面菜单位置
* [改进]个人帐号管理界面
* [修正]IE6/7下加载评论框报错
* [修正]IE6/7下时间显示错误
* [修正]腾讯微博头像显示问题

= 0.3.3 (2011-12-14) =
* [修正]一个安全漏洞
* [修正]在WordPress3.3下注册站点和注册用户时的bug
* [新增]账号共享功能，允许多人用同一个微博账号发布微博

= 0.3.2 (2011-12-13) =
* [改进]在发布文章同步到微博时带上图片
* [改进]文章没有同步时自动同步

= 0.3.1 (2011-12-12) =
* [修正]在WordPress 3.3下面同步用户不正常的bug
* [修正]新发布的文章不显示评论框的bug

= 0.3 (2011-12-12) =
* [新增]评论管理界面上线
* [改进]全面支持WordPress 3.3

= 0.2 (2011-12-6) =
* [改进]发文章同步到微博、QQ空间和人人的功能
* [新增]登录WordPress后台时，可以同时登录多说
* [新增]WordPress管理界面内就可以绑定社交帐号
* [新增]支持Gravatar头像

= 0.1 (2011-12-2) =
* [新增]基本的功能

== Upgrade Notice ==

= 0.3 =
如果系统提示你“不是管理员或编辑”，请登出WordPress再重新登录

= 0.2 =
之前发布的文章，如果没有出现多说评论框，请点击“多说评论框设置 > 同步评论到多说”。

= 0.1 =
发布文章功能可能工作不正常。

== DEMO ==

已经有上千家网站开始使用多说，其中包括：

1. [下厨房](http://blog.xiachufang.com/ "下厨房")
1. [DNSpod](http://blog.dnspod.cn/ "DNSpod")
1. [Web2.0Share](http://http://www.web20share.com/ "Web2.0Share")
1. [分享网络2.0](www.showeb20.com/ "分享网络2.0")
1. [豆果美食](http://blog.douguo.com/ "豆果美食")
1. [精品绿色便携软件](http://www.portablesoft.org/ "精品绿色便携软件")
1. [鸟类网](http://niaolei.org.cn/ "鸟类网")
1. [鸸鹋动物园](http://www.ermiao.com/ "鸸鹋动物园")
1. [影像视觉杂志](http://www.dcmagcn.com/ "影像视觉杂志")
1. [简约生活](http://www.closhow.cn/ "分享简单质朴设计")
1. [爱新鲜](http://www.ixinxian.com/ "收集新鲜创意的玩意")
1. [MacGG](http://www.macgg.com/ "MacGG")
1. [蘑菇爱家居](http://mooogu.cn/blog "蘑菇爱家居")
1. [九网软件](http://www.hit9.net/ "九网软件")
1. [木偶走天涯](http://www.moonou.com/ "木偶走天涯")

== 接下来会增加的特性 ==

* 数据统计分析
* 个人信息设置功能
* 版权信息自定制功能
* Google+ 帐号支持
* MSN 帐号支持
