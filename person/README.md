### Contents
* [Paper List](#paper-list)
  * [一作论文](#一作论文)
  * [学术活动](#学术活动)
* [数据竞赛](#数据竞赛)
* [Projects](#projects)

## Paper List
### 一作论文
* SwitchNet: A Modular Neural Network for Adaptive Relation Extraction. EMNLP 2019 在审  
* GRNN4TE: A Graph Recursive Neural Network for Joint Task Learning in Triple Extraction. EMNLP 2019 在审  
* C2FNet: A Coarse-to-Fine Neural Network for Modeling List-Context Information in Answer Passage Selection. 改投AAAI 2019
* FlexNER: A Flexible LSTM-CNN Stack Framework for Named Entity Recognition. NLPCC 2019 在审
* Building Functioning Brain Connectome Knowledge Graph through Semi-supervised Relation Extraction. Frontiers in Neuroinformatics 在审 （神经信息学领域代表期刊，SCI IF=3.074)
* SSG: A Hierarchical Attention Model for Species Sequence Generation in Biomedical Literature. Frontiers in Neuroinformatics 改投 （神经信息学领域代表期刊，SCI IF=3.074）
* Named Entity Recognititon on Neurobiology, Cognition and Disease. Frontiers in Neuroinformatics 改投（神经信息学领域代表期刊，SCI IF=3.074）
* Research Topics Variation Analysis and Prediction Based on FARO and Neural Networks. IEEE SMC 2016 (EI index)
* Brain Knowledge Graph Analysis Based on Complex Network Theory. BIH 2016 (EI index)
* Relation Inference and Type Identification Based on Brain Knowledge Graph. BIH 2016 (EI index)
* Brain Knowledge Engine.  AINI 2016

### 学术活动
* PC member of Brain Informatics conference  
* Outstanding contribution in reviewing Journal of Cognitive Systems Research

## 数据竞赛
* SemEval 2018 task 7: Subtask 2 Relation Classification (第2) Relation Extraction (第3)  
任务描述：从科学文献中抽取出预定义的6种关系类系，该任务独立完成，使用SwitchNet。
* MS MARCO passage retrieval (截至2019.01第3) 
任务描述：给定一个问题从一千个候选的passage中选择最能回答这个问题的前10个候选项。作为核心骨干完成，使用 (BERT + attention + ranking)。因为这是一个没有截至日期的榜，现在退后到12了。  
* CCL 2018中文文本蕴含推理三等奖（第5）  
任务描述：给定一句前提和一句假设，判断前提是否蕴含这假设。独立完成，使用了中文的词向量，字向量，overlap向量，decomposible attention.
* 其他比赛
  * 新闻链接预测 Hackthon 2019  （21名）
  任务描述：Science of Science Data Hackthon 给定一篇新闻，从2.5万篇参考文献候选中，选出前3篇能够引用的参考文献。作为核心骨干完成，比赛时间是3天，使用BM25进行初选，然后使用BERT。
  * Kaggle 2018 Toxic Comment Classificaiton Challenge  
  任务描述：对twitter进行多标签情感分类。独立完成，使用CNN和LSTM的混合模型，以及self attention识别出情感词。
  * 2018 拍拍贷智能客服问句匹配比赛  
  任务描述：判断不同的提问是否表达相同的意思，在智能客服方面应用。独立完成，使用注意力机制。
  * 天池大数据资金流入流出预测 2015  
  任务描述：预测某一天支付宝资金的流入流出情况。使用神经网络拟合这个回归任务。输入信息包含日期，
  * 天池大规模图像搜索 2015  
  任务描述：输入图像，找到最相似的100个候选。使用VGG16获得表示,求相似度。
  * 天池公交客流量预测 2015  
  任务描述：预测不同线路的公交车的客流量。使用
  * 华为“寻路”图搜索比赛 2016  
  任务描述：在基站网络中，找到穿过一部分指定节点，最后到达终点的最短路径。由于节点数量，而且比较运行速度，使用Dijstrka加上一些随机的猜测。

## Projects
