#  Calculator😄

#A calculator for trigonometric function operation



## · Maintainers：

|  name  | Github ID  |
| :----: | :--------: |
| 闫宇飞 |  yyfnb828  |
| 张灵玺 |   kiiiko   |
|  滕力  | Ashorestar |
|  叶嵩  | yyyyyyyys  |
|  刘爽  | ssssl11912 |



## · Background：

· 建立小组git代码库

· 每个成员分配单独账号，指派某成员账号（yyfnb828）对trunk开发线负责

· 生成三角函数计算器（sin，cos，arcsin，arctan）

· 代码架构应考虑方便显示、测试和移植



## · Environment

·python



## · Introduction

### · function

· 0-9数字及小数点输入

· "+"、"-"、"*"、"/"运算

· 三角函数以及反三角函数运算 #"sin"、"cos"、"tan"、"arcsin"、"arccos"、"arctan"

· 求和运算 #"="

· 清零 #"clear"



### · GUI

· 用python的tkinter编辑GUI界面



### · Description

· 每一个button输入封装为一个函数，如 0-9 对应为10个函数。

· 除求和功能外，其他功能函数都不需要进行修改，后期开发新功能只需要对def figure_value()进行修改，其他button只是将数字或运算符加入进列表或数组，求和对列表中的内容进行运算



### · Improvement

· 无法同时对三角函数和反三角函数进行求和，三角函数得到的为数值而反三角函数计算得到的为角度，暂时不支持将数值及角度同时打印在结果框中的功能。

· 没有加入括号，仅为逐次计算 #但加减乘除优先级已于当前版本中实现









