# 概率论问题

## 1.设置期望求取未知量，间接概率求法

### 矿工在矿井中迷失了方向，身处3个矿道交汇处，不知选择哪个矿道脱险。事实是1号矿道能脱险，2号和3号矿道只能回到原处。走完1号，2号，三号矿道花费的时间分别为3h,5h和7h。若回到起点则重新随机选择。求安全走出矿道花费的平均时间？

从概率论角度来解答这题，假设矿工走出矿井的平均时间为E(t),由于选择任意一条矿道的概率为1/3，则有

E(t)=1/3 * 3 + 1/3 * (5+E(t)) + 1/3 * (7+E(t))

E(t) = 15

## 2.浦丰投针实验
### 假设平面上
