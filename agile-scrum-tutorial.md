# The Instructor Book

Written by Michel.yg.Chen at gmail.com

License: [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

Give an overview of Agile Scrum via 15 commonly used terms and examples


## Survey A

- 大家谁知道Agile？ 
- 谁知道 Scrum？
- 谁经历过Scrum？
- 谁还觉得scrum有效？
- 其他的敏捷方法？

下面只讲 Agile Scurum (这是一种敏捷方法)


# Part 1 - Agile Scrum 的核心思想

## Game 1


组                  A           B           C           D           E
-------------------------------------------------------------------------------------
组长             
组员
完成任务用时
重新执行用时


- 组长测试移动指令
- 发放任务书给组长 (准备胶带和白纸)
- 组长计时,游戏开始


问题1   参赛者的感想
问题1   如果多个组员呢?
问题2   如果倒退着走呢?
问题3   重新执行呢?


## Game 1 解读

        - 过程: 椅子(障碍),很多人(干扰),错误指令(错误的决定),走错了(错误的执行)
        - 为什么重新执行会快辣么多?


## 敏捷的核心思想 

Agile的核心是:自主工作/自我驱动. 怎么自主工作呢?

- 如何分配工作？
- 有的人有太闲，有的人太忙咋办？
- 你管理的人员加倍了，你咋办？（没合适的lead，哈）



# Part 2 - 关于任务

## Backlog

短期todos，长期todos，或小，或大

- 不严格标记优先级
- 不做人天的预估（待续）
- 项目整体的backlog, 本周的backlog


## User Story

例子：
    "作为" 控制人员
    "我要" 发送遥控指令,控制他做各种动作
	"以便/为了" 安照我的任务需求书,实现相关的某工作

	包含了who， what， why，但不包括 how

- 业务层描述
- 需求描述
- 也可以是技术层次的需求描述 （UFS）

 
## Epic

例子：
	As a 运维专员，
	I want to 运维各种工作，如强插，置顶，推送，下线… ，
	so as to 就不用求开发同学了

巨大的story，例如"地面系统"的六大子系统, 可以看做是6个Epic



## Kanban

看一个 example，改良的kanban，专利权归 Michael 所有



# Part 3 - 关于时间

## 原型化和瀑布式 开发方法

什么是瀑布式的开发? 需求 > 设计 > 研发 > 测试 > 投产

什么是原型化的开发? 每个迭代都是瀑布式的(比如3个月一个迭代), 每个迭代都可以投产/可用. 

原型化开发的例子: 互联网App, 机器人


方面                瀑布式          原型化          
-------------------------------------------------
开发风险控制
总的工作量          高/低?          高/低?
开发总成本
可管理(可控)
可计划(何时完成)
质量可控            


延伸1: 关于全栈
延伸2: 全栈可行吗


## Sprint

即迭代周期，发布可以使用的应用，真的发布
1 month, 2 weeks, 1 week,  or 1 day

- 挑选story - by scrum team
- 评估story的工作量 （待续）
- 自选story并完成

- 可能会分拆 大的story
- 可能会增加依赖的story
- 完成一个story，意味着可以上线，不是可以测试
- 对于每个story／发布，全部测试用例都要pass


## Game 2

无单位,评估一下他们有多重, 5人一组

小组成员要达成一致

仅使用下面不含单位的数字: 

0，1， 2， 3，5，10，15，30，50，100，150，300，500，1000，infinity



## Game 2 continue

- 猫
- 蚂蚁
- 鲸鱼
- 马


## Game 2 解读

前提: 在研发工作中 (不是生产工作)

现象: 

- 对工作量的评估, 很难精细量化, 没有工作量, 就没法预估完成时间
- 即使"计算"出了工作量, 完成时间也不可信

那么我们怎么办

- 估计工作量的量级, 并(容易)达成一致
- 使用Agile Scrum的方法, 选择/做事/预估



## Story Points

即 planning／sizing 

- A组：狗 100
- B组：大象 100


问题：
你们组在2天内能不能上线“猫”这歌需求？

回答：
- 如果“狗”要2天能搞定，那么“猫”只要1天
- 如果“大象”要2天搞定，那么“猫”就是0.5小时
- 请问“狗”或者“大象”需要几天搞定？



## Velocity
	
scrum team‘s total story points per sprint

- team 成员越稳定，趋势持平略微上升
- 需要多面手
- 需要更长的backlog
- 需要把 Epic／story 解耦



## Burn-down Chart

参考 Jira burn-down chart


# Part 4 - 关于人和会议

## Team Members

- stakeholders  （澄清epic／story）
- scrum team members 
- scrum master （了解概念，不是lead，组织3个会议，后续）

例子，屏保图配文 （承上），定义一下Epics


## Scrum Meeting 

- planning meeting， 
从backlog选story到sprint，team member 把 story分给自己

- daily scrum meeting
what 昨天，what 今天，what 问题

- retrospection meeting
lesson learn， 正向，负向
velocity 

