# 最强配装计算器

## 白龙青魔最强配装：
https://gearing.ffsusu.com/?5uEmyXoDyLNkpJnV6mKzzWCePMjGieSA7FFih8rFNDVfQea

## 计算方式
每威力伤害期望 ÷ GCD时间
遍历所有装配选出最大值
数值计算方式抄的Asvel师傅的https://github.com/Asvel/ffxiv-gearing

一开始我准备在浏览器控制台用.click()调用方式遍历最强装备，但1.26e14次运算浏览器承受不住
然而我对Node.js不是很熟
所以直接用python改造了一个遍历脚本

虽然输入输出写的和屎一样，但数值没什么问题

结果前十位是装备和食物序号

0为改良型斯卡艾瓦装备

1为欧米茄装备

2为幻象装备

食物

0为贤人汉堡

1为南瓜浓汤

2为无花果饼干

3为萨维奈奶茶

后四位是魔晶石数量

第11位是暴击

第12位是信念

第13位是直击

第14位是咏唱

计算结果如图
![计算结果](https://github.com/GoodJob567/ffxiv-best-gearing/blob/main/res.PNG)

如需每威力伤害期望最大值（不计算GCD）

将calc函数的avg_damange部分改为damage即可

其他职业需要大改，暂时没时间搞，毕竟光这一个程序我就跑了11个半小时。。。
