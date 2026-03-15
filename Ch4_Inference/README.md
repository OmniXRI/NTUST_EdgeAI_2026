# 邊緣人工智慧實務（EE5354701）─ Ch4. 開源模型推論工具

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch4_Inference/2026_NTUST_EdgeAI_Ch04_Inference.jpg" width="640">

## 4.1. Arm CMSIS

* [常見 Arm 晶片CPU等級及指令集](https://omnixri.blogspot.com/2024/01/vmaker-edge-ai-13-npuai.html)
* arm Cortex-M 架構差異
* [Cortex-M 指令加速操作比較](https://hackmd.io/@OmniXRI-Jack/arm_developer_cortexm55_ethosu55_guide)
* Edge AI & TinyML 通用 / 專用開發工具
* 何謂 arm CMSIS
* [CMSIS-5](https://arm-software.github.io/CMSIS_5/latest/General/html/index.html)
* CMSIS-5 架構圖
* [CMSIS-6](https://arm-software.github.io/CMSIS_6/latest/General/index.html)
* CMSIS-6 主要元件功能
* CMSIS-6 架構圖
* CMSIS 5 / 6 Github 比較
  * [CMSIS 5 Github](https://github.com/ARM-software/CMSIS_5/tree/develop/CMSIS)
  * [CMSIS 6 Github](https://github.com/ARM-software/CMSIS_6/tree/main/CMSIS)
* CMSIS 5 / 6 主要差異
* [CMSIS-6 Core](https://arm-software.github.io/CMSIS_6/latest/Core/index.html)
* CMSIS-6 Core 相關檔案
* [CMSIS-6 Driver](https://arm-software.github.io/CMSIS_6/latest/Driver/index.html)
* CMSIS-6 Driver 架構圖
* [CMSIS-6 DSP](https://arm-software.github.io/CMSIS-DSP/latest/) 
* CMSIS-6 DSP – 通用格式
* CMSIS-6 DSP – 數學函數
* CMSIS-6 DSP – 濾波器函數
* CMSIS-6 DSP – 矩陣函式
* CMSIS-6 DSP – 變換函式
* [CMSIS 5 / 6 DSP 比較](https://omnixri.blogspot.com/2024/02/tinyml-arm-cmsis-6-dsp-nn.html)
* [CMSIS-6 NN](https://arm-software.github.io/CMSIS-NN/latest/)
* CMSIS-6 NN 架構圖
* CMSIS-6 NN – 卷積函式 
* CMSIS-6 NN –  激勵函式
* CMSIS-6 NN –  池化函式 
* CMSIS-6 NN –  全連結層函式 
* CMSIS-6 NN –  Softmax函式 
* [CMSIS 5 / 6 NN 比較](https://omnixri.blogspot.com/2024/02/tinyml-arm-cmsis-6-dsp-nn.html)

## 4.2. Edge Impulse

* [Edge Impulse 簡介](https://edgeimpulse.com/)
* Edge Impulse 應用實例
* Edge Impulse 技術支援
* Arduino [UNO Q](https://www.arduino.cc/product-uno-q) / [Ventuno Q](https://www.arduino.cc/product-ventuno-q/)
  * [Qualcomm Dragonwing QRB2210](https://www.qualcomm.com/internet-of-things/products/q2-series/qrb2210)
  * [Qualcomm Dragonwing IQ8275](https://www.qualcomm.com/internet-of-things/products/iq8-series/iq-8275)
  * [Arudino App Lab](https://docs.arduino.cc/software/app-lab/)
* [Edge Impulse 說明文件 2025 更新版](https://docs.edgeimpulse.com/)
* [Edge Impulse 支援硬體及推論工具](https://docs.edgeimpulse.com/docs/tools/edge-impulse-python-sdk)
* [Edge Impulse Studio ─ 專案功能表](https://docs.edgeimpulse.com/studio)
* [Edge Impulse 主要功能 ─ 資料集建置](https://docs.edgeimpulse.com/studio/projects/data-acquisition)
* [Edge Impulse 資料集建置方式](https://docs.edgeimpulse.com/studio/projects/data-acquisition)
* [Edge Impulse 主要功能 ─ 模型設定](https://docs.edgeimpulse.com/studio/projects/impulse-design)
  * [Processing Blocks](https://docs.edgeimpulse.com/studio/projects/processing-blocks)
  * [Learning Blocks](https://docs.edgeimpulse.com/studio/projects/learning-blocks)
* [Edge Impulse 主要功能 ─ 模型訓練](https://docs.edgeimpulse.com/studio/projects/learning-blocks/training-graphs)
* [Edge Impulse主要功能─EON 模型優化](https://docs.edgeimpulse.com/studio/projects/eon-tuner)
* [Edge Impulse 主要功能 ─ 部署](https://docs.edgeimpulse.com/studio/projects/deployment)
* [Edge Impulse - 註冊/登入帳號](https://studio.edgeimpulse.com/login)
* [啟動公用專案範例 ─ 聲音辨識](https://docs.edgeimpulse.com/tutorials/end-to-end/sound-recognition) 
* [公用專案 ─ 水流聲辨識](https://studio.edgeimpulse.com/public/14301/latest) 
* [專案工作流程](https://docs.edgeimpulse.com/tutorials/end-to-end/sound-recognition) 

## 4.3. Intel OpenVINO

* [Intel OpenVINO 官網](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/overview.html)
* [Intel OpenVINO 說明文件](https://docs.openvino.ai/2025/index.html)
* Intel OpenVINO 演進歷史
* [Intel OpenVINO Github](https://github.com/openvinotoolkit/openvino/)
* [Intel OpenVINO 相關工具程式](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/overview.html)
* [Intel OpenVINO Model Zoo](https://docs.openvino.ai/2023.3/model_zoo.html)
  * [Intel OpenVINO Model Zoo Github](https://github.com/openvinotoolkit/open_model_zoo)
* Hugging Face - Optimun Intel
  * [Hugging Face - Intel](https://huggingface.co/Intel)
  * [Optimnu Intel - OpenVINO Models](https://huggingface.co/docs/optimum-intel/openvino/models)
* [Intel OpenVINO Notebooks](https://github.com/openvinotoolkit/openvino_notebooks)
* [Intel OpenVINO Notebooks Pages](https://openvinotoolkit.github.io/openvino_notebooks/)
* Intel OpenVINO 鑑別式 AI 應用
* Intel OpenVINO 生成式 AI 應用
* [Intel OpenVINO Model Converter](https://docs.openvino.ai/2026/openvino-workflow/model-preparation.html)
* Intel OpenVINO 直接支援AI框架
* [Intel OpenVINO Benchmark_App](https://docs.openvino.ai/2026/get-started/learn-openvino/openvino-samples/benchmark-tool.html)
* 推論同步及異步處理
* [Intel OpenVINO - NNCF](https://github.com/openvinotoolkit/nncf)
* [Intel OpenVINO Model Server](https://docs.openvino.ai/2026/model-server/ovms_what_is_openvino_model_server.html)
* Intel OpenVINO Runtime
  * [Linux](https://docs.openvino.ai/2026/get-started/install-openvino/install-openvino-linux.html)
  * [Windows](https://docs.openvino.ai/2026/get-started/install-openvino/install-openvino-windows.html)
  * [macOS](https://docs.openvino.ai/2026/get-started/install-openvino/install-openvino-macos.html)
* [Intel OpenVINO – Gen AI API](https://docs.openvino.ai/2026/get-started/install-openvino/install-openvino-genai.html)
* [Intel 快速建構部署模型工具 ─ Geti](https://github.com/open-edge-platform/geti)
* [Intel AI Playground 生成式 AI 工具](https://game.intel.com/tw/stories/introducing-ai-playground/)
* Intel AI Playground 展示
  * [許哲豪，有了 Intel AI Playground 不寫程式也能輕鬆玩生成式AI](https://omnixri.blogspot.com/2025/09/intel-ai-playground-ai.html)
* 路Intel OpenVINO Notebooks 安裝 (Windows)](https://github.com/openvinotoolkit/openvino_notebooks/wiki/Windows)
* Notebooks範例 - hello-world 
* [Intel OpenVINO Notebooks Hello範例](https://openvinotoolkit.github.io/openvino_notebooks/?search=hello)
* [Google Colab 雲端執行 OpenVINO](https://colab.research.google.com/github/openvinotoolkit/openvino_notebooks/blob/latest/notebooks/hello-world/hello-world.ipynb)

## Intel OpenVINO 學習資源

* Intel OpenVINO Document  
https://docs.openvino.ai/
* Intel OpenVINO Toolkit (Youtube)  
https://www.youtube.com/watch?v=kY9nZbX1DWM&list=PLg-UKERBljNxdIQir1wrirZJ50yTp4eHv
* Intel OpenVINO Toolkit (Meduim)  
https://medium.com/@openvino  
* OmniXRI，許哲豪，OpenVINO系列發文  
https://hackmd.io/@OmniXRI-Jack/series_articles#OpenVINO%E7%B3%BB%E5%88%97
* MakerPRO， OpenVINO系列發文  
https://makerpro.cc/category/suppliers/openvino-column/

## 參考文獻

* 許哲豪，臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )  
https://omnixri.blogspot.com/p/ntust-edge-ai.html
* Arm,通用微控制器軟體介面標準 (CMSIS)  
https://www.arm.com/zh-tw/technologies/cmsis
* 許哲豪，OmniXRI TinyML 小學堂 (2025) 【第 5 講】通用微控制器軟體介面標準(CMSIS)  
https://youtu.be/JFR5o4dFxrk
* 許哲豪，TinyML 核心函式庫 Arm CMSIS 6 DSP & NN 更新比較  
https://omnixri.blogspot.com/2024/02/tinyml-arm-cmsis-6-dsp-nn.html
* Edge Impulse Documentation  
https://docs.edgeimpulse.com/
* Intel OpenVINO Document  
https://docs.openvino.ai/
* Intel OpenVINO Notebooks (Github)  
https://github.com/openvinotoolkit/openvino_notebooks
