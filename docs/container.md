# 容器

## 1. 简介

容器是一个用于装载物品的游戏对象，一般可以存在于背包、箱子等对象中，并且可以拥有一个或多个容器。

## 2. 容器的容量

容器的容量是一个数值，容器中所有存放的物品的`重量`乘以它们对应的`数量`得到的结果不得大于容器的容量。

若即将放入容器的物品计算的重量会使得容器超出容量，则该放入容器的操作会被拒绝。

不同的容器，可能有不同的容量。

## 3. 库存的容器

一个玩家拥有一个玩家库存(Inventory)。

玩家库存拥有两个容器，分别称作：背包容器，快捷栏容器。

> 对应现实中的背包，有主仓和快取的区域。

库存的背包容器，容量为 30。

库存的快捷栏容器，容量为 10。

> 快捷栏容器拥有特殊的功能，并且有对应的用户界面。关于快捷栏的定义，请参照“快捷栏”一章。

## 4. 箱子的容器

箱子是通过各种材料或物品制作出来的，可以放置在地图中。

每个箱子拥有一个容量为 50 的容器。
