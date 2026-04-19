# 邊緣人工智慧實務（EE5354701）─ Ch6.  Edge AI 實例實作 ─ 影像辨識

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch6_Image_Recognition/20260420_NTUST_EdgeAI_Ch06_Image_Recognition.jpg" width="640">

## 6.1. 影像辨識簡介  

* 傳統電腦／機器視覺 ─ 系統架構  
* 傳統電腦／機器視覺 ─ 自動光學檢測(AOI)  
* 傳統電腦／機器視覺 ─ 開發工具 [OpenCV](https://opencv.org/)  
* 範例6-1：Colab 中 OpenCV 顯示函式  
  * [如何在Colab上顯示雲端硬碟(Google Drive)上的影像和視頻](https://colab.research.google.com/github/OmniXRI/Colab_OpenCV_Display/blob/main/Colab_OpenCV_Display.ipynb)  
* 常見 AI 影像辨識任務  
* 常見 AI 影像辨識應用  
* 常見 AI 影像辨識開發工具  
* 傳統型機器視覺 vs. 新型態AI影像辨識  
* [Ultralytics 雲端訓練/推論平台](https://platform.ultralytics.com)  
* [Roboflow 雲端訓練/推論平台](https://app.roboflow.com)  
* [Google Colab 雲端訓練/推論平台](https://colab.research.google.com/)  
* 如何使用 Colab 直接開啟 Github 程式  

## 6.2. 影像分類  

* 常見電腦視覺任務  
* 常見影像分類資料集 - [ImageNet](https://www.image-net.org/index.php)
* 常見影像分類模型  
* [Intel OpenVINO Model Zoo](https://github.com/openvinotoolkit/open_model_zoo/) & Converter  
* [OpenVINO Model Zoo - Public - Classification](https://docs.openvino.ai/2023.3/omz_models_group_public.html#classification-models)  
* [OpenVINO 影像分類 Colab 範例](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/hello-world/hello-world.ipynb)  

## 6.3. 物件偵測  

* 常見電腦視覺任務  
* 常見物件偵測資料集 – [Microsoft COCO](https://cocodataset.org/#explore)  
* 物件偵測技術演進  
* 常見物件偵測模型  
* 候選區域(Region Proposals)  
* 一階式物件偵測 YOLO 發展歷程  
* 基於 Transformer 物件偵測技術  
* 旋轉物件偵測  
  * [DOTA Dataset](https://captain-whu.github.io/DOTA/index.html)  
* 常見物件偵測資料集格式  
* Ultralytics YOLO  
  * [Ultralytics YOLO 文檔](https://docs.ultralytics.com/zh/)  
  * [Ultralytics YOLO Github](https://github.com/ultralytics/ultralytics)  
* Ultralytics YOLO 執行效能比較  
* [Intel OpenVINO YOLO Colab範例](https://openvinotoolkit.github.io/openvino_notebooks/?search=YOLO)  
* 範例6-2:yolov26-object-detection-pytorch.ipynb  
  *[下載安裝 Ultralytics YOLO26 並執行基礎物件偵測](https://colab.research.google.com/github/OmniXRI/NTUST_EdgeAI_2026/blob/main/Ch6_Image_Recognition/yolov26-object-detection-pytorch.ipynb)  
* 範例6-3:yolov26-object-detection-openvino-ir.ipynb  
  * [使用 OpenVINO™ 轉換 YOLO26 模型成 IR 格式並進行物件偵測推論](https://colab.research.google.com/github/OmniXRI/NTUST_EdgeAI_2026/blob/main/Ch6_Image_Recognition/yolov26-object-detection-pytorch.ipynb)  
* 如何存取虛擬機磁碟檔案到Google Drive  
* 範例6-4: yolov26-object-detection-openvino-nncf.ipynb  
  * [使用 OpenVINO™ 轉換 YOLO26 模型經 NNCF 優化模型後再進行物件偵測推論](https://colab.research.google.com/github/OmniXRI/NTUST_EdgeAI_2026/blob/main/Ch6_Image_Recognition/yolov26-object-detection-openvino-nncf.ipynb)  
* Yolo26 不同模型處理後推論時間比較  
* 範例6-5：[OpenVINO YOLO Live Demo](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/yolov26-optimization/yolov26-object-detection.ipynb)  
* 範例6-6：[Yolo26 自定義資料集訓練](https://colab.research.google.com/github/OmniXRI/Yolo26_Colab_User_Datasets/blob/main/yolov26-training-test.ipynb)  
* 範例6-7：旋轉物件偵測(OBB)  
  * [YOLO26 Oriented Bounding Boxes Object Detection with OpenVINO™](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/yolov26-optimization/yolov26-obb.ipynb)  
* 補充：[人臉辨識（人臉定位、身份辨識）](https://github.com/OmniXRI/NTUST_EdgeAI_2023/tree/main/Ch7_Implementations/Ch7-3_Face_Recognition)  

## 參考文獻  

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* Intel OpenVINO Open Model Zoo Github  
https://github.com/openvinotoolkit/open_model_zoo  
* Intel OpenVINO Notebooks YOLO 相關範例  
https://openvinotoolkit.github.io/openvino_notebooks/?search=yolo  
* Ultralytics YOLO 說明文檔  
https://docs.ultralytics.com/zh/  
* 許哲豪，Ultralytics YOLO26 自定義資料集模型訓練  
https://github.com/OmniXRI/Yolo26_Colab_User_Datasets  

## 延伸閱讀  

* Ranjan Sapkota et al., YOLO26: Key Architectural Enhancements and Performance Benchmarking for Real-Time Object Detection  
https://arxiv.org/abs/2509.25164  
* Github, open-mmrotate  
https://github.com/open-mmlab/mmrotate  
* 許哲豪，如何以Google Colab及Yolov4-tiny來訓練自定義資料集─以狗臉、貓臉、人臉偵測為例  
https://omnixri.blogspot.com/2021/05/google-colabyolov4-tiny.html  
