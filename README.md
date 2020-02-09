# ncp-group1
用于储存病毒系统发育树相关的代码和数据
# 一组：2019-nCoV 系统发育分析与微进化研究 

## 数据来源：

### 基因组序列数据库：

[GISAID: Global Initiative on Sharing Avian Influenza Database](https://www.gisaid.org/) 

[NCBI: National Center for Biotechnology Information](http://ncbi.nlm.nih.gov/)

 [National Microbiological Data Center](http://nmdc.cn/) (accession number NMDC10013002 and genome accession numbers NMDC60013002-01 to NMDC60013002-10)

 [China National GeneBank](https://db.cngb.org/datamart/disease/DATAdis19/) (accession numbers CNA0007332–35)

## 软件工具：

### 序列比对

BLAST

### 构建进化树

Lasergene 7.0 

MEGA 6.0 

PHYLIP 

### 评估分子进化率

 [BEAST](http://beast.bio.ed.ac.uk)

FUBAR: fast-unconstrained Bayesian approximation

## 研究方案

### 1.基因组序列下载

| Name            | Source | Database (ID)       | Sequence Length | Download URL |
| --------------- | ------ | ------------------- | --------------- | ------------ |
| SARS-CoV        | Human  | GenBank (NC_004718) |                 |              |
| bat-SL-CoVZC45  | Bat    | GenBank (MG772933)  |                 |              |
| bat-SL-CoVZXC21 | Bat    | GenBank (MG772934)  |                 |              |
| 2019-nCoV       | Human  |                     |                 |              |
| SHC014          |        |                     |                 |              |

建议包含蝙蝠、猪、穿山甲、水貂、猴子源的冠状病毒,建议包含人工合成的 SHC014 重组病毒全基因组序列

### 2.序列比对构建进化树

#### 序列比对

- 全基因组比对
- 同源基因比对
- 非编码区域比对

#### 选取最优模型

#### 构建进化树

- 最大简约法(Maximum Parsimony, MP)
- 最大似然法(Maximum Likelihood, ML）
- 贝叶斯推断法(Bayesian Inference, BI)

### 3. 推测变异时间

## 参考文献：

1. [The 2019-new coronavirus epidemic: evidence for virus evolution](https://www.biorxiv.org/content/10.1101/2020.01.24.915157v1)
2. [Evolution and variation of 2019-novel coronavirus](https://www.biorxiv.org/content/10.1101/2020.01.30.926477v1)
3. [Discovery of a rich gene pool of bat SARS-related coronaviruses provides new  insights into the origin of SARS coronavirus](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1006698)
4.  [Genomic characterisation and epidemiology of 2019 novel coronavirus: Implications for virus origins and receptor binding](https://linkinghub.elsevier.com/retrieve/pii/S0140-6736(20)30251-8)
5. [Discovery of a novel coronavirus associated with the recent pneumonia outbreak in humans and its potential bat origin](https://www.biorxiv.org/content/10.1101/2020.01.22.914952v2)

==请各组组长补充详细步骤，也请同学们先阅读文献，尝试重复文献工作==
