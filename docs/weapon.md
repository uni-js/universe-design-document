# 武器

## 1. 简介

武器是一类用于攻击角色（一般是生物）的物品。

## 2. 弓类武器

### 2.1 用户界面

当弓类武器被持有时，在用户界面中显示当前装备的箭矢以及数量。
若箭矢没有被装备，则提示未装备箭矢。

发射方向由玩家改变光标等位置来决定。

弓类武器被持有时，玩家的图形会重叠所对应弓箭的图形。
这个图形会随着发射方向的改变而旋转、平移或者翻转。

发射力度由玩家进行开始发射操作的时长决定。

### 2.2 装备箭矢

弓类武器能攻击的前提是装备了箭矢，箭矢直接放入背包，

默认装备背包的主仓容器中顺序最先的箭矢。

### 2.3 发射箭矢

操作用户界面来确定发射方向、发射力度、发射时机。

### 2.4 击退

弓类武器可以发射箭矢，箭矢会对玩家等角色造成伤害，受到箭矢的攻击会击退角色。

击退定义为，若箭矢的发射方向为 D，则玩家得到一个与 D 相反的方向的“加速度”（参考“运动”一章）。

