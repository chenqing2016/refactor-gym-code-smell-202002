# 重构线上练功房代码坏味道
本项目为ThoughWorks内部【敏捷工程实践系列】之「重构」线上练功房代码块味道练习作业基础代码库


目的：

1. 简化课后练习的基础工作量。

## 开发环境
 - JDK1.8
 - JUnit 5
 - Gradle 5.2.1


## 作业说明

每个小组的组长将此项目Fork到自己的GitHub账号下，然后为小组成员添加为协作成员，小组内部在一个代码库上工作。


### 作业1 - 见码识味
在`cc.xpbootcamp.code_smell_recognise`package下有编号 `$01 ~ $24`共24种坏味道，每个人阅读这24种坏味道，并识别出他们分别是什么坏味道，并将答案在[思特沃克学习平台](https://school.thoughtworks.cn/learn/program-center/student/index.html#/program/305/introduction)上提交。提交格式以Markdown的格式案例如下：


| 编号 | 坏味道名称 | 腐烂点 |
|:-------------|:---------------|:-------------|
| $1 | Long Method | `OrderReceipt.printReceipt()` |



#### 作业要求
- 每个小组的组长将此项目Fork到自己的GitHub账号下，然后为小组成员添加为协作成员，小组内部在一个代码库上工作。
- 每个人依次补全24种坏味道，将表格提交到系统中对应的题目。


### 作业2 - 闻味寻码
在`cc.xpbootcamp.code_smell_kit`package下有24种坏味道的`package`，目前每个坏味道都标注了名称，并且是空的package。

小组组长在小组内部组织分工，小组成员共同完成寻找24中代码坏味道的案例，案例从你们平时遇到的项目中去寻找，寻找到能够突出对应坏味道的代码块即可，然代码块放入对应的坏味道package中。

#### 作业要求
- 每个小组的组长将此项目Fork到自己的GitHub账号下，然后为小组成员添加为协作成员，小组内部在一个代码库上工作。
- 坏味道代码片段不能是出自`cc.xpbootcamp.code_smell_recognise`中的代码。
- 代码片段使用注释标注说明坏味道的腐烂点

