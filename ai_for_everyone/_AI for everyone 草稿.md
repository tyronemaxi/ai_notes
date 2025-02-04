# AI for everyone

## What is AI ?

据估计，人工智能每年将创造 13 万亿美元的额外价值，到 2030 年，

![image-20250201105148805](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250201105148805.png)

未来会有更多的价值在软件行业之外，例如零售、电商、旅游、自动化制造等行业。

AI 实际上可以细分为两个独立的概念：

- ANI （artificial narrow intelligence）E.g., smart speaker, self-driving car web search, AI in farming and factories
- AGI （artificial geneal intelligence）Do anything a human can do

### Machine learning

- 有监督学习（Superivised Learning）

通过使用带有标签的的训练数据（从输入 A 到输入 B的映射关系）来训练模型。训练数据包括输入特征和对应的输出标签，模型通过学习这些数据来预测新输入的输出。



![image-20250203151345091](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203151345091.png)

监督学习的应用场景：

- 垃圾邮件过滤：输入的是邮件的内容，输出是判断是否为垃圾邮件（0/1）
- 语音识别：输入的是音频片段，输出的是文字转录
- 机器翻译：输入的是一种语言（英语），输出的是另外一种语言（如中文）
- 在线广告：输入的是广告信息和用户信息，输出的是用户是否会点击广告
- 自动驾驶：输入的是图像和雷达数据，输出的是其他车辆的位置。
- 制造业视觉检测：输入的是产品图片，输出是判断是否存在缺陷（如凹痕和损伤）

- 生成式 AI （Chatgpt）：输入的是文本片段，输出的是预测下一个词，通过大量的文本数据训练生成新内容



监督学习为何近年来快速发展？

- 数据的增长：互联网和计算机的普及使得可用的数据量大幅度上升。
- 神经网络和深度学习的崛起。
- 算力的提升：GPU

高性能 AI 系统的关键因素

- 大量数据：数据越多，模型性能通常越好
- 大规模神经网络：更大的模型能够更好地捕捉复杂模式
- 算力：GPU 等显卡的出现

监督学习的核心价值

- 尽管监督学习看似简单（只是构造 A -> B 的映射），但在合适的应用场景中，它能够创造巨大的经济和技术价值
- 例如，语音识别、在线广告和自动驾驶等领域的高性能 AI 系统都依赖于监督学习

### what is Data

例如房屋价格表格



数据的定义与类型

- 数据是 AI 系统的核心燃料，通常以表格（Excel）或非结构化的形式（图片/音频）存在

- 结构化数据（如房屋数据）

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203153801774.png" alt="image-20250203153801774" style="zoom:50%;" />

