This project file is the key code for our thesis.
Main code description:
1. The impedance spectra in the picture are plotted using: code 0304_EIS 绘制, which allows batch plotting of standard EIS plots with equiaxial scaling, as in Fig. 1 (a-h).
2. 0304_Column stacked plot of shap value multi-cells is used to calculate and plot (a) (b) in Fig. 7, which is the effect of stacking the shap values of the individual impedance characteristics of the four cells.
3. 0304_Plotting capacity changes Used to plot capacity changes as in Fig. 1(i)
4. 0304_why10_computational time and accuracy Used to plot Figure 4, to compute and compare the accuracy and measurement time when selecting 1 to 120 features.
5. EIScatboost_0304, EISDecisionTreeRegressor_0304, EISlightgbm_0304, and EISXGBRegressor_0304 are used to compute and plot the prediction effects of the four machine learning models on the four test 6. batteries, including the selection of various types of feature combinations.
6. Battery health state and capacity data are held in SOH and 合集数据
7. Battery impedance spectrum data is held in EIS_state_V.


这项工程文件是我们论文的重要代码。
主要代码介绍：
1.图片中的阻抗谱图绘制使用：代码0304_EIS绘制，可以批量绘制等轴缩放的标准EIS图，如图1（a-h）。
2.0304_Column stacked plot of shap value multi-cells 用于计算和绘制图7中的（a）（b），是四节电池各个阻抗特征的shap值的叠加效果。
3.0304_Plotting capacity changes 用于绘制容量变化图，如图1（i）
4.0304_why10_computational time and accuracy 用于绘制图4，计算和对比选择1到120个特征时候的精度和测量时间。
5.EIScatboost_0304、EISDecisionTreeRegressor_0304、EISlightgbm_0304、EISXGBRegressor_0304用于计算和绘制四种机器学习模型在四节测试电池上的预测效果，包括各类特征组合的选择。
6.SOH和合集数据中保存了电池健康状态和容量数据
7.EIS_state_V中保存了电池的阻抗谱数据。
