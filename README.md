\# HR 数据自动化处理与分析 Demo



\## 📌 项目背景

本项目模拟了 HR 日常工作中的数据处理场景：从系统导出的员工薪资、考勤、健康数据往往存在缺失值、格式混乱、字段混合等问题。本项目使用 Python（Pandas/NumPy/Matplotlib）实现从\*\*数据生成 → 清洗 → 分析 → 可视化\*\*的全流程自动化，旨在替代传统 Excel 手动操作，提升 HR 工作效率。



\## 🛠️ 技术栈

\- Python 3

\- Pandas / NumPy（数据处理）

\- Matplotlib（数据可视化）

\- Jupyter Notebook（开发环境）



\## 📂 项目结构

（此处放上面那个文件结构图）



\## 🔍 核心功能

1\. \*\*数据生成\*\*：模拟生成员工薪资表、每日 HR 数据、睡眠健康数据。

2\. \*\*数据清洗\*\*：处理缺失值（`fillna`/`dropna`）、拆分复合字段（`str.split`）、类型转换（`astype`）。

3\. \*\*数据分析\*\*：按部门/岗位分组聚合（`groupby`+`agg`）、按月/季度重采样（`resample`）、数据分箱（`pd.cut`）。

4\. \*\*可视化输出\*\*：生成部门薪资对比柱状图、睡眠等级与心率关系图，并导出 Excel 报表。



\## 🚀 快速开始

```bash

\# 安装依赖

pip install -r requirements.txt



\# 运行 Jupyter

jupyter notebook