- 非结构化数据：图片、音频、文本

  ![image-20250203154229114](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203154229114.png)

  数据的获取方式

  - 手工标注：人工标记的数据
  - 用户行为画像
    - 用户行为（如电商记录用户价格敏感度与购买决策）
    - 机器行为（如工厂设备温度、压力-> 是否故障）
  - 下载或者合作
    - 从公开网站下载数据集（需要注意版权）
    - 与合作伙伴共享数据（如工厂提供设备历史数据）

  数据的常见误区

  - 过度投资 IT 基础设施
    - 错误：先花多年时间完善数据，再启动 AI.
    - 正确：**边收集数据边迭代**，AI 团队需早期介入以优化数据搜集策略。
  - 盲目搜集数据
    - 数据量 != 价值，需要结合 AI 团队验证数据有效性
    - 反例: 某公司收购了医疗数据却无法提取价值
  - 数据的质量
    - 错误的数据/无用的数据/标记错误的数据/缺失的数据

  数据处理的挑战

  - 数据清洗：处理错误值（如房价标记为 $0.001）、缺失值（如未知卧室数）
  - 数据类型差异：
    - 结构化数据（表格）与非结构化数据（图像、音频）需不同技术处理。
    - 监督学习适用于两者，但生成式 AI 更擅长处理非结构化数据。

  关键建议

  - 尽早与AI 团队合作：优化数据搜集的方向，结合不同的数据需求来定制化搜集数据。
  - 避免数据崇拜：数据需要和业务目标结合，而非单纯追求规模
  - 接受数据复杂性：数据天然混乱，需要通过清洗和预处理提升质量

  ### 人工智能术语

  机器学习和数据科学

  - 机器学习

    - 定义：机器学习是让电脑在不被编程的情况下，就可以自己学习的研究领域。（machine learning is the field of study 

      that gives computers the ability to learn without being explicitly programmed.）

    - 应用：实时运行的 AI 系统（如广告点击率预测、自动驾驶）

    - 核心目标：生成可自动执行任务的软件（如 24/7 服务的推荐系统。

  - 数据科学

    - 定义：通过挖掘数据来获取见解
    - 输出：商业决策支持（如幻灯片报告、产品优化建议）
    - 应用案例：发现“三卧室房屋溢价”或“翻新房屋增值 15%” 等规律

  深度学习（Deep Learning）与神经网络（Neural Networks）

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203173237661.png" alt="image-20250203173237661" style="zoom:50%;" />

  - 神经网络
    - 结构：由人工神经元组成的数学方程，输入 A （如房屋面积、卧室数）-> 输出 B (价格)
    - 类比大脑：仅受生物神经元启发

  ### 怎样成为一个人工智能公司

  互联网公司 vs 人工智能公司

  - 互联网公司
    - A/B testing
    - Short iteration time
    - Decision making pushed down to engineers and other specialized roles
  - AI 公司
    - Strategy data acquisition
    - Unified data warehouse
    - Pervasive automation
    - New roles(e.g., MLE) and division of labor

  使得一个公司擅长 AI 需要一个系统化的过程，有一个基本范式来进行：

  - 1. 启动试点项目来获得势头（Execute pilot projects to gain momentum）

  - 2. 建立一个内部 AI 团队(Build an in-house Ai team)
  - 3. 提供广泛的人工智能培训（Provide broad AI training）
  - 4. 制定一个人工智能策略（Develop an AI startegy）
  - 5. 保持内外沟通的一致, 包含从工程师到产品，投资人等等（Develop internal and external communications）

  ### 人工智能能做什么/or not

  监督学习案例

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203180254285.png" alt="image-20250203180254285" style="zoom:50%;" />

  一秒法则：Anything you can do with 1 second of thought，we can probably now o soon automate.

  一个智能客服的例子：
  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203180610277.png" alt="image-20250203180610277" style="zoom:50%;" />

  用户发送给电商公司一封邮件中描述了想要退货的申请。前者按照`一秒法则` 能直接判断该内容是否是退货申请。

  而后者需要回复道歉回执，就看起来不太可能直接通过 AI 来完成。

  如何能让你快速判断这个 AI 项目的可行性，这里有两个法则（what makes a ML problem easier）

  - learning a "simple" concept( 一秒法则 )
  - Lots of data available(大量的可用数据)

  一个自动驾驶的例子：

  - 通过捕捉前车的图片，来判断车辆的位置。

  - 通过检测人的手势行为，来判断动作意图

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203182104614.png" alt="image-20250203182104614" style="zoom:50%;" />



一个 X 射线胸片图来判断患者是否患有肺炎的例子

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203182745397.png" alt="image-20250203182745397" style="zoom:50%;" />

如果只是简单的判断是否有肺炎，是可行的，但是如果需要根据图片的内容给出准确的诊断结果描述还是比较困难

机器学习的优缺点

优点：

机器学习擅长做：

- Learing a simple concept
- There is losts of data available

机器学习不擅长：

- learning complex concepts from small amounts of data
- it is asked to peform on new types of data(使用不同类型的数据)

### 深度学习非技术性解释

一个预估短袖的销量的 AI 模型：

例如有四个输入：

- price 
- shipping cost
- marketing
- material

价格 + 运费 -> 购买力

价格 + 营销 + 原材料 -> 顾客对其质量的判断

营销 -> 认知度

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250203190003194.png" alt="image-20250203190003194" style="zoom:50%;" />

