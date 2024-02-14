# <span><h1 style = "font-family: garamond; font-size: 40px; font-style: normal; letter-spcaing: 3px; color :#fe346e; border-radius: 100px 100px; text-align:center"> 见鬼作业助手第一版发布！</h1></span>
作业巨多，我懂!

课设更多，我懂!

论文，实验报告做不完，我都懂!
### 就让见鬼作业助手来拯救你

## 见鬼作业助手 （Hustwork Ai Agent）: 你的作业神器！
使用GPT4，定制化作业助手。

联系作者邮箱：[email](mailto:huangjy6666@gmail.com)

（目前赞助通道暂未开通）

## 目录

- [作者信息](#不合理作业助手-hustwork-ai-agent-你的作业神器)
- [目录](#目录)
- [功能介绍](#功能介绍)
- [兼容性](#兼容性)
- [命令](#命令-command)
- [命令详解](#命令详解)
  - [/config](#config-自定义用户信息)
  - [/plan](#plan-输入任务要求)
  - [/start](#start-开始任务)
- [可自定义项目](#自定义项目)

## 功能介绍
1. 定制个人信息，专业化完成需求
2. 协助完成作业、课设、论文、实验报告等。能够直接输出代码。

## 兼容性
目前只兼容GPT4，开放code interpreter进行数值计算和代码运行。暂不开放Daile3

## 产品导航
点击[这里](https://chat.openai.com/g/g-86LEMyAI0-homework-ai-agent) 输入 “/hello”使用产品！


## 命令 Command
1. /config <~CONFIGURATION>: [自定义用户信息](#config-自定义用户信息)
2. /plan <topic>: 输入需要见鬼作业助手完成的任务
3. /start: 见鬼作业助手开始执行任务
4. /config_advice: 打开自定义用户指南
5. /continue ： 继续生成后续内容
6. /ask ~question: 提出问题

## 命令详解
### /config 自定义用户信息
改变~CONFIGURATION自定义用户信息。
- 可以为自然语言:
    /config <我是一个大学生，想要完成一个Matlab课设>

- 也可以是伪代码：
    /config <depth = undergraduate， course = Matlab， language = Chinese>
可自定义的项目为：[可自定义项目](#自定义项目)

### /plan 输入任务要求
- 直接输入需求即可：/plan<在我们的周边有一家配件厂，据我们得知，该厂为装配线生产若干种部件时因更换要付生产准备费（与生产数量无关），同一部件的产量大于需求时因积压资金、占用仓库要付贮存费。
模型假设为了处理的方便，考虑连续模型，即设生产周期T和产量Q均为连续量。根据问题性质，我们作如下假设：1.	产品每天的需求量为常数r；2.	每次生产准备费为c1，每天每件产品贮存费为c2；3.	生产能力为无限大（相对于需求量），当贮存量降到零时，Q件产品立即生产出来供给需求；4.	假设允许缺货，每天每件产品缺货损失费为c3，但缺货数量需在下次生产（或订货）时补足。
仿真要求  根据上述假设进行系统建模与仿真，系统输入为需求量常数r，每次生产准备费用c1，每天每件产品储存费c2，每天每件产品缺货损失费为c3，生产周期T和产量Q。系统输出为每天平均C。要求有输入、输出界面及仿真过程。>

  */plan阶段只做内容分析，不做具体求解*    

### /start 开始任务
- 当对/plan给出的分析，输入/start开始详细求解

## 自定义项目：
#### Depth:
    ["Elementary (Grade 1-6)", "Middle School (Grade 7-9)", "High School (Grade 10-12)", "Undergraduate", "Graduate (Bachelor Degree)", "Master's", "Doctoral Candidate (Ph.D Candidate)", "Postdoc", "Ph.D"];

#### Communication-Style:
    ["Formal", "Textbook", "Layman", "Story Telling", "Socratic"]; 
#### Reasoning-Framework:
    ["Deductive", "Inductive", "Abductive", "Analogical", "Causal"]; 
#### Language: 
    [any];
#### Course: 
    [any];
#### Require-Code: 
    [True, False];