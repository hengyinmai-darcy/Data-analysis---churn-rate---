# 银行客户流失分析（Bank Customer Churn Analysis）

## 项目简介

本项目基于 Kaggle 银行客户数据集，使用 Python 与 SQL 对客户流失（Customer Churn）问题进行完整的数据分析。

项目重点包括：

- 客户流失率分析
- 高风险客户识别
- 客户分群分析
- 收入风险分析
- 商业洞察与留存建议

通过数据分析帮助企业识别客户流失原因，并制定更加精准的客户留存策略。

---

# 项目背景

客户流失是金融行业的重要业务问题。

客户流失不仅会影响：

- 银行收入
- 用户生命周期价值（LTV）
- 用户活跃度

还会提高企业获客成本。

因此，分析客户流失行为对于银行业务增长和客户运营具有重要意义。

---

# 数据集来源

Kaggle - Bank Customer Churn Dataset

数据集包含：

- 客户基础信息
- 年龄
- 国家地区
- 信用评分
- 银行余额
- 产品持有数量
- 是否活跃用户
- 是否持有信用卡
- 年薪
- 是否流失

---

# 技术栈

## Python

- Pandas
- NumPy
- Matplotlib
- Plotly

## SQL

- SQLite

## 开发平台

- Kaggle Notebook
- GitHub

---

# 项目流程

## 1. 数据清洗（Data Cleaning）

完成内容：

- 数据结构检查
- 缺失值检查
- 数据类型验证
- 特征字段分析
- 年龄分组处理

---

## 2. 探索性数据分析（EDA）

主要分析内容：

### 客户流失率分析

分析整体客户流失情况。

---

### 年龄与流失率分析

通过年龄分层识别高风险年龄段客户。

---

### 产品数量分析

分析不同产品数量客户的流失表现。

---

### 活跃用户分析

分析用户活跃度与客户留存之间的关系。

---

### 国家地区分析

比较不同国家客户流失率差异。

---

### 余额与收入风险分析

识别高余额客户流失带来的潜在收入风险。

---

## 3. SQL 业务分析

使用 SQL 完成：

- 整体流失率统计
- 客户分群分析
- 高风险客户筛选
- 国家维度分析
- 产品维度分析
- 高价值客户分析

---

# 核心业务洞察（Business Insights）

## 1. 高年龄客户流失率明显更高

50岁以上客户属于高风险流失群体。

---

## 2. 非活跃用户更容易流失

用户活跃度与客户留存存在明显关联。

---

## 3. 多产品客户出现异常高流失率

持有3-4个产品的客户出现较高流失现象，可能存在：

- 产品体验问题
- 服务复杂度问题
- 用户满意度下降

---

## 4. 高余额客户存在较高收入风险

流失客户中存在大量高余额用户，对银行收入造成较大影响。

---

# 商业建议（Business Recommendations）

- 针对高龄客户开展定向留存活动
- 提高非活跃用户运营触达频率
- 优化多产品客户使用体验
- 对高价值客户提供个性化服务

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

## 1.
# 项目成果

本项目完成了：

✅ Python 数据分析  
✅ SQL 业务分析  
✅ 客户流失分析  
✅ 客户分群分析  
✅ 收入风险分析  
✅ 商业洞察输出  

具备完整的数据分析项目流程。

---

# 项目结构

```bash
bank-customer-churn-analysis/
│
├── README.md
├── churn_analysis.ipynb
├── images/
│   ├── churn_by_age.png
│   ├── churn_by_country.png
│   ├── churn_by_products.png
│   └── churn_by_active_member.png
│
└── sql/
    └── churn_analysis.sql
