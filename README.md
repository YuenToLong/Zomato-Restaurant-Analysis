# Zomato-Restaurant-Analysis
Cognifyz Data Analysis Internship | Zomato Global Restaurant Dataset Analysis (Level 1 + Level 2) in Chinese and English

Cognifyz数据分析实习任务|Zomato 全球餐厅数据集分析（level 1 + level 2）中英双语

# 🍽️ Zomato Restaurant Data Analysis

**Cognifyz Technologies Data Analysis Internship Project**  
（Zomato 全球餐厅数据集完整分析 | Level 1 + Level 2）

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B300?style=flat&logo=leaf&logoColor=white)

---

### 📋 项目介绍

本项目基于 **Zomato 全球餐厅数据集**（含巴西餐厅数据），完整完成了 Cognifyz Technologies 数据分析实习的所有任务（Level 1 + Level 2）。

通过系统化的数据清洗、探索性分析和可视化，深入研究了餐厅分布、价格区间、菜系组合、连锁餐厅特征以及地理空间分布等核心问题，并产出了高质量的交互式图表。

**目标**：为 Zomato 平台运营、商家策略和市场拓展提供数据洞察。

---

### 📊 数据集信息

- **来源**：Zomato Global Restaurants Dataset
- **记录数**：9,551 条餐厅数据
- **主要字段**：Restaurant Name, City, Cuisines, Aggregate rating, Votes, Price range, Has Online delivery, Has Table booking, Latitude, Longitude 等
- **特色**：覆盖多国数据（印度为主，包含巴西），具有极高的商业分析价值

---

### 🗂️ 项目结构

#### **Level 1**
- Task 1：数据探索与基本清洗
- Task 2：城市分析（餐厅数量与平均评分）
- Task 3：价格区间分布分析
- Task 4：在线外送对评分的影响

#### **Level 2**
- Task 1：菜系组合分析（最常见组合 + 高评分组合）
- Task 2：地理空间分析（城市分布 + 交互地图）
- Task 3：连锁餐厅定义与分析
- Task 4：连锁 vs 非连锁餐厅对比（评分、人气、分布差异）

---

### 🛠️ 技术栈

- **核心库**：Python 3, Pandas, NumPy
- **可视化**：Plotly Express（交互图表）+ Folium（地理地图）
- **其他**：Matplotlib, Seaborn, Collections

---

### 📈 关键洞察（部分）

- 餐厅数量最多的城市是 **New Delhi**，但高评分城市多为中小城市
- **North Indian + Chinese** 是全球最常见的菜系组合
- 连锁餐厅的平均评分和人气普遍高于非连锁餐厅
- 有在线外送的餐厅评分显著高于无外送餐厅
- 高价位餐厅（Price range 4）评分最高，但数量较少

（完整洞察详见各 Task Notebook）

---

### 🚀 如何运行

1. 克隆仓库
   ```bash
   git clone https://github.com/YuenToLong/Zomato-Restaurant-Analysis.git

2.安装依赖
  pip install pandas plotly folium matplotlib

3.启动Jupyter lab
  jupyter lab

4.依次运行Level 1 和Level 2 文件夹下的Notebook

🙏 Acknowledgments
特别感谢：

@heyamay 的开源项目:[Consumer-Trends-and-Preferences-in-the-Restaurant-Industry](https://github.com/heyamay/Consumer-Trends-and-Preferences-in-the-Restaurant-Industry)
其项目结构和分析思路给了我很大的启发和参考。
Cognifyz Technologies 提供的数据分析实习任务
Zomato 公开的全球餐厅数据集

Made with ❤️ by YuenToLong
如果你觉得这个项目对你有帮助，欢迎 Star ⭐ 支持！