神经网络的神奇之处就是在于当你使用神经网络构建一个机器学习系统时，你只需要给他输入 A 和 B 就可以了，它自己会把中间过程弄清楚。

### 机器学习的工作流程

keys steps of a machine learning project

- collect data
- train model
  - Iterate many times until good enough
- deploy model
  - get data back
  - maintain / update model



自动驾驶的例子

![image-20250204184241817](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204184241817.png)

### 数据科学项目的工作流程

与机器学习项目不同，数据科学的输出通常是一组可操作的见解，一组能够使你以不同方式做事的洞察力，因此数据科学项目有着不同的工作流程。

- 优化一个销售漏斗（Optimize a sales funnel）

  - 1. collect data
    2. Analyze data
       1. Iterate many times to get good insights
    3. suggest hypotheses/actions
       1. Deploy changes
       2. Re-analyze new data periodically

    <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204184851382.png" alt="image-20250204184851382" style="zoom:50%;" />

### 每个工作职能都需要学习如何使用数据

- 产品经理

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204185437967.png" alt="image-20250204185437967" style="zoom:50%;" />

  

- 面试官

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204185650512.png" alt="image-20250204185650512" style="zoom:50%;" />

- 市场营销

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204185811181.png" alt="image-20250204185811181" style="zoom:50%;" />



### 如何选择一个人工智能项目

寻找你所在的行业+AI

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204191814583.png" alt="image-20250204191814583" style="zoom:50%;" />

团队头脑风暴的三个想法中的三个原则

- Think about automating tasks(自动化任务) rather than automating jobs.E.g., call center routing, radiologists.
- what are the main drivers of business value?(商业价值的主要驱动因素是什么？)
- what are the main pain points in your business?(业务中的主要痛点是什么？)

有用的建议：

You can make pocesess even without big data

- Having more data almost never hurts
- data makes some businesses (like web search) defensible.
- But with small datasets, you can still make progress



需要多少数据通常取决于你要解决的问题，不要因为在一开始的时候因为没有很多的数据就放弃。



Due dilegence on project && feasible research

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204192320526.png" alt="image-20250204192320526" style="zoom:50%;" />

Build vs. buy

- ML projecs can be in -house or outsourced
- DS projects are more commonly in-house
- Some things will be industry standard - avoid building those

对于行业通用的解决方案，我们的做法不应该是闭门造车。

### 如何与人工智能团队合作

- specify your acceptance criteria(具体的验收标准)

  <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204193110461.png" alt="image-20250204193110461" style="zoom:50%;" />

- how AI teams think about data

  - training data

  - test data

    <img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204193405593.png" alt="image-20250204193405593" style="zoom:50%;" />

Pitfall: Expecting 100% accuracy

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204193645327.png" alt="image-20250204193645327" style="zoom:50%;" />

### 人工智能团队的技术工具

AI technical tools

<img src="/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250204193920105.png" alt="image-20250204193920105" style="zoom:50%;" />





# what is machine learning

- 监督学习

推荐系统/自动驾驶/cv

![image-20250129192812337](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250129192812337.png)

算力+数据

- dataset 

  how to acquiring data - 1. manual labeling。2. from observing behaviors。3. download from websites/partnerships

- 有用的数据&&无用的数据 



## what AI can do or not

principle

1. learning a simple concept
2. Lots of data available

cannot do 
![image-20250131121425104](/Users/tyronemaxi/Library/Application Support/typora-user-images/image-20250131121425104.png)



# starting an AI project

- workflow of projects
- selecting AI projects
- oranizing data and team of projects

### example of speech 

- 1. collect data
  2. train model
     1. iterate many time until good enough
  3. Deploy model
     1. get data back maintain/update model

### key steps of a machine learing project



### Example: Optimizing a sales funnel

1. collect data
2. analyze data
   1. iterate many times to get good insights
3. suggecy hypotheses/actions



## how to choose a AI project

- what AI can do
- valuable for your business

AI 算法专家 + 业务专家

驱动商业价值的主要因素有哪些？

- think about automating tasks rather than automating jobs. E.g. call center routing, radiologists.



 



















