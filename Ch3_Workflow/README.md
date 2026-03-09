# 邊緣人工智慧實務（EE5354701）─ 3. 邊緣智慧開發流程
<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch3_Workflow/2026_NTUST_EdgeAI_Ch03_Workflow.jpg" width="640">

## 3.1. 資料收集與標註
* Edge AI 開發流程
* 問題定義 ─ 流程規畫
* 資料類型與標註關係
* 資料型態 ─ 感測器數據
  * [20221108_南開科大_自動化工程系_智慧製造與工業感測技術](https://omnixri.blogspot.com/2022/11/20221108.html)
* 資料型態 ─ 格式化
* 資料集建置
* 端到端資料集建置案例
* 資料擴增 ─ 影像類
* 資料擴增 ─ 時序類
* 資料擴增 ─ 模擬生成類
* 公開資料集 ─ 影像類
  * [MNIST](https://www.kaggle.com/datasets/hojjatk/mnist-datasetim)
  * [ILSVRC(ImageNet)](https://www.image-net.org/)
  * [Pascal VOC](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/)
  * [Microsoft COCO](https://cocodataset.org/)
* 公開資料集 ─ 影像類 ([Roboflow](https://roboflow.com/universe
))
* 公開資料集 ─ 聲音類
  * [ESC-50](https://github.com/karolpiczak/ESC-50)
  * [Google AudioSet](https://research.google.com/audioset/)
  * [Google Speech Commands Dataset](https://www.kaggle.com/datasets/yashdogra/speech-commands)
* 公開資料集 ─ 生成式AI類
  * [Hugging Face](https://huggingface.co/datasets)
* 影像標註類型 ─ 依工作內容
* 影像標註類型 ─ 依標註外形
* 影像標註格式 ─ VOC (xml)
* 影像標註格式 ─ COCO (json)
* 影像標註格式 ─ YOLO (txt)
* 影像標註工具 ─ LabelImg, CVAT
  * [LabelImg](https://github.com/HumanSignal/labelImg)
  * [Intel CVAT](https://cvat.org)
* 影像標註工具 ─ [Roboflow](https://blog.roboflow.com/getting-started-with-roboflow/)
* 資料集迷思 ─ 資料增長
* 資料集迷思 ─ 標註水準
* 資料集迷思 ─ 子集不均
* 資料集迷思 ─ 自動聚類

## 3.2. 模型選用與訓練
* Edge AI 開發流程
* 模型選用 ─ 模型動物園
  * [Model Zoo](https://modelzoo.co/)
  * [Intel Mode Zoo](https://github.com/openvinotoolkit/open_model_zoo)
  * [Kaggle Models](https://www.kaggle.com/models)
  * [ONNX Model Zoo](https://github.com/onnx/models/)
  * [Google TensorFlow Model Graden](https://github.com/tensorflow/models)
  * [Arm Model Zoo](https://github.com/Arm-Examples/ML-zoo)
  * [Hugging Face Models](https://huggingface.co/models)
  * [Roboflow Models](https://roboflow.com/models)
* 建立模型 ─ 自建模型
  * [網頁版](https://netron.app/) 、[下載版](https://github.com/lutzroeder/netron)
* 訓練調參 ─ 反向傳播
* 訓練調參 ─ 可視化工具
* 訓練調參 ─ 學習率
* 訓練調參 ─ 常見超參數
* 訓練調參 ─ 資料集配置
* 訓練調參 ─ 資料集交叉驗證
* 評估指標
* 評估指標 ─ 分類問題
* 評估指標 ─ ROC / PR曲線
* 評估指標 ─ 物件偵測問題
* 評估指標 ─ 影像分割問題
* 評估指標 ─ 回歸預測問題
* 評估指標 ─ 生成式 AI 
* 自定義模型訓練
  * [20201218_PyTorch_Classification_Training.ipynb](https://colab.research.google.com/github/OmniXRI/NTUST_Colab_PyTorch_Classification/blob/main/20201218_PyTorch_Classification_training.ipynb)
* 自定義模型推論
  * [20201218_PyTorch_Classification_Inference.ipynb](https://colab.research.google.com/github/OmniXRI/NTUST_Colab_PyTorch_Classification/blob/main/20201218_PyTorch_Classification_Inference.ipynb)
* 模型儲存與還原
* 預訓練模型推論 
  * [20201218_PyTorch_Classification_Pretrained_Inference.ipynb](https://colab.research.google.com/github/OmniXRI/NTUST_Colab_PyTorch_Classification/blob/main/20201218_PyTorch_Classification_Pretrained_Inference.ipynb)

## 3.3. 專題設計與製作
* [創意專題製作心法](https://omnixri.blogspot.com/2024/11/20241117.html)
* [邊緣人工智慧案例實作](https://github.com/OmniXRI/NTUST_EdgeAI_2026)
* 邊緣人工智慧專題參考網站
  * [TinyML案例分享（技術分類）](https://hackmd.io/@OmniXRI-Jack/tinyML_30_projects)
  * [Edge Impulse 案例研究](https://www.edgeimpulse.com/case-studies)
  * [Arduino UNO Q 教學案例整理](https://omnixri.blogspot.com/2026/02/arduino-uno-q.html)
  * [Hackster.io 人工智慧及機器學習專案](https://www.hackster.io/ML)
  * [Intel OpenVINO Notebooks](https://openvinotoolkit.github.io/openvino_notebooks/)
  * [Roboflow 部落格案例研究](https://blog.roboflow.com/tag/case-studies/)
* 期末專題提案大綱
  * 期末專題提案範本 - 2026_EdgeAI_期末專題提案_學號_姓名.docx
* 期末專題提交方式

## 3.4. 基本工具
  * Colab - 2023_NTUST_EdgeAI_Cloab進階應用.pdf
  * Markdown - 2023_NTUST_EdgeAI_Markdown.pdf

## 參考文獻

* [臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )](https://omnixri.blogspot.com/p/ntust-edge-ai.html)
* [許哲豪，【AI HUB專欄】如何建立精準標註的電腦視覺資料集](https://omnixri.blogspot.com/2020/10/ai-hub_16.html)
 * [許哲豪，【課程簡報分享】AI萬能？導入AI的八大迷思剖析](https://omnixri.blogspot.com/2019/08/aiai.html)
* [許哲豪，20241117_中央大學_創意專題製作心法：從想法評估可行性分析到新創競賽](https://omnixri.blogspot.com/2024/11/20241117.html)
