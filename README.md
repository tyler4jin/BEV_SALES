# Electric Vehicle Crawler | 新能源汽车爬虫

## 关于作者

点击我的主页[youchengli.com](youchengli.com)了解关于我的情况。

## 快速上手

我们的项目包括：
- 数据爬虫
  - 汽车之家新能源汽车销量、售价
  - 国际原油价格
  - 中国充电桩分布
- 数据分析
  - 对充电桩分布进行聚类分析
  - 使用线性回归和灰色预测预测新能源汽车的销量

## 关于项目

[[项目背景]](https://github.com/xjtulyc/Electric_Vehicle_Crawler/blob/main/docs/background.md)
[[API]](https://github.com/xjtulyc/Electric_Vehicle_Crawler/blob/main/docs/api.md)

## 运行

下载项目到本地

```
git clone git@github.com:xjtulyc/Electric_Vehicle_Crawler.git
```

爬取数据，依次爬取汽车销量等需要分析的数据。

```shell
python crawler.py
```

使用线性回归和灰色预测对数据进行分析，其中充电桩的空间分布使用聚类分析进行度量。

```shell
python analysis.py
```
## 依赖

```requirements.txt
numpy
pandas
selenium
bs4
```

## 项目进展

### 1. 数据爬虫 （2023-01-10 to 2023-01-25）

- [x] 1.1. 汽车销量 （2023-01-10 to 2023-01-14）

- [x] 1.2. 汽车售价 （2023-01-14 to 2023-01-16）

- [x] 1.3. 汽油柴油价格 （2023-01-16 to 2023-01-20）参考[这个项目](https://github.com/datasets/oil-prices)

- [x] 1.4. 充电桩数目和空间分布 （2023-01-20 to 2023-01-25）

### 2. 数据分析 （2023-01-26 to 2023-02-05）

- [ ] 2.1. 线性回归 （2023-01-26 to 2023-02-01）

- [ ] 2.2. 灰色预测 （2023-02-02 to 2023-02-05）
