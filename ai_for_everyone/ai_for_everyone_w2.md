# AI For Everyone —— week2
本文总结于吴恩达视频课程 《ai for everyone》 

[课程传送门](https://www.coursera.org/learn/ai-for-everyone/home/week/1)

[bilibili 中英文字幕](https://www.bilibili.com/video/BV1yC4y127uj?vd_source=275f6919f1e622d67ac6c138d0967924&spm_id_from=333.788.player.switch&p=17)

## 如何开展 AI 项目（Building AI projects）
> - AI 项目的工作流程（Workflow of projects）
> - 如何选择一个正确的项目（Selecting AI projects）
> - 如何为这个项目组织团队和项目组（Organizing data and team for the projects）

## AI 项目的工作流（Workflow of projects）
### 语音助手
我们用一个例子来说明该工作流，例如如何构建一个语音助手（smart speaker）
- collect data
例如当收集到足够多的数据后，例如许多的语音数据。
- Train model
    Iterate many times until good enough（反复迭代）
- Deploy model
    Get data back（数据反馈）
    Maintain / update model（模型升级）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_18.png)

### 自动驾驶
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_19.png)

## 数据科学项目的工作流（Data science workflow）
### 如何优化一个数据漏斗（Optimizing a sales funnel）
分析用户行为，构建用户画像，能够帮助电商团队有针对的制定营销策略
- 收集数据（Collect data）
- 分析数据（反复迭代，提炼原理）(Analyze data && Iterate many times to get good insights)
- 提炼观点和做出行为（Suggest hypotheses/actions && Deploy changes && Re-annalyze new data）

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_20.png)
### 优化工厂流水线（Manufacturing line）
提升工厂流水线的效率和质量
例如发现当湿度变低时，杯子较易开裂的现象。
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_21.png)

## 每个工作职能都需要学习如何使用数据（Every job function needs to learn how to use data）
**随着数据信息时代的到来，对于每一份职业，数据很可能改写着你的工作职能。**
### 销售
- **数据科学方面，对于销售人员可以根据数据科学项目，分析出不同受众人群，并制定不同的营销策略。**
- **机器学习方面，如何一名销售人员能够精准的定位到自己的客户，并通过模型判断每个客户的优先级，那么将是非常省时的。**
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

**有更多的数据肯定是锦上添花的，但是高质量的小数据集也能解决一些问题。**

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
- **更少的成本（Lower costs）**
- **更多的收入（Increase Revenue）**
- **新的业务形态（Launch new product or business）**

![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_27.png)

### 购买 vs. 自研
在上述的调研中，对于研发成本，我们也要结合自身的研发力量进行评估：是购买还是自研？并各有优缺点

- ML projects can be in-house or outsourced.
- DS projects are more commonly in-house.
- Some things will be industry standard - avoid building those.

**对于一个机器学习项目，短期来看，外包出去，可能能更快地找到相关人才。
但是对于数据科学项目，往往是内部工作人员，因为内部的业务人员往往是更了解内部的业务逻辑的。
对于行业内通用的解决方案，要学会借力，避免成为“被火车追逐的人（暗指闭门造车）”**
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
**很多未从事人工职能行业的人，可能对于一项人工智能任务有 100% 的期待，但是目前 ML 的发展有以下限制：**

- **机器学习的限制(黑盒子)（Limitations of ML）**
- **无法提供足够的数据（Insufficient data）**
- **混乱的数据（Mislabeled data）**
- **不准确的数据（Ambiguous labels）**

由于机器学习的不可解释性和数据的缺失和验收的尺度问题，无法提供理论意义上 100% 的准确性
![](https://raw.githubusercontent.com/tyronemaxi/ai_notes/master/ai_for_everyone/imgs/img_31.png)

## 总结：AI项目的成功要素与行动指南

### 一、核心工作流程

1. **AI项目三步法**：
   - **数据收集**：需确保数据质量与场景匹配（如语音助手需多样化的语音样本）
   - **模型迭代**：通过反复训练优化性能（自动驾驶需持续更新道路场景数据）
   - **部署反馈**：建立数据回流机制实现模型升级（如电商推荐系统的实时用户行为反馈）
2. **数据科学项目关键**：
   - 通过漏斗分析提炼业务洞见（如工厂湿度与产品质量的关联性）
   - 形成"数据收集→分析→行动→再验证"的闭环

### 二、项目选择方法论

1. **可行性矩阵**：

   - 技术维度：AI能力边界评估（当前技术能否实现预期精度）
   - 业务维度：ROI测算（成本降低/收入增长/新业务潜力）
   - 案例：医疗影像分析应聚焦特定病灶检测而非全流程自动化

2. **决策树模型**：

   mermaid

   复制

   ```
   graph TD
   A[潜在AI项目] --> B{技术可行性?}
   B -->|Yes| C{业务价值>实施成本?}
   B -->|No| D[淘汰]
   C -->|Yes| E[优先执行]
   C -->|No| F[暂缓]
   ```

### 三、团队协作与数据管理

1. **跨职能团队构建**：
   - 铁三角模型：业务专家（领域知识）+数据科学家（分析能力）+ML工程师（模型部署）
   - 典型案例：零售场景中营销团队需明确用户分层标准，数据团队设计特征工程
2. **数据治理原则**：
   - 训练集/测试集需反映真实业务分布（如金融风控需包含欺诈样本的长尾分布）
   - 标注质量管控：建立交叉验证机制，处理模糊案例（如医学图像的病灶边界）

### 四、实施避坑指南

1. **预期管理**：
   - 接受合理误差范围（当前技术下人脸识别95%精度已属优秀）
   - 建立容错机制：AI输出需结合人工复核（如法律文件审查）
2. **构建防御性优势**：
   - 数据护城河：通过用户授权持续积累特有数据（如智能家居的用户习惯数据）
   - 技术选型：通用能力用API（如语音识别），核心业务自研模型（如个性化推荐算法）

### 五、行动检查清单

1. 启动前：
   - 完成技术可行性POC验证
   - 明确核心业务指标（KPI）
   - 评估数据可获得性与合规性
2. 执行中：
   - 建立每周跨部门同步会
   - 实施阶段性验收（Milestone验证）
   - 部署监控报警系统（数据漂移检测）
3. 迭代期：
   - 建立用户反馈闭环通道
   - 制定模型再训练计划
   - 规划技术债偿还路线图

通过系统化的工作框架、严谨的项目评估和跨团队协作，企业能有效规避"为AI而AI"的陷阱，真正实现人工智能技术的业务价值转化。记住：成功的AI项目不是技术炫技，而是用智能化的方式解决那些长期存在的业务痛点。
