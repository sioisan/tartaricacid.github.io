---
layout: post
title: 血魔法束灵套装降级数据说明
tags: [wiki]
description: >
  通过查看源码，对血魔法2的束灵套装降级部分进行数据说明
---

这些降级往往都会提供一些负面效果。但是提供了负面效果以后，能够给予束灵套更多的强化点数。

1. 饿殍遍野              
	会加快玩家饥饿消耗速度。额，严格意义上来说是加快了饥饿等级的消耗
  
	> 饥饿等级（foodExhuastionLevel），取值范围是从0.0到4.0，玩家的每项行动都会增加它。当饥饿等级到达4.0时，它会自动归零，并且从食物饱和度或者食物水平（当食物饱和度等于0时）减去1点。注意的是如果饱和度不足1将减为0，不会从饥饿值中扣除点数。    

	> Ref: [minecraft中文wiki饥饿词条](http://minecraft-zh.gamepedia.com/%E9%A5%A5%E9%A5%BF)

	| 等级 | 消耗点数 | 降级附加的负面效果 |
	| :--: | :------: | :----------------: |
	| 1    | -10      | 每30s饥饿等级-0.02 |
	| 2    | -20      | 每30s饥饿等级-0.04 |
	| 3    | -35      | 每30s饥饿等级-0.06 |
	| 4    | -50      | 每25s饥饿等级-0.08 |
	| 5    | -75      | 每20s饥饿等级-0.1  |

2. 残废手臂            
	你的副手槽不能用了，额，就成了摆设，顶多能放放东西而已。

	| 等级 | 消耗点数 |
	| :--: | :------: |
	| 1    | -150     |

3. 弱化挖掘             
	降低你的挖掘速度。

	| 等级 | 消耗点数 | 降低后的挖掘速度（倍数） |
	| :--: | :------: | :----------------------: |
	| 1    | -10      | 0.9                      |
	| 2    | -17      | 0.8                      |
	| 3    | -28      | 0.7                      |
	| 4    | -42      | 0.6                      |
	| 5    | -60      | 0.55                     |
	| 6    | -80      | 0.5                      |
	| 7    | -100     | 0.4                      |
	| 8    | -125     | 0.35                     |
	| 9    | -160     | 0.3                      |
	| 10   | -200     | 0.2                      |

4. 平衡失调 （平衡又失调了？快吃汇源肾宝！）            
	玩家每秒都有几率会随机乱转（老牛逼了）

	| 等级 | 消耗点数 | 随机几率 |
	| :--: | :------: | :------: |
	| 1    | -10      | 1%       |
	| 2    | -20      | 2%       |
	| 3    | -30      | 3%       |
	| 4    | -40      | 4%       |
	| 5    | -70      | 5%       |
	| 6    | -80      | 6%       |
	| 7    | -100     | 8%       |
	| 8    | -140     | 10%      |
	| 9    | -180     | 12%      |
	| 10   | -220     | 14%      |

5. 钝拙之刃          
	玩家攻击力会减少。           

	| 等级 | 消耗点数 | 减少的倍数 |
	| :--: | :------: | :--------: |
	| 1    | -10      | 0.1        |
	| 1    | -17      | 0.2        |
	| 1    | -28      | 0.25       |
	| 1    | -42      | 0.3        |
	| 1    | -60      | 0.35       |
	| 1    | -80      | 0.4        |
	| 1    | -100     | 0.5        |
	| 1    | -125     | 0.6        |
	| 1    | -160     | 0.7        |
	| 1    | -200     | 0.8        |

6. 淬火        
	你不能喝东西了，嗯，任何东西都不能喝了。

	| 等级 | 消耗点数 |
	| :--: | :------: |
	| 1    | -100     |

7. 如履寒冰           
	真是如履寒冰，你现在走起来就和在冰面上有点像。

	| 等级 | 消耗点数 |
	| :--: | :------: |
	| 1    | -50      |

8. 愈合延缓           
	玩家回血速度将会变得更慢

	| 等级 | 消耗点数 | 降低后的回血点数（倍数） |
	| :--: | :------: | :----------------------: |
	| 1    | -10      | 0.9                      |
	| 2    | -17      | 0.8                      |
	| 3    | -28      | 0.7                      |
	| 4    | -42      | 0.6                      |
	| 5    | -60      | 0.55                     |
	| 6    | -80      | 0.5                      |
	| 7    | -100     | 0.4                      |
	| 8    | -125     | 0.35                     |
	| 9    | -160     | 0.3                      |
	| 10   | -200     | 0.2                      |

9. 疲瘸之腿           
	玩家将会走的更慢。

	| 等级 | 消耗点数 | 降低后的速度（倍数） |
	| :--: | :------: | :------------------: |
	| 1    | -10      | 0.9                  |
	| 2    | -17      | 0.8                  |
	| 3    | -23      | 0.7                  |
	| 4    | -35      | 0.6                  |
	| 5    | -48      | 0.55                 |
	| 6    | -60      | 0.5                  |
	| 7    | -80      | 0.45                 |
	| 8    | -110     | 0.4                  |
	| 9    | -160     | 0.35                 |
	| 10   | -200     | 0.3                  |

10. 风暴骑兵            
	增加玩家射出箭的偏移程度。

	| 等级 | 消耗点数 | 偏移程度|
	| :--: | :------: | :-----: |
	| 1    | -10      | 0.04    |
	| 2    | -25      | 0.08    |
	| 3    | -40      | 0.12    |
	| 4    | -65      | 0.16    |
	| 5    | -90      | 0.20    |
