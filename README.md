# rog-huashuo
rog-huashuo
|             Name             |             归属             |  属性  | 说明                                                         |
| :--------------------------: | :--------------------------: | :----: | ------------------------------------------------------------ |
|        `JD_BEAN_STOP`        |      京东多合一签到             | 非必须 | `jd_bean_sign.js`自定义延迟签到,单位毫秒.默认分批并发无延迟，<br>延迟作用于每个签到接口，如填入延迟则切换顺序签到(耗时较长)，<br>如需填写建议输入数字`1`，详见[此处说明](https://github.com/NobyDa/Script/blob/master/JD-DailyBonus/JD_DailyBonus.js#L93) |
|  `JD_BEAN_SIGN_STOP_NOTIFY`  |      京东多合一签到             | 非必须 | `jd_bean_sign.js`脚本运行后不推送签到结果通知，默认推送，填`true`表示不发送通知 |
| `JD_BEAN_SIGN_NOTIFY_SIMPLE` |      京东多合一签到             | 非必须 | `jd_bean_sign.js`脚本运行后推送签到结果简洁版通知，<br>默认推送签到简洁结果，填`true`表示推送简洁通知，[效果图](./icon/bean_sign_simple.jpg) |
|     `PET_NOTIFY_CONTROL`     |     东东萌宠<br>推送开关     | 非必须 | 控制京东萌宠是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `FRUIT_NOTIFY_CONTROL`    |     东东农场<br>推送开关     | 非必须 | 控制京东农场是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `CASH_NOTIFY_CONTROL`    |     京东领现金<br>推送开关     | 非必须 | 控制京东领现金是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `CASH_EXCHANGE`    |     京东领现金<br>红包兑换京豆开关     | 非必须 | 控制京东领现金是否把红包兑换成京豆,<br>`false`为否,`true`为是(即：花费2元红包兑换200京豆，一周可换四次)，默认为`false` |
|    `DDQ_NOTIFY_CONTROL`    |     点点券<br>推送开关     | 非必须 | 控制点点券是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `JDZZ_NOTIFY_CONTROL`    |     京东赚赚小程序<br>推送开关     | 非必须 | 控制京东赚赚小程序是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `MONEYTREE_NOTIFY_CONTROL` |     京东摇钱树<br>推送开关     | 非必须 | 控制京东摇钱树兑换0.07金贴后是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `JD_JOY_REWARD_NOTIFY`    |  宠汪汪<br>兑换京豆推送开关  | 非必须 | 控制`jd_joy_reward.js`脚本是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|       `JOY_FEED_COUNT`       |        宠汪汪喂食数量        | 非必须 | 控制`jd_joy_feedPets.js`脚本喂食数量,可以填的数字0,10,20,40,80,其他数字不可. |
|       `JOY_HELP_FEED`        |       宠汪汪帮好友喂食       | 非必须 | 控制`jd_joy_steal.js`脚本是否给好友喂食,`false`为否,`true`为是(给好友喂食) |
|        `JOY_RUN_FLAG`        |        宠汪汪是否赛跑        | 非必须 | 控制`jd_joy.js`脚本是否参加赛跑(默认参加双人赛跑),<br>`false`为否,`true`为是，脚本默认是`true` |
|       `JOY_TEAM_LEVEL`       | 宠汪汪<br>参加什么级别的赛跑 | 非必须 | 控制`jd_joy.js`脚本参加几人的赛跑,可选数字为`2`,`10`,`50`，<br>其中2代表参加双人PK赛，10代表参加10人突围赛，<br>50代表参加50人挑战赛(注：此项功能在`JOY_RUN_FLAG`为true的时候才生效)，<br>如若想设置不同账号参加不同类别的比赛则用&区分即可(如下三个账号：`2&10&50`) |
|       `JOY_RUN_NOTIFY`       | 宠汪汪<br>宠汪汪赛跑获胜后是否推送通知 | 非必须 | 控制`jd_joy.js`脚本宠汪汪赛跑获胜后是否推送通知，<br>`false`为否(不推送通知消息),`true`为是(即：发送推送通知消息)<br> |
|    `JOY_RUN_HELP_MYSELF`      |    宠汪汪<br>赛跑自己账号内部互助     | 非必须 | 输入`true`为开启内部互助 |
|     `JD_JOY_REWARD_NAME`     |  宠汪汪<br>积分兑换多少京豆  | 非必须 | 目前可填值为`20`或者`500`,脚本默认`0`,`0`表示不兑换京豆     |
|     `JOY_RUN_TOKEN`     |  宠汪汪<br>赛跑token  | 非必须 | 需自行抓包，宠汪汪小程序获取token，点击`发现`或`我的`，寻找`^https:\/\/draw\.jdfcloud\.com(\/mirror)?\/\/api\/user\/user\/detail\?openId=`获取token     |
|    `MARKET_COIN_TO_BEANS`    |    东东超市<br>兑换京豆数量    | 非必须 | 控制`jd_blueCoin.js`兑换京豆数量,<br>可输入值为`20`或者`超值京豆包`的数字或者其他商品的名称,例如`碧浪洗衣凝珠` |
|    `MARKET_REWARD_NOTIFY`    |  东东超市<br>兑换奖品推送开关  | 非必须 | 控制`jd_blueCoin.js`兑换奖品成功后是否静默运行,<br>`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) |
|    `JOIN_PK_TEAM`            |    东东超市<br>自动参加PK队伍    | 非必须 | 每次pk活动参加作者创建的pk队伍,`true`表示参加,`false`表示不参加 |
|    `SUPERMARKET_LOTTERY`     |          东东超市抽奖          | 非必须 | 每天运行脚本是否使用金币去抽奖,`true`表示抽奖,`false`表示不抽奖 |
|      `FRUIT_BEAN_CARD`       |    东东农场<br>使用水滴换豆卡    | 非必须 | 东东农场使用水滴换豆卡(如果出现限时活动时100g水换20豆,此时比浇水划算,推荐换豆),<br>`true`表示换豆(不浇水),`false`表示不换豆(继续浇水),脚本默认是浇水 |
|       `UN_SUBSCRIBES`        |      jd_unsubscribe.js       | 非必须 | 共四个参数,换行隔开.四个参数分别表示<br>`是否取关全部商品(0表示一个都不)`,`是否取关全部店铺数(0表示一个都不)`,`遇到此商品不再进行取关`,`遇到此店铺不再进行取关`，[具体使用往下看](#取关店铺环境变量的说明) |
|       `JDJOY_HELPSELF`       |    疯狂的JOY<br>循环助力     | 非必须 | 疯狂的JOY循环助力，`true`表示循环助力,`false`表示不循环助力，默认不开启循环助力。 |
|     `JDJOY_APPLYJDBEAN`      |    疯狂的JOY<br>京豆兑换     | 非必须 | 疯狂的JOY京豆兑换，目前最小值为2000京豆(详情请查看活动页面-提现京豆)，<br>默认数字`0`不开启京豆兑换。 |
|       `BUY_JOY_LEVEL`        |   疯狂的JOY<br>购买joy等级   | 非必须 | 疯狂的JOY自动购买什么等级的JOY                               |
|   `MONEY_TREE_SELL_FRUIT`    |    摇钱树<br>是否卖出金果    | 非必须 | 控制摇钱树脚本是否自动卖出金果兑换成金币，`true`卖出，`false`不卖出，默认`false` |
| `FACTORAY_WANTPRODUCT_NAME`  |     东东工厂<br>心仪商品     | 非必须 | 提供心仪商品名称(请尽量填写完整和别的商品有区分度)，达到条件后兑换，<br>如不提供则会兑换当前所选商品 |
| `DREAMFACTORY_FORBID_ACCOUNT`|    京喜工厂<br>控制哪个京东账号不运行此脚本     | 非必须 | 输入`1`代表第一个京东账号不运行，多个使用`&`连接，例：`1&3`代表账号1和账号3不运行京喜工厂脚本，注：输入`0`，代表全部账号不运行京喜工厂脚本 |
| `JDFACTORY_FORBID_ACCOUNT`|    东东工厂<br>控制哪个京东账号不运行此脚本     | 非必须 | 输入`1`代表第一个京东账号不运行，多个使用`&`连接，例：`1&3`代表账号1和账号3不运行东东工厂脚本，注：输入`0`，代表全部账号不运行东东工厂脚本 |
|    `CFD_NOTIFY_CONTROL`      |    京喜财富岛<br>控制是否运行脚本后通知     | 非必须 | 输入`true`为通知,不填则为不通知 |
|    `JXNC_NOTIFY_LEVEL`      |    京喜农场通知控制<br>推送开关,默认1     | 非必须 | 通知级别 0=只通知成熟;1=本次获得水滴>0;2=任务执行;3=任务执行+未种植种子 |
|    `PURCHASE_SHOPS`      |    执行`lxk0301/jd_scripts`仓库的脚本是否做加物品至购物车任务。默认关闭不做加购物车任务     | 非必须 | 如需做此类型任务。请设置`true`，目前东东小窝(jd_small_home.js)脚本会有加购任务 |
|    `TUAN_ACTIVEID`      |    京喜工厂拼团瓜分电力活动的`activeId`<br>默认读取作者设置的     | 非必须 | 如出现脚本开团提示失败：`活动已结束，请稍后再试~`，可自行抓包替换(开启抓包，进入拼团瓜分电力页面，寻找带有`tuan`的链接里面的`activeId=`) |
|    `HELP_AUTHOR`      |    是否给作者助力 免费拿,极速版拆红包,省钱大赢家等活动.<br>默认是     | 非必须 | 填`false`可关闭此助力 |
