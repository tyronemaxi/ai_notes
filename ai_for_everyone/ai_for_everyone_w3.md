# AI For Everyone —— week3
本文总结于吴恩达视频课程 《ai for everyone》 

[课程传送门](https://www.coursera.org/learn/ai-for-everyone/home/week/1)

[bilibili 中英文字幕](https://www.bilibili.com/video/BV1yC4y127uj?vd_source=275f6919f1e622d67ac6c138d0967924&spm_id_from=333.788.player.switch&p=17)

本周将学习如何在公司内部构建 AI 项目：
- AI 产品的案例研究（Case studies of complex AI products）
- AI 项目组的角色定义（Roles iin an AI team）
- AI 转型手册（AI Transformation Playbook）
- 如何开始 AI 项目的第一步（Taking your first step）
## 案例学习
### 智能语音助手（Smart speaker）
如何构建一个能听懂人语，例如 “hi device” 的人工智能软件呢？
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_32.png)
命令执行步骤（steps to process the command）：
- 触发词唤醒（Trigger word/wakeword detection）———— "Audio -> Hey device?"
- 语音识别（Speech recognition）———— "Audio -> `tell me a joke`"
- 意图识别（Intent recognition）———— "tell me a joke"
- 执行对应功能（Excute joke）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_33.png)

定闹钟
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_34.png)
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_35.png)

### 自动驾驶
决定汽车驾驶的关键步骤（Steps for deciding how to drive your car）
首先汽车会接受各种传感器输入：
- image/Radar/Lidar
然后会将各种数据传输给 `动作规划系统（Motion planning）`
- 汽车的行驶动作（Steer/Accelerate/Brake）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_36.png)

关键步骤：
- car detection（车辆检测）
- Pedestrian detection(行人检测)
- Motion planning(运动规划)
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_37.png)

除了行人检测和车辆检测，还有很多传感器和器件：
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_38.png)

## 人工智能团队的重要角色
从上述我们可以发现，对于实现一个 AI 产品，我们可能需要一个庞大的人工智能团队，像这样的大型人工智能团队需要哪些角色和职责呢？
通过这里的介绍，让我们初步对 AI 团队有一个清晰的认识

### 相关角色
- 软件开发工程师（Software Engineer）
- 机器学习工程师（Machine Learning Engineer）
  - 职责是构建神经网络，训练神经网络，并部署
- 机器学习研究员（Machine Learning Researcher）
  - Extend state-of-the-art in ML
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_39.png)

- 数据科学专家（Data Scientist）
  - Examine data and provide insights
  - Make presentation to team/executive
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_40.png)

- 数据工程师（Data Engineer）
  - Organize data
  - Make sure data is saved in an easily accessible, secure and cost effective way
-  AI产品经理（AI Product Manager）
  - help decide what to build; what's feasible and valuable
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_41.png)

### 在一个小团队展开行动
- 1 software Engineer, or
- 1 Machine Learning Engineer/Data Scientist, or
- Nobody but yourself

## 人工智能转型计划
你如何能帮助你的公司变得更加擅长使用人工智能呢？

### 人工智能转型手册
- 第一步：获取试点项目来获得势头（Execute pilot projects to gain momentum）
- 第二步：建立内部 AI 团队（Build an in-house AI team）
- 第三步：提供广发的人工智能培训（Provide broad AI training）
- 第四步：制定 AI 发展战略（Develop an AI strategy）
- 第五步：内外部的 AI 发展宣传（Develop internal and external communications）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_42.png)

#### 如何开展试点项目
- 在开展一个或者多个试点项目时，我们需要考虑的是这个项目是否更易成功而不是更有价值（More important for the initial project to succeed rather
than be the most valuable）
- 在 6-12 月之内展示成绩（Show traction within 6-12 月）
- 外包 or 内部（Can be in-house or outsourced）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_43.png)

#### 如何搭建内部团队
笔者这里给的建议是在构建初期的 AI 团队时，能分配 AI 团队的人去对接各个业务部门的同学，然后一起合作去创造有趣的项目。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_44.png)

#### AI 知识培训

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_45.png)
