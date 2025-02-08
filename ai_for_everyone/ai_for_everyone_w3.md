# AI For Everyone —— week3
本文总结于吴恩达视频课程 《ai for everyone》 

[课程传送门](https://www.coursera.org/learn/ai-for-everyone/home/week/1)

[bilibili 中英文字幕](https://www.bilibili.com/video/BV1yC4y127uj?vd_source=275f6919f1e622d67ac6c138d0967924&spm_id_from=333.788.player.switch&p=17)

本周将学习如何在公司内部构建 AI 项目：
- **AI 产品的案例研究（Case studies of complex AI products）**
- **AI 项目组的角色定义（Roles iin an AI team）**
- **AI 转型手册（AI Transformation Playbook）**
- **如何开始 AI 项目的第一步（Taking your first step）**
- **主要人工智能应用领域调查**
- **主要人工智能技术调查**

## 案例学习
### 智能语音助手（Smart speaker）
如何构建一个能听懂人语，例如 “hi device” 的人工智能软件呢？

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_32.png)

**命令执行步骤**（steps to process the command）：
- 触发词唤醒（Trigger word/wakeword detection）———— "Audio -> Hey device?"
- 语音识别（Speech recognition）———— "Audio -> `tell me a joke`"
- 意图识别（Intent recognition）———— "tell me a joke"
- 执行对应功能（Excute joke）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_33.png)

- 定闹钟

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_34.png)
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_35.png)

### 自动驾驶

决定汽车驾驶的关键步骤（Steps for deciding how to drive your car）
首先汽车会接受各种传感器输入：

- image/Radar/Lidar（传感器系统）
然后会将各种数据传输给 `动作规划系统（Motion planning）`
- 汽车的行驶动作（Steer/Accelerate/Brake）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_36.png)

**关键步骤：**
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
- **机器学习工程师**（Machine Learning Engineer）
  - 职责是构建神经网络，训练神经网络，并部署
- **机器学习研究员**（Machine Learning Researcher）
  - Extend state-of-the-art in ML
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_39.png)

- **数据科学专家（Data Scientist）**
  - Examine data and provide insights
  - Make presentation to team/executive
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_40.png)

- **数据工程师（Data Engineer）**
  - Organize data
  - Make sure data is saved in an easily accessible, secure and cost effective way
-  AI产品经理（AI Product Manager）
  - help decide what to build; what's feasible and valuable
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_41.png)

### 在一个小团队展开行动

即使我们没有优秀的团队和人才，我们也能组织一个小团队，通过慢慢学习 AI 领域的知识来做成一些事情
- 1 software Engineer, or
- 1 Machine Learning Engineer/Data Scientist, or
- Nobody but yourself

## 人工智能转型计划

你如何能帮助你的公司变得更加擅长使用人工智能呢？

### 人工智能转型手册

- **第一步：获取试点项目来获得势头（Execute pilot projects to gain momentum）**
- **第二步：建立内部 AI 团队（Build an in-house AI team）**
- **第三步：提供广发的人工智能培训（Provide broad AI training）**
- **第四步：制定 AI 发展战略（Develop an AI strategy）**
- **第五步：内外部的 AI 发展宣传（Develop internal and external communications）**

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_42.png)

#### 如何开展试点项目

- 在开展一个或者多个试点项目时，我们需要考虑的是**这个项目是否更易成功而不是更有价值**（More important for the initial project to succeed rather
than be the most valuable）
- 在 **6-12 月之内展示成绩**（Show traction within 6-12 月）
- **外包 or 内部**（Can be in-house or outsourced）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_43.png)

#### 如何搭建内部团队

笔者这里给的建议是在构建初期的 AI 团队时，能**分配 AI 团队的人去对接各个业务部门的同学，然后一起合作去创造有趣的项目**。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_44.png)

#### AI 知识培训

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_45.png)

#### 制定 AI 发展战略

在进入一家公司而言，**先熟悉公司内部的业务和人员结构是很重要的，不必一开始就推行 AI**
- 战略制定的时机（Leverage AI to create an advantage specific to your industry sector）
  - AI 战略不应作为第一步，而应在企业通过试点项目、建立团队和培训后，对 AI 有更深理解后再制定。过早制定战略可能导致脱离实际的学术性策略。
- **良性的 AI 发展战略**
  - 通过更好的产品吸引更多用户，从而收集数据，进一步优化产品，形成正循环。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_46.png)

#### 数据战略

- 战略性数据获取：领先的 AI 公司擅长通过免费服务（如电子邮件、照片分享）获取数据，进而优化广告投放等商业模式。
- 统一数据仓库：将分散的数据整合到一个统一的数据仓库中，有助于 AI 工程师发现数据间的关联，提升 AI 模型的性能。

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_47.png)

#### 内外部沟通

- 投资者关系：确保投资者理解公司作为 AI 公司的价值。
- 政府关系：在高度监管的行业（如医疗、自动驾驶、金融），企业需要与政府合作，确保 AI 解决方案既能带来益处，又能保护消费者。
- 用户教育：如果产品因 AI 发生变化，用户教育至关重要。
- 人才招聘：展示 AI 成功案例有助于吸引稀缺的 AI 人才。
- 内部沟通：在 AI 转型过程中，内部沟通可以帮助缓解员工的担忧，确保顺利过渡。

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_48.png)

## 避免 AI 陷阱
### 五个常见的 AI 陷阱及应对策略
- **不要期望 AI 解决所有问题**

- **AI 虽然强大，但也有其局限性。企业应基于技术、数据和工程资源的实际情况，合理评估 AI 的能力范围。**

- **建议：在选择 AI 项目时，除了商业尽职调查，还应进行技术尽职调查，确保项目既可行又有价值。**

### 不要仅仅依赖少数机器学习工程师

