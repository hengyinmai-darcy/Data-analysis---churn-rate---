# 银行客户流失分析（Bank Customer Churn Analysis）

## 项目简介（Project Overview）

本项目基于 Kaggle 银行客户数据集，使用 Python 与 SQL 对客户流失（Customer Churn）问题进行完整的数据分析。  
This project analyzes customer churn behavior using a Kaggle banking dataset with Python and SQL.

项目重点包括：  
Key analysis areas include:

- 客户流失率分析（Customer Churn Rate Analysis）
- 高风险客户识别（High-Risk Customer Identification）
- 客户分群分析（Customer Segmentation）
- 收入风险分析（Revenue Risk Analysis）
- 商业洞察与留存建议（Business Insights & Retention Strategies）

通过数据分析帮助企业识别客户流失原因，并制定更加精准的客户留存策略。  
The project aims to identify churn drivers and provide actionable customer retention strategies.

---

# 项目背景（Project Background）

客户流失是金融行业的重要业务问题。  
Customer churn is a critical business issue in the banking industry.

客户流失不仅会影响：  
Customer churn can negatively impact:

- 银行收入（Bank Revenue）
- 用户生命周期价值（Customer Lifetime Value）
- 用户活跃度（Customer Engagement）

还会提高企业获客成本。  
It can also increase customer acquisition costs.

因此，分析客户流失行为对于银行业务增长和客户运营具有重要意义。  
Therefore, churn analysis is highly valuable for business growth and customer operations.

---

# 数据集来源（Dataset Source）

Kaggle - Bank Customer Churn Dataset

数据集包含：  
The dataset includes:

- 客户基础信息（Customer Information）
- 年龄（Age）
- 国家地区（Country）
- 信用评分（Credit Score）
- 银行余额（Account Balance）
- 产品持有数量（Number of Products）
- 是否活跃用户（Active Member Status）
- 是否持有信用卡（Credit Card Ownership）
- 年薪（Estimated Salary）
- 是否流失（Churn Status）

---

# 技术栈（Tech Stack）

## Python

- Pandas
- NumPy
- Matplotlib
- Plotly

## SQL

- SQLite

## 开发平台（Development Platform）

- Kaggle Notebook
- GitHub

---

# 项目流程（Project Workflow）

## 1. 数据清洗（Data Cleaning）

完成内容：  
Completed tasks:

- 数据结构检查（Data Structure Validation）
- 缺失值检查（Missing Value Check）
- 数据类型验证（Data Type Validation）
- 特征字段分析（Feature Analysis）
- 年龄分组处理（Age Group Processing）

---

## 2. 探索性数据分析（EDA - Exploratory Data Analysis）

主要分析内容：  
Main analysis topics include:

### 客户流失率分析（Customer Churn Rate Analysis）

分析整体客户流失情况。  
Analyzed overall churn distribution.

---

### 年龄与流失率分析（Age & Churn Analysis）

通过年龄分层识别高风险年龄段客户。  
Identified high-risk age groups through age segmentation.

---

### 产品数量分析（Product Analysis）

分析不同产品数量客户的流失表现。  
Analyzed churn behavior across different product counts.

---

### 活跃用户分析（Active Member Analysis）

分析用户活跃度与客户留存之间的关系。  
Explored the relationship between customer activity and retention.

---

### 国家地区分析（Country Analysis）

比较不同国家客户流失率差异。  
Compared churn rates across countries.

---

### 余额与收入风险分析（Balance & Revenue Risk Analysis）

识别高余额客户流失带来的潜在收入风险。  
Identified potential revenue risks caused by high-balance customer churn.

---

## 3. SQL 业务分析（SQL Business Analysis）

使用 SQL 完成：  
SQL was used for:

- 整体流失率统计（Overall Churn Rate Calculation）
- 客户分群分析（Customer Segmentation）
- 高风险客户筛选（High-Risk Customer Detection）
- 国家维度分析（Country-Level Analysis）
- 产品维度分析（Product-Level Analysis）
- 高价值客户分析（High-Value Customer Analysis）

---

# 核心业务洞察（Business Insights）

## 1. 高年龄客户流失率明显更高  
Older customers show significantly higher churn rates.

50岁以上客户属于高风险流失群体。  
Customers above 50 years old are considered high-risk churn customers.

---

## 2. 非活跃用户更容易流失  
Inactive customers are more likely to churn.

用户活跃度与客户留存存在明显关联。  
Customer activity level is strongly related to retention.

---

## 3. 多产品客户出现异常高流失率  
Customers with multiple products show unusually high churn rates.

持有3-4个产品的客户出现较高流失现象，可能存在：  
Customers holding 3-4 products experienced abnormal churn behavior, potentially due to:

- 产品体验问题（Product Experience Issues）
- 服务复杂度问题（Service Complexity）
- 用户满意度下降（Lower Customer Satisfaction）

---

## 4. 高余额客户存在较高收入风险  
High-balance customers represent major revenue risk.

流失客户中存在大量高余额用户，对银行收入造成较大影响。  
Many churned customers hold high account balances, creating substantial revenue exposure.

---

# 商业建议（Business Recommendations）

- 针对高龄客户开展定向留存活动（Launch retention campaigns for senior customers）
- 提高非活跃用户运营触达频率（Increase engagement with inactive users）
- 优化多产品客户使用体验（Improve experience for multi-product customers）
- 对高价值客户提供个性化服务（Provide personalized services for high-value customers）

---

# 项目截图

![年龄分布](images/Age_distribution.png)

![不同流失状态的年龄分布](images/age_distribution_by_churn.png)

![不同流失状态的余额分布](images/balance_distribution_by_churnstatus.png)

![客户活跃状态流失率分析](images/churn_rate_by_activitystatus.png)

![国家客户流失率分析](images/churn_rate_by_country.png)

![性别客户流失率分析](images/churn_rate_by_gender.png)

![产品数量与流失率分析](images/churn_rate_by_number_of_products.png)

![客户流失分布](images/customer_churn_distribution.png)

![不同流失状态的薪资分布](images/salary_distribution_by_churn.png)

---

# 项目成果（Project Outcome）

本项目完成了：  
This project successfully completed:

✅ Python 数据分析（Python Data Analysis）  
✅ SQL 业务分析（SQL Business Analysis）  
✅ 客户流失分析（Customer Churn Analysis）  
✅ 客户分群分析（Customer Segmentation Analysis）  
✅ 收入风险分析（Revenue Risk Analysis）  
✅ 商业洞察输出（Business Insight Generation）

具备完整的数据分析项目流程。  
This project demonstrates a complete end-to-end data analytics workflow.

---
作者 | Author
麦恒铟 HENGYIN Mai

GitHub Portfolio Project for Data Analyst
