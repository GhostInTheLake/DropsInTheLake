# Chat-GPT在跨境电商，外贸工作中的实际落地应用，提升工作效率神器

## 声明

前段时间感染新冠 了，这是一篇迟来的教程，或许不少朋友已经用上了Chat-GPT，但是对于那些还没有接触过的朋友来说，这篇教程或许会对你有所帮助。

这篇教程是我根据实际工作应用撰写的原创内容，大部分都能直接落地使用，如果大家有更多的想法，也欢迎留言评论交流，进一步完善这个工具的使用方法，提升工作效率。

大家也不用担心我这些内容被剽窃，这篇文章写的内容只是我现阶段探索出来的一些交互方法，我相信后期还能探索出更多的用法，也不存在教会徒弟，饿死师傅的问题，欢迎大家随意转载，咱们这圈子其实也没有想象中那么大。

如果阅读完我这篇文章，你能通过这些方法提升效率，甚至卖课赚钱，那都是你的本事，不要有心里负担，当然如果能表明参考出处那是最好

![img](https://pic4.zhimg.com/80/v2-624e75f634acb2a62a3963ec034d1cbb_720w.webp)

## 前言

我大概是从去年6，7月就在V2EX, Reddit上发现很多程序员老哥开始测试，恶搞Chat- GPT，大概8月我自己开始正式使用，去年也是各种AI工具井喷爆发的一年，我同时也测试了如下方表格所示市面上其他一些AI工具（排名不分先后），总体来说，包括Chat-GPT在内各种工具其实都有各自的优缺点。

| 产品                         | 简介                                      | 网址                                                         | 价格                                   |
| ---------------------------- | ----------------------------------------- | ------------------------------------------------------------ | -------------------------------------- |
| Chat-GPT                     | Open AI 出品对话流AI交互工具              | [https://openai.com/blog/chatgpt/](https://link.zhihu.com/?target=https%3A//openai.com/blog/chatgpt/) | 免费                                   |
| DALL·E 2                     | Open AI 出品AI图像工具                    | [https://labs.openai.com/](https://link.zhihu.com/?target=https%3A//labs.openai.com/) | 部分免费，每月会送15点数               |
| Barely AI                    | AI写作助手                                | [https://bearly.ai/](https://link.zhihu.com/?target=https%3A//bearly.ai/) | $20一月或$200一年                      |
| Storywizard                  | 主要用来生成儿童故事                      | [https://www.storywizard.ai/](https://link.zhihu.com/?target=https%3A//www.storywizard.ai/) | 一个故事1美元                          |
| PromptHouse                  | AI绘画，角色建模，视频创作                | [https://www.prompthouse.ai/](https://link.zhihu.com/?target=https%3A//www.prompthouse.ai/) | $25-300                                |
| Digirama - Character Creator | 上传照片AI生成卡通形象                    | [https://apps.apple.com/us/app/character-creator-digirama/id6444673721](https://link.zhihu.com/?target=https%3A//apps.apple.com/us/app/character-creator-digirama/id6444673721) | $6.99 50点数积分                       |
| boo.ai                       | AI写作助手，适合小说创作                  | [https://boo.ai/](https://link.zhihu.com/?target=https%3A//boo.ai/) | $7.99每月                              |
| Scalenut                     | AI写作工具，支持SEO，适合网站，社媒，电商 | [https://www.scalenut.com/](https://link.zhihu.com/?target=https%3A//www.scalenut.com/) | 免费到$149每月不等，节假日年费折扣较大 |
| Ad Creative AI               | 适合社媒帖文，广告文案                    | [https://www.adcreative.ai/](https://link.zhihu.com/?target=https%3A//www.adcreative.ai/) | $29-149每月                            |
| Canva Magic Write            | 适合设计方向相关                          | [https://canva.com](https://link.zhihu.com/?target=https%3A//canva.com) | 免费                                   |
| Chat BCG                     | AI文字生成PPT                             | [https://www.chatbcg.com/](https://link.zhihu.com/?target=https%3A//www.chatbcg.com/) | 免费                                   |
| ContentBot                   | 比较全面的AI写作助手，支持SEO，查重       | [https://contentbot.ai/](https://link.zhihu.com/?target=https%3A//contentbot.ai/) | $99每月                                |
| Rytr                         | 社媒，电商，博客文案生成                  | [https://rytr.me/](https://link.zhihu.com/?target=https%3A//rytr.me/) | 免费到$29每月                          |
| ContentEdge                  | AI写作助手，支持SEO                       | [https://www.contentedge.com/](https://link.zhihu.com/?target=https%3A//www.contentedge.com/) | $29-109每月                            |
| Fliki                        | 视频，音频AI配音，合成                    | [https://fliki.ai/](https://link.zhihu.com/?target=https%3A//fliki.ai/) | $48一年                                |
| Looka                        | logo生成                                  | [https://looka.com/](https://link.zhihu.com/?target=https%3A//looka.com/) | $96一年                                |
| Copy AI                      | AI写作助手                                | [https://app.copy.ai/](https://link.zhihu.com/?target=https%3A//app.copy.ai/) | $48一月                                |
| Moonbeam                     | AI 写作助手，文学，小说方向               | [https://www.gomoonbeam.com/](https://link.zhihu.com/?target=https%3A//www.gomoonbeam.com/) | $15一月                                |
| Word Spinner                 | AI内容重写                                | [https://word-spinner.com/](https://link.zhihu.com/?target=https%3A//word-spinner.com/) | 免费                                   |
| BlogNLP                      | 博客写作助手                              | [https://www.blognlp.com/](https://link.zhihu.com/?target=https%3A//www.blognlp.com/) | 免费                                   |

由于工具太多，涉及到文案部分，这里面我重点推荐大家尝试Chat-GPT, Scalenut, Rytr，我个人平时也是多种工具结合使用，其效果远远比单独使用chat-GPT要好很多，当然今天我们重点讲Chat-GPT部分。

那么，什么是Chat-GPT呢？

Chat-GPT是一种基于自然语言生成的机器人，它可以帮助你与电脑进行聊天。它是基于GPT-3模型开发的，GPT-3是一种预训练的自然语言处理模型，能够帮助计算机理解人类语言。

使用Chat-GPT与电脑进行聊天非常简单。你只需要输入你想说的话，Chat-GPT就会生成一条回复。它的回复并不是预先编写好的，而是通过对你的输入进行分析，生成一条适当的回复。

对于我们这些跨境电商，外贸从业者来说，Chat-GPT更像是我们的一个专业文案小助手，对于日常工作中的大部分涉及到文字的工作，它都可以对我们进行辅助协作。

## 如何注册Chat-GPT

注册其实很简单，但是有两点注意事项：

1. 准备一个海外的手机号码，或者一个接码平台，尽量不要是港澳台，日本的号码。
2. 科学上网线路最好是欧美。亲测，香港，日本容易被屏蔽。

打开[open AI](https://link.zhihu.com/?target=https%3A//openai.com/)官网，在页面页脚出找到[Chat-GPT](https://link.zhihu.com/?target=https%3A//openai.com/blog/chatgpt/)入口，注册用Gmail邮箱即可注册，但是需要用手机号码接收短信验证码验证。

### 推荐的一些实体电话卡

如果是公司使用，考虑作为企业数据资产的长期使用，个人建议还是弄一套海外真实手机号码，香港地区的号码有时候也会失效，所以这里就不推荐港澳地区常见的各种日神，月神卡。

我个人推荐的有：

1. 美国实体手机卡Ultra Mobile，只收短信选3美元一个月的那种套餐，如果还有语音电话业务，可以考虑季付39美元那个套餐，这个号码还可以用来保号验证或者注册新的Google Voice账号（是的，GV号码也越来越严格了），激活问题可以让美国朋友激活后再寄给自己，也可以淘宝，上面有激活好的一条龙服务。
2. 英国实体手机卡CM link，我一直使用的CM link，只收短信买了以后切换成Pay as you Go 套餐，一年充个两三磅，基本用不完。（很多人反馈现在CM link官网是5G套餐，而且薅羊毛的太多，现在限制在中国大陆，港澳地区激活，必须要去英国激活，解决办法很简单，不要去官网下单申请，去淘宝或者飞猪买一个激活的卡即可）
3. 新西兰的实体手机卡，skinny，一年20来块钱，收短信免费，部分电报群有拼车服务，飞猪淘宝也可以尝试，或者有朋友在新西兰的可以请朋友邮一张回来，新西兰各种加油站，超市几乎都有售。

PS: CM link是中国移动海外版，用户信息会传回中国大陆，所以请注意，互联网不是法外之地 。



> **声明：**这些实体卡我都没有放推广链接，Ultra Mobile和CM link是我长期使用的，Skinny是我朋友推荐的，有需要的请自行Google搜索这些具体资费与套餐详情，自行考虑是否购买，只使用Chat-GPT不一定需要实体卡，我只是从企业和open AI未来可能出现的一些风控手段角度考虑做出建议，此处如果你有更好的实体卡建议，也欢迎在下方评论留言以帮助到更多的人

### 接码平台

这里推荐使用[SMS-Activate](https://link.zhihu.com/?target=https%3A//sms-activate.org/)这个平台。

进入官网，在左侧搜索栏搜索open AI。

![img](https://pic2.zhimg.com/80/v2-2976107d8fe748d54ada50107d36e5b9_720w.webp)

![img](https://pic3.zhimg.com/80/v2-25b5c71a8bbe0a43229afdc5f84ae88a_720w.webp)

选择一个目标国家号码，加入购物车，充值购买即可，平台支持支付宝充值。他的价格是卢布的价格，一般充1美元即可，除去手续费，最后账户上大概有60多卢布。

**建议选欧美号码，印尼，马来西亚也行，薅羊毛的很多，现在印度，巴西这些地方的号码经常收不到open AI的短信了。**

![img](https://pic1.zhimg.com/80/v2-1fd0098e1712010f9f7b3dac4ad5ed54_720w.webp)

买完以后，会跳转到一个号码界面，open AI发送短信，到这个界面查看即可。

### 线路问题

如截图所示，我的日本IP经常会显示被拒绝访问，而美国IP，欧洲IP基本都没问题，我有不少朋友的香港IP甚至拉的专线也会遇到这种情况，所以IP建议尽量是欧美的线路。这方面有问题请联系贵公司网管或网络服务商自行解决。

![img](https://pic4.zhimg.com/80/v2-da43c43aeb2f2fa92c926c88cd8011cb_720w.webp)

## Chat-GPT在电商，外贸工作中的具体使用

这里我们只谈跨境电商，外贸相关的一些日常使用，什么写代码，写小说，水自媒体文章什么不在讨论范围之类。

首先我们也要明确一点，吹的再神的神器，它也只是一个工具，就我个人看来，如果是Google代表了成熟的搜索引擎系统，常见的电商app，短视频app代表了成熟的推荐系统，Chat-GPT姑且算是未来“交互引擎”的一个雏形吧，不要神话chat-GPT, 它本身仍然存在很多问题。

它的知识库容量决定了现阶段它无法产出实时性内容，比如我想让它写一篇关于iPhone 14 pro的测评文章，它就不行，因为它的知识库大部分只更新到2021年以前的内容。

它的内容的事实性错误也很多，因为我们看着觉得很厉害的神器，他的结果最初也是靠工作人员一次次的数据标记来判断训练的，没有全知全能的人，所以在很多领域它存在很多问题，比如我就看到过它把杨玉环和明成祖Judy划分到中国伟大的女皇帝的答案中的翻车情况。

现在open AI把这个工具开放给大家，也是希望通过更多的交互，更大的信息体量进一步的训练这个模型。

上述个人看法如果有不对的地方，也欢迎大家批评指正。

当然，对于我们的日常工作，大部分他还是可以胜任的。下面来讲讲常见的一些工作案例。

为了方便，我这里先假设我是一个销售滑雪产品的的品牌，包含了2B与2C的业务，后面的对话信息也是基于滑雪产品来举例。

为了担心与AI交互中产生歧义，我所有的对话几乎都是用英文来问答, 这里也体现出一个好处，哪怕我这种工地英语水平，只要你能表述清楚目的，Chat-GPT也能读懂并输出内容。

我个人也建议大家使用使用英语，因为有些营销活动，文案方面的问题，我也不知道中文到底是什么，如果你英语实在不太好，可以用Google translate，DeepL这些工具翻译后再输入。

### 品牌取名

不管是英文商学里面的 “Your company name is often the first element of your brand”， 特劳特的“The mind works by ear, not by eye.” 还是国内出名的华与华，小马宋等大佬的理论，取一个好的品牌名对我们的品牌有着很大的加分。

但如果你做亚马逊，你会发现很多店铺品牌取的名字要么是拼音，要么是老外都看的一眼懵，念都不知道怎么念的离谱字母组合词，我个人有时候觉得就挺离谱的，你难道我会记住指望一个我连音都发不出的所谓品牌名，而不是Apple，Google，Anker, Target这种朗朗上口的品牌名？

我知道很多公司为了多注册店铺，这些工作大多数都是直接安排财务人员，或者找外包服务商搞定，他们很多可能在取名这块是不太行，可能只考虑不会重复，能够把这个品牌注册下来。那么使用Chat-GPT在取名这一部分就可以很好的解决这个问题。

我：

> I have a ski brand that sell ski goggles, give me 10 company name ideas

**Chat-GPT:**

> Here are ten potential company names for a ski goggles brand:
> 1.FrostyVision
> 2.PeakPerformanceGoggles
> 3.SnowSight
> 4.GlacialVision
> 5.ArcticEyes
> 6.PowderPro
> 7.SummitSeer
> 8.SlopeSight
> 9.ColdFrontGoggles
> 10.MountainView

这品牌名就好很多，如果你还是不满意，还可以继续让它再多给你一些建议。注册的时候也可以多几个备用选项。

### 撰写营销计划

我：

> make a marketing plan to promote my ski brand. I make ski goggles to make people enjoy the ski sport

**Chat-GPT:**

> Sure! Here is a basic outline for a marketing plan to promote your ski goggles brand:
> 1.Define your target market: Who are your goggles intended for? Are they for casual skiers or professional athletes? Are they for children or adults? Understanding your target market will help you tailor your marketing efforts.
> 2.Determine your marketing budget: How much money do you have available to allocate towards marketing efforts? This will help you determine which strategies and tactics are feasible for your brand.
> 3.Develop a brand identity: Your brand identity is how you want your brand to be perceived by your target market. This includes your brand name, logo, slogan, and overall aesthetic. Your brand identity should be consistent across all marketing materials.
> 4.Create a website: A website is a crucial part of any marketing plan. It should be professional, easy to navigate, and provide information about your products, including high-quality photos and detailed product descriptions.
> 5.Use social media: Social media is a powerful tool for promoting your brand. Create profiles on platforms like Instagram, Facebook, and Twitter and use them to share photos and information about your products, as well as ski-related content that will be of interest to your target market.
> 6.Consider paid advertising: Paid advertising can be an effective way to reach a larger audience, but it can also be expensive. Consider options like Google AdWords, social media ads, or sponsored posts on popular ski blogs or websites.
> 7.Collaborate with ski resorts and shops: Partnering with ski resorts and shops can help get your brand in front of a large, targeted audience. Consider offering discounts to resort employees or setting up a product demo at a ski shop.
> 8.Attend ski trade shows: Trade shows are a great opportunity to showcase your products and network with other industry professionals. Look for trade shows specific to the ski industry and consider exhibiting at them.
> 9.Encourage customer reviews and testimonials: Customer reviews and testimonials can be a powerful marketing tool. Encourage your customers to leave reviews on your website or social media profiles, and consider featuring testimonials on your website or in marketing materials.
> 10.Monitor and track your results: It's important to regularly track and measure the effectiveness of your marketing efforts. Use tools like Google Analytics to track website traffic, social media analytics to track engagement, and sales data to track conversions. This will help you identify what's working and what may need to be adjusted.
> I hope this helps! Let me know if you have any other questions.

Chat-GPT 给出的营销计划建议包括：

1. 明确你的目标市场，包括滑雪镜的目标人群，适合专业运动人士还是休闲滑雪爱好者，针对成人还是儿童等等
2. 明确我们的营销资金预算
3. 建立品牌标识，包括品牌名，logo，slogan，和品牌风格等
4. 创建品牌网站
5. 使用社交媒体
6. 考虑付费广告
7. 与滑雪胜地的商店合作
8. 参加滑雪贸易展会
9. 鼓励用户评价推荐
10. 监控追踪营销结果

发现没有，即使你对营销是一头雾水，Chat-GPT也能从大的方向上引导规划你的产品营销方向。如果你有营销背景或相关知识，那么你可以根据这些建议选取当前最适合你产品的营销策略。

------

### 撰写品牌Slogan

我：

> FrostyVision is pretty good, write 5 slogan for it

**Chat-GPT:**

> Here are five potential slogans for FrostyVision ski goggles:
> \1. "Crystal clear vision, even in the coldest conditions."
> 2."See the mountain like never before with FrostyVision."
> 3."Stay focused on the slopes with our anti-fog technology."
> 4."Experience the ultimate in winter eye protection with FrostyVision."
> 5."Elevate your ski game with FrostyVision's superior clarity."

------

### 撰写Google广告文案

我：我的目标受众是普通的休闲滑雪爱好者，给我写5条Google广告文案

> my target audience is the casual skier, write 5 google ads copy for me

**Chat-GPT:**

> Sure! Here are five potential Google Ads copy options for your ski goggles brand targeting casual skiers:
> \1. "Experience the best of the slopes with our high-quality ski goggles" - This copy highlights the benefits of using your goggles and positions them as a must-have for anyone looking to fully enjoy their time on the slopes.
> 2."Stay comfortable and protected on the mountain with our ski goggles" - This copy focuses on the practical benefits of your goggles, like comfort and protection from the elements.
> 3."Upgrade your ski gear with our stylish and functional goggles" - This copy highlights the style and functionality of your goggles, making them an attractive choice for anyone looking to improve their ski gear.
> 4."Get the most out of your ski vacation with our performance-enhancing goggles" - This copy positions your goggles as a way to improve your overall ski experience, making them a worthwhile investment for casual skiers.
> 5."From beginner to advanced skier, our goggles have you covered" - This copy speaks to a wide range of skiers and positions your goggles as suitable for anyone, regardless of their skill level.
> I hope these suggestions are helpful! Let me know if you have any other questions.


我：我觉得第一条广告文案不错，给这一条文案写一段广告描述文案

> the first title copy looks great, write a google ads description for it

**Chat-GPT:**

> Sure! Here is a potential Google Ads description for the title copy "Experience the best of the slopes with our high-quality ski goggles":
> "Looking to get the most out of your time on the mountain? Our ski goggles are here to help. Designed with performance and comfort in mind, our goggles are perfect for skiers of all levels. Featuring high-quality lenses and a durable frame, they'll protect your eyes from the elements and help you see clearly on the slopes. Plus, with a stylish design and a range of colors to choose from, you'll look good while you ski. Upgrade your ski gear and experience the best of the slopes with our ski goggles."
> This description expands on the benefits of using your goggles and speaks to the target audience of casual skiers. It highlights the practical benefits, like performance and comfort, as well as the stylish design. It also mentions the high-quality materials used in the goggles, which can help build credibility and trust with potential customers.
> I hope this helps! Let me know if you have any other questions.

我：添加一段关于滑雪镜防紫外线的卖点到文案

> add an UV protection feature in the copy

**Chat-GPT:**

> Sure! Here is an updated version of the Google Ads description with the added feature of UV protection:
> "Looking to get the most out of your time on the mountain? Our ski goggles are here to help. Designed with performance and comfort in mind, our goggles are perfect for skiers of all levels. Featuring high-quality lenses with UV protection and a durable frame, they'll protect your eyes from the elements and harmful UV rays while helping you see clearly on the slopes. Plus, with a stylish design and a range of colors to choose from, you'll look good while you ski. Upgrade your ski gear and experience the best of the slopes with our ski goggles."
> This revised version includes the added benefit of UV protection, which can be an important feature for many skiers. By highlighting this feature, you can differentiate your goggles from competitors and address a potential pain point for potential customers.
> I hope this helps! Let me know if you have any other questions.

### Facebook广告

比如我想针对我的休闲滑雪爱好者这个目标受众群体，写一个广告包含了这些人群他们的使用体验，并且鼓励大家积极评价反馈的广告。

**我：**

> write a Facebook ad copy that will showcase the unique and personal experiences of casual skier with my ski goggles and persuade them to share their positive review with their followers.

**Chat-GPT:**

> Attention: Are you a casual skier looking for the perfect pair of ski goggles?
> Interest: Our ski goggles are designed with both style and function in mind, and they've been tested and loved by skiers just like you.
> Desire: But don't just take our word for it - check out these personal experiences from happy customers who have shared their positive reviews on our page:
> "I was a little hesitant to try a new brand of ski goggles, but I'm so glad I did! These are the best goggles I've ever owned - the anti-fog technology is top-notch and the style is on point. I've already recommended them to all my ski buddies."
> "I love my new ski goggles! They're super comfortable and stay in place no matter how much I'm moving around on the mountain. Plus, the anti-fog technology is a game-changer - no more foggy lenses ruining my runs. Highly recommend!"
> Action: Want to join the ranks of satisfied customers and share your positive experience with your followers? Click here to check out our ski goggles and share your review on our page.

### YouTube 视频广告

比如我想让他写一个YouTube视频广告的脚本文案，向休闲滑雪者展示我的滑雪护目镜的价值和好处，并通过一个报价或者折扣和明确的号召性用语说服他们立即购买。

**我：**

> Write a YouTube ad script that will showcase the value and benefits of my ski goggles to casual skier and persuade them to shop now with a strong offer and clear call-to-action.

**Chat-GPT:**

> Hello skiers! Are you tired of constantly having to deal with foggy ski goggles that obstruct your vision on the slopes? We know how frustrating and potentially dangerous this can be, which is why we've designed a solution: our ski goggles.
> Our goggles are equipped with advanced anti-fog technology, ensuring crystal clear vision during even the most intense runs. Plus, they have a sleek, stylish design that will make you stand out on the mountain. And with a durable, aerodynamic frame and comfortable, adjustable strap, they're the perfect choice for all your winter sports needs.
> But don't just take our word for it - check out these testimonials from happy customers who have tried our ski goggles:
> "I was a little hesitant to try a new brand of ski goggles, but I'm so glad I did! These are the best goggles I've ever owned - the anti-fog technology is top-notch and the style is on point. I've already recommended them to all my ski buddies."
> "I love my new ski goggles! They're super comfortable and stay in place no matter how much I'm moving around on the mountain. Plus, the anti-fog technology is a game-changer - no more foggy lenses ruining my runs. Highly recommend!"
> Don't let foggy goggles ruin your next ski trip. Upgrade to our high-quality, anti-fog ski goggles today and experience the benefits for yourself. And as a special offer for our YouTube viewers, use the code "YOUTUBE10" at checkout to get 10% off your purchase. Don't miss out - shop now and take your ski game to the next level.

### Linkedin 广告

我：我还有滑雪镜的B2B业务，给我写三条领英广告来推广我的B2B业务部分

> I also have ski goggles B2B Business, write 3 Linkedin ads copy to promote my B2B business part

**Chat-GPT:**

> *Sure! Here are three potential LinkedIn Ads copy options to promote your ski goggles B2B business:*
> *"Outfit your ski resort with top-quality goggles" - This copy targets ski resorts as potential buyers and positions your goggles as a high-quality choice for their needs.*
> *"Elevate your ski shop's gear offerings with our goggles" - This copy targets ski shops and highlights the opportunity for them to offer a higher-end product to their customers.*
> *"Improve the experience of your ski tour guests with our goggles" - This copy targets ski tour operators and positions your goggles as a way to enhance the overall experience of their guests.*
> *I hope these suggestions are helpful! Let me know if you have any other questions.*

### 8种常见广告文案套路的输入模板：

我们在日常准备这些平台广告的时候，往往也有不同的文案策略套路，不管是针对不同的活动，或者用来做AB Test, 这里我分享我常用的8种文案套路供大家参考,使用时根据你的实际产品+目标客户群体根据我的输入模板进行适当修改输入到Chat-GPT即可：

1.强有力的标题和文案吸引目标客户群体，使用具有说服力的证据来说服客户采取行动

Write a Facebook ads copy/YouTube ads script (或者替换为其他平台，Twitter,TikTok,IG等等)that will draw in [你的产品的目标客户群体] with a strong headline and hook, and then convince them to [CTA采取行动，Shop now, Grab it today,Sign up 等常见的CTA用词，后面不再重复解释] with persuasive language and compelling evidence.

2.向目标客户群体展示我们产品独特的卖点，特性，附加上social proof来获取受众的信任，并鼓励引导他们采取行动

Write a Facebook ads copy/ YouTube ad script that will showcase the unique features and benefits of my [你的产品或者服务] to [你的目标客户群体] and persuade them to make a purchase with social proof and credibility-building elements.

3.如果我是一个比较成熟专业的品牌产品，我想通过我的品牌专业度和权威性来教育用户，告诉他们我产品的好处，并引导他们购买，可以这么输入：

Write a Facebook ad copy(或者其他平台) that will leverage the authority and expertise of [你的品牌或者公司] to educate my [目标客户群] on the benefits of my [产品或服务] and persuade them to make a purchase.

\4. 提供一个独家的折扣，并给目标客户提供一种容易错过的紧迫感

I need a [广告平台] ad copy that will create a sense of urgency and FOMO for my [目标客户群] by featuring exclusive deals and promotions for my [产品或服务]

PS. FOMO就是Fear of missing out, 我测试过输入FOMO，chat- GPT可以理解这个缩写

5.根据和红人合作的素材，利用红人的影响力来影响目标客户群体，并引导客户购买，有两种情况：

I need a ad copy that will use the influence and reach of [红人类型] to showcase the unique features and benefits of my [产品或者服务] to [你的目标客户群] and encourage them to make a purchase.

I need a [广告平台] ad copy that will leverage the authority and credibility of [红人类型] to educate [目标客户群] on the benefits of my [产品或服务] and persuade them to try it out for themselves

6.说明目标用户群体的痛点或者问题，营造一种紧迫感来引导客户采取行动

I'm looking for a YouTube ad script / Facbook Ads copy that will speak directly to the needs and pain points of [目标客户群体] and persuade them to [CTA行动号召] with a sense of urgency and strong offer.

\7. 通过以前使用过我的产品或者服务的素人种草推荐，来建立目标客户群体对我品牌或者产品的信任感

Write a YouTube ad script/Facbook Ads copy that will establish trust and credibility with [目标客户群体] by highlighting the successes and testimonials of previous customers who have used my [产品或者服务]

\8. 通过与红人的联动，鼓励目标客户群体与红人进行互动，真实的分享产品或服务的好处，并鼓励大家购买

write a Facebook ad copy that will engage [目标客户群] with [与红人策划好的活动内容] from [你的合作红人类型] who can authentically share the benefits of my [产品或者服务] and encourage them to make a purchase.

### 撰写基础产品文案

我：

> *write a ski goggles product feture copy*

**Chat-GPT:**

> *Our ski goggles are designed with the ultimate in winter sports performance in mind. With a sleek, aerodynamic frame and comfortable, adjustable strap, our goggles will stay securely in place no matter how rough the terrain gets. The lenses are made from a high-quality, shatter-resistant material that can withstand the cold and harsh conditions of the mountain. Plus, the lenses are treated with an anti-fog coating to ensure crystal clear vision during even the most intense runs. Whether you're an experienced skier or just starting out, our goggles are the perfect choice for all your winter sports needs.*

如果你是做亚马逊，沃尔玛这类平台型网站，可以很方便的通过这些文案来提炼自己的卖点，如果你还有其他独特的卖点，也可以继续输入让其重新优化生成文案

如果你是做独立站，发社媒，或者在准备一些宣传材料，在考虑这个文案的基础上，我们还可以让它改写成更具有营销风格的文案，常见的文案风格框架包括：

1. AIDA
2. PAS
3. BAB
4. Feature to Benefit
5. SPF(2B)

在这里先科普一下，以便没有这方面相关知识的读者更容易理解。

### AIDA文案

**AIDA**可能是最最最常见的模型，哪怕你没有太多的营销背景知识，做我们这行的也一定听说过一个词叫做营销漏斗。

AIDA即Attention, Interest, Desire, Action， 可以理解为是引起注意，诱发兴趣，刺激欲望，促成购买。

由此引申出一种AIDA文案写作框架，通常用于以一种旨在引导读者完成购买决定过程的方式构建营销和广告材料。

根据 AIDA 模型，流程的第一步是引起读者的注意。 这可以通过多种方式实现，例如使用醒目的标题或醒目的视觉效果。 一旦吸引了读者的注意力，下一步就是引起对所提供产品或服务的兴趣。 这可以通过使用引人注目的内容或突出产品或服务的优势来实现。

第三步是创造对产品或服务的渴望。 这可以通过展示产品或服务如何满足读者的需求，或者通过为读者制造购买的紧迫感来实现。 最后，最后一步是鼓励读者采取行动并进行购买。 这可以通过使用号召性用语或提供特别促销或折扣来实现。

总体而言，AIDA 模型是一个框架，可帮助企业了解如何有效地向消费者推销其产品或服务以产生销售额。

当我们要写一个AIDA风格的文案时，可以直接输入：

> rewrite the copy in style of AIDA model

**Chat-GPT:**

> Attention: Are you in search of the perfect ski goggles? Look no further.
> Interest: Our goggles feature a sleek, aerodynamic frame and comfortable, adjustable strap for a secure fit on the slopes. The shatter-resistant lenses are treated with an anti-fog coating for crystal clear vision, no matter the conditions.
> Desire: Whether you're an experienced skier or just starting out, these goggles will enhance your winter sports experience.
> Action: Don't miss out on the opportunity to upgrade your ski gear. Try our high-quality ski goggles today and take your performance to the next level.

### PAS文案

**PAS** 是 Problem、Agitation、Solution 的缩写。 它是一个文案框架，通常用于构建有说服力的写作，特别是在营销和广告的背景下。 PAS 的目标是识别和解决读者的问题，围绕问题营造紧迫感，然后提供解决问题的方法。

根据 PAS 框架，第一步是确定读者面临的问题。 这可能是读者正在经历的痛点、挑战或挫折。 下一步是激起问题，或者围绕它创造一种紧迫感。 这可以通过强调不解决问题的后果或强调读者解决问题的愿望来实现。

最后，最后一步是提供问题的解决方案。 这可以是正在宣传的产品或服务，也可以是推荐或建议。 解决方案的目标是帮助读者克服文章中较早发现和存在的问题。

让Chat-GPT 重写成PAS风格的文案：

> Rewrite the ski goggles copy in style of PAS framework

**Chat-GPT:**

> Problem: Are you tired of ski goggles that fog up and obstruct your vision on the slopes?
> Agitation: This can be a frustrating and dangerous problem, especially if you rely on clear vision to navigate the mountain. Imagine missing a turn or not being able to see obstacles in your path because of foggy goggles.
> Solution: Our ski goggles are equipped with advanced anti-fog technology, ensuring crystal clear vision during even the most intense runs. Plus, the sleek, stylish design will make you stand out on the mountain. Don't let foggy goggles ruin your next ski trip. Upgrade to our high-quality, anti-fog ski goggles today and enjoy the benefits of clear vision on the slopes.

### BAB文案

**BAB**，或 Before，After，Bridge，是一种文案写作框架，旨在以强调产品或服务可以带来的转变或改进的方式构建有说服力的写作。

根据 BAB 框架，第一步是描述读者当前面临的情况或问题（“之前”阶段）。 这可能是读者正在经历的痛点、挑战或挫折。 下一步是描述所宣传的产品或服务如何帮助解决问题或带来积极的转变（“后”阶段）。 最后，最后一步是提供两个阶段之间的“桥梁”，解释产品或服务如何带来转变以及它如何为读者做同样的事情。

让Chat- GPT重写成BAB风格的文案：

> Write the ski goggles copy in style of BAB framework

**Chat-GPT:**

> Before: Are you fed up with constantly having to deal with foggy ski goggles that obstruct your vision on the slopes? This can be a frustrating and potentially dangerous problem, especially if you rely on clear vision to navigate the mountain.
> After: Our ski goggles are equipped with advanced anti-fog technology, ensuring crystal clear vision during even the most intense runs. No more missed turns or dangerous obstacles because of foggy goggles.
> Bridge: The transformation our goggles can bring about is clear. By eliminating fog, you'll be able to enjoy a safer and more enjoyable ski experience. Plus, the sleek, stylish design will make you stand out on the mountain. Don't let foggy goggles ruin your next ski trip. Upgrade to our high-quality, anti-fog ski goggles today and experience the difference for yourself.

### Feature to Benefit 文案

Feature to Benefit 风格则是直接明了说明产品卖点与给消费者带来的好处。

让Chat-GPT写成Feature to Benefit风格的文案：

> write the ski goggles copy in style of features benefits copywriting framework

**Chat- GPT：**

> Our ski goggles are designed with both style and function in mind.
> Features:
> Aerodynamic frame for a secure, comfortable fit
> Shatter-resistant lenses for added durability
> Anti-fog coating for crystal clear vision
> Adjustable strap for a customizable fit
> Benefits:
> Improved performance on the slopes with a secure, comfortable fit
> Enhanced protection from the elements with shatter-resistant lenses
> Better visibility in any condition with anti-fog technology
> Customizable fit for maximum comfort during long days on the mountain
> Overall, our ski goggles are the perfect choice for winter sports enthusiasts who want both style and function in their eyewear.

### SPF文案

SPF这是一个常见的B端文案框架，分别代表Stages阶段, Psychology心理学, and Funnel漏斗。

不像前面的四种文案框架，大部分2C的朋友日常可能大量接触文案工作，前面的几个文案框架内容即使没有营销背景知识，也很容易理解。

我认识的很多做2B的朋友可能没有相关的知识补充，我在这里针对2B的这个SPF文案框架多讲两句。

同时也由于Chat-GPT对于SPF框架的理解是Sender Policy Framework，这是一种检测邮件身份验证的方法，所以这里你需要先向AI解释你的SPF文案框架是代表了哪些内容。

![img](https://pic3.zhimg.com/80/v2-5e035b278a8eba1dd6e6782088f7846a_720w.webp)

![img](https://pic3.zhimg.com/80/v2-8de5d5d50c94fff452d5e95b2944caae_720w.webp)

Stages阶段一般包含四个阶段，这个是指潜在客户对于我们的目标产品的不同认知阶段，不同于营销上的Awareness阶段，这里的Stages更相当于Buyer's Journey：

1. Problem Unaware
2. Category Unaware
3. Product Unaware
4. Product aware

第一个阶段，你的产品虽然解决了问题，但是你的一些潜在客户甚至没有意识到他们存在问题。比如客户是做网站的，你是开发聊天机器人的，客户自己网站数据表现不佳，跳出率高，用户留存低，有的客户可能就没有意识到如果通过一些手段，提供用户与网站的交互，就可以大大的提升网站的留存，极端一点有的客户可能脑子里就没有交互这个概念。或者你是销售某种机械设备的，能够提升某些生产环节的生产效率，但是某些工厂可能压根儿就不了解，在这个生产环节上还是采用传统的手工生产方式。

第二阶段，客户知道他们存在问题，但是他们不知道找哪个类目的供应商来最终解决他们的问题。

第三阶段，就是客户知道他们的问题，也知道在哪个类目，方向做出选择，但是不知道选哪一家的产品。他们不熟悉你的产品或你的特定品牌。他们不知道你的特定产品有什么好处。他们不知道你的特定产品是做什么的，他们从未听说过你的品牌名称。

第四阶段，才是客户知道他们的问题，知道哪个类目，哪个方向的产品解决他们的问题，最重要的是客户知道你的产品，你的品牌能够解决他们的问题。

B2B 文案写作需要对商业术语、关键行业洞察力的专业理解，以及将复杂主题提炼成清晰、简洁语言的能力。 能够以与目标受众产生共鸣的方式写作也很重要，因为 B2B 买家通常对产品或服务的实用价值更感兴趣，而不是它可能唤起的情感或感受。

传统的AIDA漏斗模型，容易给2B业务造成一种错觉，如果你的文案一上来就是各种开发，推销，折扣，而目标潜在客户都没有意识到自己的问题时，那么一定是你有问题，你选择性忽视掉了前面漏斗顶部更大的潜在客户群体。

第二部分心理学，B2B商业写作的核心是说服力。 它使用文字和图像来向其他商业专业人士推广和销售你的产品和想法。 虽然有许多不同的方法可以实现这一点，但共同点是心理学。 它让人们相信您的想法和产品值得投资。

B2B 文案写作和更普遍的销售流程的一个问题是，许多公司都停留在现状并使用旧产品。 他们没有兴趣或动力去改变他们的商业行为，所以很难让他们有足够的动力和足够的信息来采取措施进入你的销售渠道。

心理学部分一般包含5大阶段：

1. Reactance
2. Endowment
3. Distance
4. Uncertainty
5. Corroborating Evidence

最终Chat-GPT输出的一份B2B文案：

> Stages:
> Problem Unaware: Many winter sports enthusiasts struggle with foggy ski goggles that obstruct their vision on the slopes.
> Category Unaware: Our ski goggles are specifically designed to address this problem with advanced anti-fog technology.
> Product Unaware: In addition to their performance benefits, our goggles have a sleek, stylish design that will make your team stand out on the mountain.
> Product Aware: With a durable, aerodynamic frame and comfortable, adjustable strap, our goggles are the perfect choice for all your winter sports needs.
> Psychology:
> Reactance: Our ski goggles offer a solution to a common problem that many winter sports enthusiasts experience. By highlighting the benefits of our anti-fog technology, we aim to appeal to their desire to overcome this issue.
> Endowment: The sleek, stylish design of our goggles will make your team feel proud to wear them on the mountain.
> Distance: Our durable, aerodynamic frame and shatter-resistant lenses help to alleviate concerns about the goggles breaking or being damaged during use.
> Uncertainty: By highlighting the benefits and addressing the needs and concerns of our target audience, we aim to reduce any uncertainty they may have about choosing our ski goggles.
> Corroborating Evidence: Testimonials from satisfied customers and data-driven performance claims can serve as corroborating evidence to support the effectiveness and value of our ski goggles.
> Funnel:
> Our marketing materials are designed to effectively guide potential customers through the four stages of the purchasing process. By highlighting the benefits, addressing the needs and concerns of our target audience, and providing corroborating evidence, we aim to persuade them to choose our ski goggles for their winter sports needs.

