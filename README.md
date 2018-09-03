# Forecast
用机器学习来预测购物中心客流

运行环境：Jupyter Notebook
调用包：sklearn、pandas、numpy、time、matplotlib
具体步骤：
1、在Raw_data.csv中添加数据，每一列可对照客流分析表.xlsx填写（不少于50条历史数据，数据越多越准确）。
2、在Jupyter Notebook内运行forecast.ipynb。
3、软件会生成一个yyyy-mm-dd hh.mm.ss.csv的文件。第一列date表示日期，y表示实际值，forecast表示预测值，percent表示准确率。
