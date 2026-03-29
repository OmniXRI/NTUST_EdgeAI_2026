# 邊緣人工智慧實務（EE5354701）─ Ch5.  模型優化與部署

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch5_Optimization/20260330_NTUST_EdgeAI_Ch05_Optimization.jpg" width="640">

## 5.1 模型訓練優化

* 神經網路訓練與推論  
* 數值擬合  
* 輸出格式  
* 損失函數  
  * 損失函數 ─ MAE  
  * 損失函數 ─ MSE, RMSE  
  * 損失函數 ─ Cross-Entropy  
* 梯度下降  
  * 梯度下降 ─ 極值、梯度  
  * 梯度下降 ─ 學習率  
  * 梯度下降 ─ 固定學習率  
  * 梯度下降 ─ 常見優化器調整方式  
  * 梯度下降 ─ BGD / SGD / MBGD  
  * 梯度下降 ─ 梯度更新  
  * 梯度下降 ─ Adagrad  
  * 梯度下降 ─ RMSProp  
* 慣性動量
  * 慣性動量 ─ Momentum  
  * 慣性動量 ─ Adam  
  * 慣性動量 ─ 實驗比較
* 隨機丟棄  

## 5.2 加速訓練方式 

* 常見模型訓練加速方式  
* 硬體計算加速  
* 模型架構加速  
  * 模型架構加速  ─ 批次正規化  
  * 模型架構加速  ─ 低複雜度模型  
  * 模型架構加速 ─ 輕量化卷積
  * 模型架構加速 ─ 自動學習
  * 自動學習 (AutoML)  
  * 自動學習 ─ 基本框架  
* 訓練策略加速  
  * 訓練策略加速 ─ 混合精度 / 優化器  
  * 訓練策略加速 ─ 遷移學習  
  * 遷移式學習 ─ 應用程式  
  * 訓練策略加速 ─ 分散式學習  
  * 訓練策略加速 ─ 聯邦學習  
* 資料處理加速 ─  資料管道 / 資料降維  

## 5.3 模型推論優化  

* 數值量化 ─ 轉換位數  
* 數值量化 ─ 量化方式  
* 模型剪枝  
* 模型剪枝 ─ 實施方式  
* 權重共享  
* 矩陣乘法優化  
  * 矩陣乘法優化 ─ 標準卷積  
  * 矩陣乘法優化 ─ 快速卷積
  * 矩陣乘法優化 ─ 低秩逼近
  * 矩陣乘法優化 ─ im2Col
* 知識蒸餾
* [Intel 神經網路壓縮框架 (NNCF)](https://github.com/openvinotoolkit/nncf) 
  * [Intel NNCF 工作流程](https://docs.openvino.ai/2026/openvino-workflow/model-optimization.html)  
  * [Intel NNCF ─ 訓練後量化](https://docs.openvino.ai/2026/openvino-workflow/model-optimization-guide/quantizing-models-post-training.html)  
    - [Basic Quantization](https://docs.openvino.ai/2026/openvino-workflow/model-optimization-guide/quantizing-models-post-training/basic-quantization-flow.html)  
    - [Quantizing with Accuracy Control](https://docs.openvino.ai/2026/openvino-workflow/model-optimization-guide/quantizing-models-post-training/quantizing-with-accuracy-control.html)  
  * [Intel NNCF ─ 量化感知訓練](https://docs.openvino.ai/2026/openvino-workflow/model-optimization-guide/compressing-models-during-training/quantization-aware-training.html)  
  * [Intel NNCF ─ 剪枝](https://docs.openvino.ai/2026/openvino-workflow/model-optimization-guide/compressing-models-during-training/filter-pruning.html)  

## 參考文獻

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )   https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* 陽明交通大學電子工程學系張添烜老師，「深度學習的模型壓縮與加速」(YouTube)  
https://www.youtube.com/playlist?list=PLj6E8qlqmkFv3cCjjX2SA1D4FJ9fadDij  
* MIT Han Lab (韓松）,「TinyML and Efficient Deep Learning Computing | MIT 6.5940 Fall 2024」  
https://hanlab.mit.edu/courses/2024-fall-65940  
* Intel, OpenVINO Document – How to Use - Conventional AI Workflow - Model Optimization – NNCF  
https://docs.openvino.ai/2026/openvino-workflow/model-optimization.html  
*  Hamza A. el., Neural Network Quantization for Microcontrollers: A Comprehensive Survey of Methods, Platforms, and Applications  
https://arxiv.org/abs/2508.15008  
