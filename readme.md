# STGNN: Spatial-Temporal Graph Neural Network for Traffic Prediction

这是一个基于时空图神经网络的交通流量预测模型。该模型结合了图神经网络(GNN)和门控循环单元(GRU),能够有效捕获交通数据的时空依赖关系。

## 模型架构

该模型主要包含以下组件:

- **空间特征提取**: 使用图神经网络(SGNN)捕获空间依赖关系
- **时间特征提取**: 使用改进的GRU单元处理时序信息
- **注意力机制**: 实现多头自注意力,增强长期依赖建模