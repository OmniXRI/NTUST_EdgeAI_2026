# 邊緣人工智慧實務（EE5354701）─ Ch7.  Edge AI 實例實作 ─ 影像分割、姿態估測

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch7_Pose_Estimation/20260427_NTUST_EdgeAI_Ch7_Pose_Estimation.jpg" width="640">

## 7.1. 影像分割  

* 傳統影像分割技術 ─ 像素特徵  
* 傳統影像分割技術 ─ 聚類、圖論  
* AI 影像分割技術 ─ 像素級分割任務  
* AI 影像分割技術 ─ 影像分割標註方式  
* AI 影像分割技術 ─ VOC 資料集格式  
* PNG8 (Indexed, Palette)格式  
* AI 影像分割技術 ─ COCO資料集格式  
* AI 影像分割技術 ─ 基於卷積神經網路  
  * [Image Segmentation Using Deep Learning: A Survey](https://arxiv.org/abs/2001.05566)  
* 影像語義分割技術 ─ [FCN](https://arxiv.org/abs/1411.4038)  
* 影像語義分割技術 ─ [U-Net](https://arxiv.org/abs/1505.04597)  
* 影像語義分割技術 ─ [DeepLabV3+](https://arxiv.org/abs/1802.02611)  
* AI 影像分割技術 ─ 實例分割技術演進  
  * [A Survey on Instance Segmentation: State of the art](https://arxiv.org/abs/2007.00047)  
* 影像實例分割技術 ─ [Mask R-CNN](https://arxiv.org/abs/1703.06870)   
* 影像實例分割技術 ─ [Yolact](https://arxiv.org/abs/1904.02689) & [Yolact Edge](https://arxiv.org/abs/2012.12259)   
* 影像實例分割技術 ─ YOLO 系列  
  *  中研院 (Academia Sinica) [YOLOv7](https://github.com/WongKinYiu/yolov7)  
  *  Ultralytics [YOLO v8 / v11 / 26] (https://docs.ultralytics.com/zh/tasks/segment/)  
* [Intel OpenVINO YOLO 實例分割範例](https://openvinotoolkit.github.io/openvino_notebooks/?search=YOLO)  
* 範例7-1：OpenVINO YOLO26 實例分割  
  * 說明文檔：https://github.com/openvinotoolkit/openvino_notebooks/tree/latest/notebooks/yolov26-optimization  
  * 範例程式：  https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/yolov26-optimization/yolov26-instance-segmentation.ipynb  
* Yolo26 不同模型實例分割時間比較  
* Yolo26 不同模型實例分割效果比較  
* AI 影像分割技術 ─ 基於Transformer  
  * [Meta - Segment Anything Model, SAM](https://aidemos.meta.com/segment-anything/)  
* Meta SAM 影像分割主要應用  
* [Intel OpenVINO SAM 相關範例](https://openvinotoolkit.github.io/openvino_notebooks/?search=SAM)  
* 範例7-2：OpenVINO Fast SAM 實例分割
  * 說明文檔：https://github.com/openvinotoolkit/openvino_notebooks/tree/latest/notebooks/fast-segment-anything  
  * 範例程式：  https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/fast-segment-anything/fast-segment-anything.ipynb  
  * Gradio 人機介面  
  * Fast SAM 實例分割結果  
* 如何使用 Gradio 快速搭建人工智慧應用圖形化人機介面  
  * 說明文檔：https://omnixri.blogspot.com/2024/12/vmaker-edge-ai-24-gradio.html  
  * 範例程式：https://colab.research.google.com/github/OmniXRI/Hello_World_Gradio/blob/main/Hello_World_Gradio.ipynb  
* 範例7-3：Ultralytics SAM  
  * 說明文檔：https://docs.ultralytics.com/zh/models/sam/  
  * 範例程式：https://colab.research.google.com/github/ultralytics/notebooks/blob/main/notebooks/inference-with-meta-sam-and-sam2-using-ultralytics-python-package.ipynb  
* [SAM 系列 vs. YOLO-seg 性能比較](https://docs.ultralytics.com/zh/models/mobile-sam/#mobilesam-comparison-vs-yolo)  

## 7.2.  姿態估測  

* 姿態估測(Pose Estimation)簡介  
* 姿態估測常見用途  
* 姿態估測（人體關鍵點）資料集  
* 常見的2D關鍵點開放資料集  
* [Microsoft COCO 關鍵點資料集](https://cocodataset.org/#keypoints-2020)  
  * [Keypoint Evaluation](https://cocodataset.org/#keypoints-eval)  
* [CMU OpenPose 基本介紹](https://github.com/CMU-Perceptual-Computing-Lab/openpose)  
* OpenPose 關鍵點定義   
* 姿態關鍵點轉換  
* OpenPose 結果展示  
* Intel OpenVINO 姿態估測範例  
  * [YOLO系列](https://openvinotoolkit.github.io/openvino_notebooks/?search=YOLO)  
  * [其它POSE](https://openvinotoolkit.github.io/openvino_notebooks/?search=pose)  
* 範例7-4：OpenVINO YOLO26 姿態估測
  * 說明文檔：https://github.com/openvinotoolkit/openvino_notebooks/tree/latest/notebooks/yolov26-optimization  
  * 範例程式：https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/yolov26-optimization/yolov26-keypoint-detection.ipynb  

## 7.3.  Google MediaPipe  

* Google AI Edge – MediaPipe簡介  
  * 開發文件：https://developers.google.com/mediapipe
  *  GITHUB：https://github.com/google-ai-edge/mediapipe  
* Google MediaPipe 可用解決方案  
* Google MediaPipe [解決方案展示](https://mediapipe-studio.webapps.google.com/home)  
* Google MediaPipe Tasks [WEB測試頁](https://google-ai-edge.github.io/mediapipe-samples-web/)
* 物件偵測 (Object Detecion)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/object_detector?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/object_detection/python/object_detector.ipynb  
* 影像分類 (Image Classification)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/object_detector?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/image_classification/python/image_classifier.ipynb  
* 影像分割 (Image Segmentation)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/image_segmenter?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/image_segmentation/python/image_segmentation.ipynb  
* 互動式分割 (Interactive_segmentation)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/interactive_segmenter?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/interactive_segmentation/python/interactive_segmenter.ipynb  
* 手勢辨識 (Gesture Recognition)   
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/gesture_recognizer?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/gesture_recognizer/python/gesture_recognizer.ipynb  
* 手部特徵點偵測 (Hand landmark detection)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/hand_landmarker/python/hand_landmarker.ipynb  
* 人臉偵測 (Face Detection)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/face_detector?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/face_detector/python/face_detector.ipynb  
* 臉部特徵點偵測 (Face Landmark Detection)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/face_landmarker?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/face_landmarker/python/%5BMediaPipe_Python_Tasks%5D_Face_Landmarker.ipynb  
* 姿態特徵點偵測 (Pose Landmark Detection)  
  * 說明文檔：https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker?hl=zh-tw  
  * 範例程式：https://colab.research.google.com/github/googlesamples/mediapipe/blob/main/examples/pose_landmarker/python/%5BMediaPipe_Python_Tasks%5D_Pose_Landmarker.ipynb  
* 整體特徵點偵測 (Holistic Landmark Detection)  
* 綜合範例:浮空手勢簡報播放
  * 說明文檔： https://omnixri.blogspot.com/2023/05/vmaker-edge-ai-05google-mediapipe.html
  * 範例程式：https://github.com/OmniXRI/PPT_Gesture_Demo

## 參考文獻  

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* Intel OpenVINO Notebooks Github  
https://github.com/openvinotoolkit/openvino_notebooks  
* Ultralytics YOLO 說明文檔  
https://docs.ultralytics.com/zh/  
* CMU OpenPose Github  
https://github.com/CMU-Perceptual-Computing-Lab/openpose  
* Google MediaPipe  
https://ai.google.dev/edge/mediapipe/solutions/guide?hl=zh-tw  



