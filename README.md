# 姓名大乐斗
> 姓名大乐斗——欢乐联机小游戏（VB版）

## 更新日志
### 姓名大作战 1.0
* 游戏内容：输入两个人的姓名，即可进行姓名PK。

* 有六项属性值：
生命值，攻击，防御，速度，命中，运气。
除了运气，其他5项属性每个姓名都有唯一的属性值相匹配。

* 目前只支持输入中文名。

* 有三项特殊技能：九阳神功，降龙十八掌，快速治疗。

* 具体内容，大家玩玩就知道啦~

欢迎各位提出宝贵意见，提交BUG，升级意见欢迎投稿邮箱：gx-deng@163.com。另外欢迎联系QQ：361411192

创作日期：2014.4.5

### 姓名大作战 1.1
更新内容如下：

1. 修复了速度属性值可能为0的BUG
2. 修复了运气值相等时无法开始游戏的BUG
3. 优化了游戏界面
4. 增加了调整游戏速度的按钮
5. 增加了作弊器
6. 增加了复位键
    
至于增加新的技能，等下个版本再吧！这个版本还是遵循网页传统版本做的，贸然增加新的东西进去不但可能破坏游戏平衡性，还会引来不必要的BUG。

谢谢游戏！

更新日期：2014.4.6

### 姓名大作战 1.2
更新内容如下：

1. 优化了游戏页面，删除了一些多余的按钮
2. 修改了战斗先手系统，融入了速度属性值因素
3. 修改了游戏速度按钮
4. 优化了作弊器
5. 降低触发“垂死挣扎”的条件：触发血量上调至15
6. 修复了text控件可编辑的BUG
7. 发现了“降龙十八掌”中的巨大BUG，删除了此项技能
8. 丰富了提示系统，并添加了登录窗口 (用户名：Airing 密码：123)
9. 增强了“快速治疗”回复的最大生命值（由原来的20上调至30）
10. 增加了“吸星大法”，可以吸收对方生命值和属性值

此次修改之后游戏算是成型了，新添加“吸星大法”或许有些BT，会在以后慢慢调整的，另外增加恢复HP系统是为了变相削弱攻击力属性。在测试中，发现攻击力过于逆天，有些姓名的攻击可以相差到100点，以至于秒杀，毫无游戏观赏性。伤害计算公式较为合理，所以只能够通过技能来增加伤害。另外，原来的“降龙十八掌”很鸡肋，初期释放过于逆天，后期释放相当于没放，运气成分过大，所以将其删除。今后会就持续游戏做出调整，比如增加姓名的HP、增加防御或者削弱攻击来达到持续战斗的目的。下个版本会融入命中率参数。

有任何新的游戏建议请联系本人，谢谢支持！

更新日期：2014.4.9

### 姓名大作战 1.3
更新内容如下：

1. 优化了登陆窗口，增加了登录系统（系统试用账号：2014612，密码：222222）
2. 增加了注册系统，用户名与姓名关联，一人一号
3. 增加了密码找回系统
4. 增加了管理员系统
5. 削弱了“吸星大法”，削弱释放几率，限时使用次数                        （由原本的47.5%下调为7%，全场限制施放3次）
6. 增加了新技能“八门遁甲”
7. 增强了“九阳神功”，取消了施放失败的情况，增强了技能威力，释放几率大幅增加（由原本下降最大属性10点，上调为15点，释放几率由2.5%升为15%）
8. 增强了“快速治疗”，释放几率大幅增加（由原本的2.5%上调至10%）
9. 增强了普通攻击，基础攻击上调，释放几率增加（基础攻击最大值由10点上升到30点，释放几率由47.5%上调至60%）
10. 修复了连续与同一人作战产生相同作战过程的BUG
12. 增加了胜场显示标签


* 新技能介绍：八门遁甲，增加自身属性值300~400点，自使用起，三个回合未解决战斗，则施放者功力枯竭而死，全场使用次数上限为1次，释放几率为5%。

更新中断了两个月，其实是在弄别的游戏，这次将技能大改动，削弱了上个版本很BUG的吸星大法。吸星大法本身效果BT，然后释放几率高达50%，所以两个人来回吸，你吸我一口我吸你一口，打个三五分钟都无法结束战斗。故本版本从几率和施放上限上削弱了吸星大法。本版本在增加普攻几率的同时，通过增加破甲基本攻击，削弱了高防御属性的姓名。平衡了各个技能的出现几率。最主要的是增加了数据库，做出登录系统，采用一人一号制，为未来的更新打下的基础。
          
更新日期：2014.6.13

### 姓名大乐斗 1.4
更新内容如下：

1. 《姓名大作战》正式更名《姓名大乐斗》
2. 加密了数据库
3. 增加了人物等级和技能等级系统
4. 增加了金钱系统
5. 增加了属性窗口
6. 增加了显示失败场次
7. 增加了商店系统，并引入新物品：小红药
8. 增加了物品系统，加入新物品“小红药”和“复活药”
9. 增加了新技能“金蝉脱壳”
10. “垂死挣扎”更名为“回光返照”
11. 修复了使用八门遁甲功力枯竭身亡不算失败的BUG
12. 修复了一方攻击比另一方防御高的时候，普攻有几率给对方加血的BUG
13. 修复了可以输入不规范对手名的BUG
14. 将命中属性更名为敏捷属性
15. 增加了游客试玩界面（v1.3版本）
16. 增加了新副本——试炼之塔
17. 增加了乐斗模式

