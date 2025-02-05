# AI For Everyone —— week2
本文总结于吴恩达视频课程 《ai for everyone》 refs: https://www.coursera.org/learn/ai-for-everyone/home/week/1

bilibili: https://www.bilibili.com/video/BV1yC4y127uj?vd_source=275f6919f1e622d67ac6c138d0967924&spm_id_from=333.788.player.switch&p=17 [toc]
## 介绍

## 如何开展 AI 项目（Building AI projects）
- AI 项目的工作流程（Workflow of projects）
- 如何选择一个正确的项目（Selecting AI projects）
- 如何为这个项目组织团队和项目组（Organizing data and team for the projects）

## AI 项目的工作流（Workflow of projects）
### 语音助手
我们用一个例子来说明该工作流，例如如何构建一个语音助手（smart speaker）
- 1. collect data
例如当收集到足够多的数据后，例如许多的语音数据。
- 2. Train model
    Iterate many times until good enough（反复迭代）
- 3. Deploy model
    Get data back（数据反馈）
    Maintain / update model（模型升级）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_18.png)

### 自动驾驶
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_19.png)

## 数据科学项目的工作流（Data science workflow）
### 如何优化一个数据漏斗（Optimizing a sales funnel）
分析用户行为，构建用户画像，能够帮助电商团队有针对的制定营销策略
- 1. 收集数据（Collect data）
- 2. 分析数据（反复迭代，提炼原理）(Analyze data && Iterate many times to get good insights)
- 3. 提炼观点和做出行为（Suggest hypotheses/actions && Deploy changes && Re-annalyze new data）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_20.png)
### 优化工厂流水线（Manufacturing line）
提升工厂流水线的效率和质量
例如发现当湿度变低时，杯子较易开裂的现象。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_21.png)

## 每个工作职能都需要学习如何使用数据（Every job function needs to learn how to use data）
随着数据信息时代的到来，对于每一份职业，数据很可能改写着你的工作职能。
### 销售
- 数据科学方面，对于销售人员可以根据数据科学项目，分析出不同受众人群，并制定不同的营销策略。
- 机器学习方面，如何一名销售人员能够精准的定位到自己的客户，并通过模型判断每个客户的优先级，那么将是非常省时的。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_22.png)
### 优化工厂流水线（Manufacturing line manager）
- 利用工厂流水线的产品数据，优化流水线，提升产品质量
- 使用缺陷检测模型，识别不合格产品
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_23.png)
### 农业（Agriculture）
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_24.png)

## 如何选择一个人工职能项目
这里介绍一个头脑风暴出令人振奋并且具有潜力的 AI 项目的框架
在前面的学习中，你已经了解到，AI 的能力是有限的，例如下图：
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_25.png)

我们要做的就是在 AI 的能力内和对业务有价值的方向的交集寻求一个解决方案。
这样的团队就是需要 AI 算法专家和业务专家协同完成。

### 放射科室
对于一个放射科医生而言，他们的工作有很多，例如：
- 观察患者的 X 射线图
- 分析病因，给出病例

我们思考的是在这些众多的工作中，找出一两项可以自动化的工作。

### 数据应该贴合业务场景，并不是越大越好
- Having more data almost never hurts.
- Data makes some businesses (like web search) defensible.
- But with small datasets, you can still make progress.

有更多的数据肯定是锦上添花的，但是高质量的小数据集也能解决一些问题。

### 判断一个项目是否值得花费时间去深入探索
在开展一个项目之前，我们通常会对其进行彻底的考察（Due diligence）,好的项目需要具备两点：
- 可行性
- 有价值
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_26.png)

#### 技术调研（Technical diligence）
- AI 系统的性能（Can Ai system meet desired performance）
- 数据量（How much data is needed）
- 开发周期（Engineering timeline）

#### 业务调研（Business diligence）
- 更少的成本（Lower costs）
- 更多的收入（Increase Revenue）
- 新的业务形态（Launch new product or business）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_27.png)

### 购买 vs. 自研
在上述的调研中，对于研发成本，我们也要结合自身的研发力量进行评估：是购买还是自研？并各有优缺点

- ML projects can be in-house or outsourced.
- DS projects are more commonly in-house.
- Some things will be industry standard - avoid building those.

对于一个机器学习项目，短期来看，外包出去，可能能更快地找到相关人才。
但是对于数据科学项目，往往是内部工作人员，因为内部的业务人员往往是更了解内部的业务逻辑的。
对于行业内通用的解决方案，要学会借力，避免成为“被火车追逐的人（暗指闭门造车）”
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_28.png)

## 与人工智能团队合作（working with an AI team）
### 确认你的验收标准（train data && test data）
对于一个 AI 系统，明确的验收标准是很重要的，方便 AI 工程师给出合理的解决方案。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_29.png)

### 数据集
在进行模型训练之前，往往需要两类数据集，即：
- training data
- testing data

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_30.png)

### 准确率的误区（Pitfall: Expecting 100% accuracy）
很多未从事人工职能行业的人，可能对于一项人工智能任务有 100% 的期待，但是目前 ML 的发展有以下限制：

- 机器学习的限制(黑盒子)（Limitations of ML）
- 无法提供足够的数据（Insufficient data）
- 混乱的数据（Mislabeled data）
- 不准确的数据（Ambiguous labels）

由于机器学习的不可解释性和数据的缺失和验收的尺度问题，无法提供理论意义上 100% 的准确性
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_31.png)
