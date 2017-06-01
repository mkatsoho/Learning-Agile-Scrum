# The Instructor Book

Written by Michael.yg.Chen<at>gmail.com

License: [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

Give an overview of Agile Scrum via 15 commonly used terms and examples


## Survey A

- 大家谁知道Agile？ 
- 谁知道 Scrum？
- 谁经历过Scrum？
- 谁还觉得scrum有效？
- 其他的敏捷方法？

 
## Self-driving 

- 如何分配工作？
- 有的人有太闲，有的人太忙咋办？
- 你管理的人员加倍了，你咋办？（没合适的lead，哈）

类似于 “无监督的学习”
类似于 “从我做起”
其实我的体验是 ”做老大交代的事“


## Backlog
	
短期todos，长期todos，或小，或大

- 不严格标记优先级
- 不做人天的预估（待续）


## Story

例子：
	As a 运营专员，
	I want to 通过关键词快速查找到相应的一篇／偶尔多篇文章，并下线其中的一篇或者多篇，
	so as to 先发后审，以及已经出问题后的紧急处理

	包含了who， what， why，但不包括 how

- 业务层描述
- 需求描述
- 也可以是技术层次的需求描述 （UFS）


## Epic

例子：
	As a 运维专员，
	I want to 运维各种工作，如强插，置顶，推送，下线… ，
	so as to 就不用求开发同学了

巨大的story，例如Atlas


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


## Survey B

- 迭代开发可以节省人天？
- 迭代开发越到后面迭代bug会增多？
- 目前我们开放选择在什么时候重构？
- 重构是高风险的，对吗？
- bug 可以不修复，对吗？


- 迭代开发需要节省人天？更多人天，但更早防止跑偏 （例子）
- 迭代开发越到后面迭代，bug会增多？如果没有测试用例覆盖，多数如此 （据说某客户端，一把一把的bug）
- 目前我们开放选择在什么时候重构？不得不的时候。没新需求的时候。迭代的过程既是重构的过程。
- 重构是高风险的，对吗？有测试用例，咱怕啥！没测试用例，啥都怕！


## Kanban

看一个 example，改良的kanban，专利权归 Michael 所有


## Team Members

- stakeholders  （澄清epic／story）
- scrum team members 
- scrum master （了解概念，不是lead，组织3个会议，后续）

例子，屏保图配文 （承上），定义一下Epics


## Story Points

即 planning／sizing 

- 扑克游戏
- A组：狗 100
- B组：大象 100

问题：
你们API在2天后能不能上线“狐狸”这歌需求？

回答：
- 如果“狗”要2天能搞定，那么“狐狸”只要1天
- 如果“大象”要2天搞定，那么狐狸就是2小时
- 请问“狗”或者“大象”需要几天搞定？


## Velocity
	
scrum team‘s total story points per sprint

- team 成员越稳定，趋势持平略微上升
- 需要多面手
- 需要更长的backlog
- 需要把 Epic／story 解耦


## Scrum Meeting 

- planning meeting， 
从backlog选story到sprint，team member 把 story分给自己

- daily scrum meeting
what 昨天，what 今天，what 问题

- retrospection meeting
lesson learn， 正向，负向
velocity 


## Burn-down Chart

参考 Jira burn-down chart
