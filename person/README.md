## 补充材料
### 目录
* [论文列表](#论文列表)
  * [一作论文](#一作论文)
  * [学术活动](#学术活动)
* [数据竞赛](#数据竞赛)
* [项目简介](#项目简介)
* [知识背景](#知识背景)

## 论文列表
#### 2020
* Hongyin Zhu, Yi Zeng, Dongsheng Wang, Cunqing Huangfu. Species Classification for Neuroscience Literature Based on Span of Interest Using Sequence-to-sequence Learning Model. Frontiers in Human Neuroscience, 2020 (SCI IF=2.870)  

#### 2019  
* Hongyin Zhu, Wenpeng Hu, Yi Zeng. FlexNER: A Flexible LSTM-CNN Stack Framework for Named Entity Recognition. NLPCC 2019. [Picture](pic/nlpcc2019.png)    
* Dongsheng Wang, Prayag Tiwari, Sahil Garg, Hongyin Zhu, and Peter Bruza. Structural block driven - enhanced convolutional neural representation for relation extraction. Applied soft computing (SCI IF=4.873)  

#### 2016  
* Hongyin Zhu, Yi Zeng, Dongsheng Wang, Bo Xu. Brain Knowledge Graph Analysis Based on Complex Network Theory. BIH 2016 (SCI/EI)
* Hongyin Zhu, Yi Zeng, Dongsheng Wang, Bo Xu. Relation Inference and Type Identification Based on Brain Knowledge Graph. BIH 2016 (SCI/EI)
* Yi Zeng, Dongsheng Wang, Hongyin Zhu. User Interests Analysis and Its Application on the Linked Brain Data Platform. BIH 2016 (SCI/EI)
* Hongyin Zhu, Yi Zeng, Yiping Yang. Research Topics Variation Analysis and Prediction Based on FARO and Neural Networks. IEEE SMC 2016 (EI index)
* Hongyin Zhu, Yi Zeng, Dongsheng Wang. Brain Knowledge Engine. Advances in Neuroinformatics IV. AINI 2016. Conference Abstract: Demonstration Session-12. DOI:10.14931/aini2016.ds.12

### 学术活动
* PC member of Brain Informatics conference  
* Outstanding contribution in reviewing Journal of Cognitive Systems Research [link](pic/Certificate.jpg) 
* IEEE SMC 2016 oral presentation  
* BIH 2016 oral presentation (introducing 3 papers)  

## 数据竞赛
* SemEval 2018 task 7: Subtask 2 Relation Classification (第2) Relation Extraction (第3) (Post evaluation using SwitchNet) [link](pic/1648318500.jpg)   
任务描述：从科学文献中抽取出预定义的6种关系类型。独立完成，使用SwitchNet。
* CCL 2018中文文本蕴含推理三等奖（第5）[link](pic/img6.jpg)     
任务描述：给定一句前提和一句假设，判断前提是否蕴含这假设。独立完成，使用了中文的词向量，字向量，overlap向量，decomposible attention.
* 其他比赛
  * MS MARCO passage retrieval (截至2019.01第3)  
  任务描述：给定一个问题从一千个候选的passage中选择最能回答这个问题的前10个候选项。作为核心骨干完成，使用 (BERT + attention + ranking)。这是一个没有截至日期的榜，排名有所后退。  
  * CCKS 2019 中文人物关系抽取 (第10) [link](pic/ccks2019.png)  
  任务描述： 使用远程监督产生的带有噪音的数据集作为训练语料，去抽取预定义的34种人物关系类型，例如“现妻”，“前妻”，“未婚妻”，“叔伯”，“舅舅”等。作为核心骨干合作完成，采用GCN。(I am uw1成绩不理想，数据筛选上有所欠缺，共358 支队伍 • 828 名参赛者)
  * 新闻链接预测 Hackthon 2019  
  任务描述：Science of Science Data Hackthon 给定一篇新闻，从2.5万篇参考文献候选中，选出前3篇能够引用的参考文献。作为核心骨干完成，比赛时间是3天，使用BM25进行初选，然后使用BERT。
  * Kaggle 2018 Toxic Comment Classificaiton Challenge  
  任务描述：对twitter进行多标签情感分类。独立完成，使用CNN和LSTM的混合模型，以及self attention识别出情感词。
  * 2018 拍拍贷智能客服问句匹配比赛  
  任务描述：判断不同的提问是否表达相同的意思，在智能客服方面得到体现。独立完成，使用注意力机制。
  * 天池大数据资金流入流出预测 2015  
  任务描述：预测某一天支付宝资金的流入流出情况。使用神经网络拟合这个回归任务。
  * 天池大规模图像搜索 2015  
  任务描述：输入图像，找到最相似的100个候选。使用VGG16获得表示然后求相似度。
  * 天池公交客流量预测 2015  
  任务描述：预测不同线路的公交车的客流量。
  * 华为“寻路”图搜索比赛 2016  
  任务描述：在基站网络中，找到穿过一部分指定节点，最后到达终点的最短路径。由于节点数量，而且比较运行速度，使用Dijstrka加上一些随机的猜测。

## 项目简介
项目 | 描述
---|---
FlexNER | 基于Tensorflow的命名实体识别开源工具包，支持数据增强。
GRNN4TE | 端到端三元组抽取神经网络，从简单的文本输入中抽取出(subject, predicate, object)结构化数据。
SwitchNet | 模块化关系抽取神经网络模型。
Brain Knowledge Engine | 脑科学知识图谱服务。从Query box输入查询的术语，（例如：Hippocampus），系统就会按照不同物种组织并返回关联关系。
Algorithm | 实现各种常见算法。（排序、二叉搜索树、图搜索、链表、队列、堆栈等）
SpecExplorer | 输入生物医学文献的文档，生成它所研究的物种类别，用于从物种角度组织文献和知识。
GDBT | 用于语义知识库增删改查，导入导出知识的toolkit。基于Java、Virtuoso、Jena。
BertQA | 搜索引擎问答模型。输入一个问题和1000个候选答案，自动对其进行排序，返回最能匹配这个问题的前10个答案。
RelationRunner | 半监督关系抽取算法。给定几个种子，总结一些规则，然后抽取更多关系。使用LCS算法学习规则，为了提升计算效率，采用KMP算法优化字符串匹配。

## 知识背景
类型 | 课程
---|---
人工智能 | 自然语言处理、人工智能、高级人工智能、计算语言学、计算机视觉、计算社会学
机器学习 | 机器学习、数据挖掘、矩阵论、模式识别、概率论与数理统计、运筹学
语义技术 | 知识图谱的数据管理、语义网与Agency
算法设计 | 计算机算法设计与分析

## 其他奖励材料
 * 2016研究生国家奖学金 [link](pic/guojiang.pdf)
 * 优秀学生干部 [link](pic/ganbu.jpg)
 * 优秀学生会部长 [link](pic/buzhang.pdf)
 * 其他约10种奖励 [link](pic)
