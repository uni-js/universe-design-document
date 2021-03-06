# 物品

## 1. 介绍

物品是一类可以被持有、被使用、被佩戴、被丢弃的游戏对象。

存在于背包（参见背包章节）中的，物品允许在各个容器（参见容器章节）之间流动。

## 2. 物品的类型

|序号|物品名|分类名|重量|耐久类型|用途简介|
|-|-|-|-|-|-|
|1|稿子|工具类|2|耐久进度|敲击石头等砖块,并使得砖块减少耐久,获得碎石等物品|
|2|石刀|工具类|1|耐久进度|用来切割生物皮肤，并得到脂肪、毛皮等物品|
|3|火把|工具类|2|耐久进度|火把可以照亮周围的地面，持有时会一直损耗火把的耐久|
|4|熔炉|工作台类|5|不显示耐久|使用后在对应位置生成一个熔炉实体，可以被操作|
|5|石制工作台|工作台类|5|不显示耐久|工作台可以显示更多的合成配方|
|6|木制弓|武器类|2|耐久进度|木制弓是一种远程射击武器|
|7|树枝|材料类|0.1|耐久数量|树枝可以用于制作箭矢等材料|
|8|木质箭矢|材料类|0.1|耐久数量|将树枝的头部削尖，作为箭矢，伤害较低|

> 分类名仅用于为各种物品分类，游戏实现中可以不区分这些种类。

## 3. 物品的制作

玩家自己在没有工作台的时候可以制作一部分物品

## 4. 物品的使用

使用物品，指的是玩家进行 `使用物品` 操作，当前快捷栏持有的物品对环境产生作用的这一过程。

## 5. 物品的持有

`持有物品`，指的是玩家切换快捷栏，则快捷栏的当前物品被持有。

## 6. 武器类物品

武器类物品是一类用于攻击角色（一般是生物）的物品。

武器类物品在持有时，有可能显示特殊的用户界面，

详细的武器类物品定义，参考"武器"一章。