新物品介绍：

> 小红药：限试炼之塔使用，售价100/个，效果HP+50

> 复活药：限试炼之塔死亡时使用，目前只有通关试炼之塔才可获得，死亡时原地满状态复活

新技能介绍：

> 金蝉脱壳：HP降为0时有几率以一定血量复活，每人限用1次

> Lv1：触发几率5%，复活后血量20

> Lv2：触发几率6%，复活后血量30

> Lv3：触发几率7%，复活后血量40

新副本介绍：

> 试炼之塔，共十层，守塔人为教技十男子。挑战过程中可以使用物品，挑战过程中状态不会回复，一旦挑战失败便会掉到第一层。通关奖励：金币5000，小红药x10，复活药x1

新模式介绍：

> 乐斗模式，节操无下限，血量无上限！！取消等级系统，所有角色血量上限扩大20倍，八门遁甲释放几率上升为20%，并且取消限制使用次数，使用之后也不会死亡！！！金蝉脱壳触发几率上调为50%，取消限制使用次数，复活血量升为100~300！！九阳神功威力提升三倍！！尽情疯狂的打架吧！！

人物等级介绍：
```
Lv1：胜场0~2 
Lv2：胜场3~9 
Lv3：胜场10~19 
Lv4：胜场20~
```

技能等级介绍：（主动技能的释放几率不会随等级变化）
```
破甲攻击：
Lv1：伤害值0~30
Lv2：伤害值5~30
Lv3：伤害值5~35
九阳神功：
Lv1：属性下降值1~15
Lv2：属性下降值2~17
Lv3：属性下降值3~20
八门遁甲：
Lv1：属性提升值300~400
Lv2：属性提升值320~420
Lv3：属性提升值340~440
快速回复：
Lv1：治疗值0~30
Lv2：治疗值10~40
Lv3：治疗值20~50
吸星大法:
Lv1：吸收比率10%
Lv2：吸收比率11%
Lv3：吸收比率12%
回光返照：
Lv1：属性提升值0~10，触发血量上限15
Lv2：属性提升值2~15，触发血量上限17
Lv3：属性提升值5~20，触发血量上限20

```

试炼之塔NPC介绍：
```
第1层：刘杰容——50，20，10，15，14
第2层：张荣佳——100，50，10，42，41
第3层：赵俊杰——2500，0，0，0，0
第4层：陈谊明——300，100，20，50，50
第5层：黄晓剑——100，300，100，50，50
第6层：赖鹏津——2000，0，500，0，0
第7层：梅震坤——500，200，200，50，50
第8层：缎嘉文——300，200，100，5000，50
第9层：范振威——3000，100，200，50，50
第10层：邓国雄——5000，500，500，500，500
```

经过几天几夜的更新，终于迎来了《姓名大乐斗1.4》，这次改动是几次来最大的，加入了新技能，副本系统，金钱系统，等级系统，乐斗模式，游客模式，物品系统，商店系统~~哇塞，居然改了这么多！嗯，努力往全球第一发展，争取游戏越做越大，玩家越来越多！！接下来会丰富物品系统和副本，推出越来越多的新模式，加入更多的新技能！！动画版是下一个大目标，在动画版做出来之前先慢慢丰富游戏内容，平衡游戏，增加游戏可玩度！之后的大目标的实现联网PVP对战，相信不久的将来，呈现给大家的是全新的《姓名大乐斗》！谢谢支持！

更新日期：2014.6.15

### 姓名大乐斗 1.5
更新内容如下：

1. 支持联机PVP，所有注册资源共享
2. 新增了擂台战模式，只要打赢了擂主就能成为擂主，每次挑战消耗100金币，成为擂主有丰厚奖励！(金币x200，复活药x1)
3. 新增了联机对战模式，只要输入对方的ID便能够PK
4. 降低了小红药的售价，从200金币/个改为100金币/个
5. 试炼之塔进入需要购买门票——100金币/次
6. 试炼之塔不再触发八门遁甲
7. 提高试炼之塔的奖励制度（第三层之后每层奖励200金币，并且回复300HP，通过之后复活药奖励改为3个）
8. 新增了更新检查系统


经过几天几夜的更新，终于迎来了《姓名大乐斗1.5》，这次最重大的改动是可以联网了！！没错，新增的决斗场和擂台战绝对可以让玩家们感受到竞技的乐趣。上个版本关于试炼之塔的BUG已经修复，比如可以无限刷“刘杰容”来刷金币刷等级，莫名其妙触发八门遁甲而死的⋯⋯增加了门票收费制度的同时也丰富了奖励制度。嗯，差不多就是这样。另外新增了更新检查，有更新会提示的，暂时无法做到自动更新，注意关注我的微博，会有更新说明的。另外，招美工，为2.0版本做准备！谢谢支持！

微博：[Airing](http://weibo.com/601241434)
                  
更新日期：2014.6.17