- 机器学习工程师是稀缺资源，但他们无法单独为公司找到最佳的应用场景。

- 建议：**将机器学习人才与业务人才结合，跨职能合作，共同筛选出最有价值和可行的项目。**

### 不要期望 AI 项目一次成功

- AI 开发通常是一个迭代过程，可能需要多次尝试才能取得成功。

- 建议：**为 AI 项目制定迭代计划，预留足够的时间和资源进行多次实验和优化。**

### 不要照搬传统的项目管理流程

- AI 项目的规划与传统项目不同，需要根据 AI 的特点调整时间表、里程碑和关键绩效指标（KPI）。

- 建议：**与 AI 团队合作，制定适合 AI 项目的规划方式，确保目标合理且可衡量。**

### 不要认为必须拥有顶尖 AI 工程师才能开始

- 虽然顶尖人才很重要，但许多通过在线课程学习的 AI 工程师也能出色地完成项目。

- 建议：**利用现有团队开始 AI 项目，逐步壮大团队，而不是等待“超级明星”工程师的加入。**

### 总结与鼓励
尽早开始：AI 项目的成功需要不断积累经验，第二个项目会比第一个更好，第三个项目会比第二个更好。重要的是迈出第一步。

避免陷阱：通过避开上述五个常见陷阱，企业可以在 AI 领域领先于许多竞争对手。

下一步：在接下来的视频中，Andrew Ng 将分享一些具体的 AI 入门步骤，帮助大家快速启动 AI 项目。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_49.png)
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_50.png)

## 主要人工智能应用领域调查

### 计算机视觉（Computer Vision）

- 图像识别（Image classification/Object recognition）
- 物体检测（Object detection）
- 图像分割（Image segmentation）
- 追踪算法（Tracking）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_51.png)

### 自然语音处理（Natural Language Processing）

NLP 指的是 AI 理解自然语音的能力
- 文本分类（Text classification）
- 信息处理（Information Retrieval）
  - E.g., web search
- 命名实体识别（Name entity recognition）
- 机器翻译（Machine translation）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_52.png)

- 其他：解析&&语音部分标准技术（parsing, part-of-speech tagging）

### 语音处理（Speech）

- Speech recognition(speech-to-text)
- Trigger word/wakeword detection
- Speaker ID
- Speech synthesis(text-to-speech, TTS)

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_53.png)

### 机器人

- 感知（perception: figuring out what's in the world around you）
- 运动规划（Motion planning: finding a path for the robot to follow）
- 控制（Control: sending commands to the motors to follow a path）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_54.png)

### 机器学习在结构化数据中的应用

机器学习在结构化数据中的应用：
- 除了非结构化数据（如图像、音频、文本），机器学习也广泛应用于结构化数据（如表格数据），尽管后者较少被媒体报道，但其经济价值巨大。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_55.png)

## 主要人工智能技术调查

### 非监督学习（Unsupervised learning）

核心思想：无监督学习不依赖于标注数据（即没有明确的输入和输出对），而是让算法从数据中自动发现有意义的结构或者模式。
例子：
- 聚类（clustering）：超市通过分析顾客购买薯片的数据，自动将顾客分为两类：一类是购买大量低价薯片的大学生，另一类是购买少量高价薯片的职场人士。这种市场细分可以帮助制定不同的营销策略。
- google cat: 通过无监督学习算法分析大量 youtube 视频，AI 自动发现了猫这个概念，尽管没有提前告知要寻找猫。
优势和挑战：无监督学习不需要大量的标注数据，但目前其经济价值远低于监督学习。未来可能通过突破性进展，使 AI 更接近人类的学习方式。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_56.png)

### 迁移学习（Transfer learning）

- 核心思想：将一个任务中学到的知识迁移到另一个相关任务中，尤其是在目标任务的标注数据较少时。

- 典型应用：
例如，自动驾驶汽车已经学会了检测普通汽车，但在新城市中需要检测高尔夫球车。迁移学习可以利用已有的汽车检测知识，快速提升高尔夫球车检测的性能。
优势：迁移学习在计算机视觉等领域非常有效，能够显著提升模型性能，尽管它并不常被媒体报道。

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_57.png)


### 强化学习（Reinforcement Learning）

核心思想：通过奖励和惩罚机制训练AI，使其逐步学会如何最大化奖励。
典型应用：
- 机器人控制：例如，斯坦福的自主直升机通过强化学习学会飞行。AI在模拟器中尝试飞行，成功时获得正奖励，失败时获得负奖励，最终学会复杂的飞行动作。 
- 游戏：强化学习在围棋、象棋、电子游戏等领域表现出色，例如AlphaGo。
- 挑战：强化学习通常需要大量数据或模拟环境，目前其经济价值仍低于监督学习，但未来可能有突破性进展。

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_58.png)

### 生成对抗网络（GANs）

核心思想：通过两个神经网络（生成器和判别器）相互对抗，生成高质量的新数据。

典型应用：

图像生成：例如，NVIDIA团队使用GANs生成从未存在过的名人照片。

娱乐行业：GANs被应用于计算机图形、游戏和媒体内容生成。

潜力：GANs在生成逼真图像和内容方面具有巨大潜力，正在推动娱乐行业的创新。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_59.png)

### 知识图谱（Knowledge Graph）

核心思想：构建大规模的结构化数据库，存储实体（如人、地点、事物）及其之间的关系。

典型应用：

搜索引擎：例如，搜索“达芬奇”时，右侧显示的信息面板就是基于知识图谱。

企业应用：许多公司构建了关于电影、酒店、机场等领域的知识图谱，用于快速检索和分析。

现状：尽管知识图谱在经济上创造了巨大价值，但学术界对其研究相对较少。

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_60.png)

