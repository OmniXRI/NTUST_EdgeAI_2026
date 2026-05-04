# 邊緣人工智慧實務（EE5354701）─ Ch8  TinyML 案例實作 ─ 聲音辨識

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch8_Voice_Recognition/20260427_NTUST_EdgeAI_Ch8_Voice_Recognition.jpg" width="640">

## 8.1. 聲音感測器原理  

* 感測器類比/數位信號互換  
* 常見錄音裝置  
* 聲音訊號─取樣、量化  
* 常見聲音訊號波形（時間域）  
* 傳統時間序列相似度分析 ─ DTW  
* 特徵提取 ─ 時間域、頻率域轉換  
* 特徵提取 ─ 線性頻譜、梅爾倒頻譜表示法  
* 深度學習模型聲音分類  
* [Arduino Nano 33 BLE Sense Rev.2 規格](https://docs.arduino.cc/hardware/nano-33-ble-sense-rev2/)  
* [Seeed Xiao nRF52840 (Sense) 規格](https://wiki.seeedstudio.com/XIAO_BLE/)  
* Seeed Xiao nRF52840 (Sense) 接腳圖  
* Seeed Xiao nRF52840 (Sense) 元件圖  
* [Seeed Xiao 擴充底板](https://wiki.seeedstudio.com/Seeeduino-XIAO-Expansion-Board/)  
* [Seeed Xiao nRF52840 (Sense) 技術文件](https://wiki.seeedstudio.com/XIAO_BLE/)  
* [Seeed Xiao nRF52840 Sense PDM](https://wiki.seeedstudio.com/XIAO-BLE-Sense-PDM-Usage/)  
* 自定義語音命令錄音技巧  
* [聲音分割開源工具 Audacity](https://www.audacityteam.org/)  
* [Edge Impulse 連續信號自動分割工具](https://docs.edgeimpulse.com/studio/projects/data-acquisition)  

## 8.2. 喚醒詞偵測   

* 喚醒詞偵測  
* 案例分享 ─ 聲控電風扇  
  * [正確示範（美女版）](https://www.youtube.com/shorts/X8yJjRj7Uus)  
  * [錯誤示範（阿媽版）](https://www.youtube.com/shorts/OdPn091H-0E)  
  * [正確示範（台灣國語）](https://youtu.be/vpZgt0VQf8Y)  
* Google Speech Commands 公開資料集  
  * [Dataset](https://www.tensorflow.org/datasets/catalog/speech_commands)  
  * [Paper](https://arxiv.org/abs/1804.03209)  
* 關鍵詞偵測(KWS) 特徵提取  
* Xiao nRF52840 Sense 模組 ─ 參考電路  
* TinyML 開發流程選項  
* Arduino 新增開發板設定  
  * http://files.seeedstudio.com/arduino/package_seeduino_boards_index.json  
* 安裝Seeed nRF52840函式庫  
  * Seeed nRF52 Boards (BLE)  
  * Seeed nRF52 mbed-enagled Boards (PDM, IMU, ML)  
* 指定工作開發板及埠號  
* [Xiao nRF52840 Sense 語音辨識](https://wiki.seeedstudio.com/XIAO-BLE-Sense-TFLite-Mic/)  
* Aruino 預安裝模組  
  * https://github.com/lakshanthad/tflite-micro-arduino-examples  
* [啟動 Google Colab 模型訓練範例](https://colab.research.google.com/github/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/examples/micro_speech/train/train_micro_speech_model.ipynb)  
* 修正 Colab 範例訓練參數  
* Colab 開始執行模型訓練  
* Colab 完成模型訓練  
* 更新 Arduino 函式庫  
*  NO Code 測試結果  
*  Arduino 2.0 快速(增量)編譯  

## 8.3. 環境音辨識  

* [ESC-50 環境音公開資料集](https://github.com/karolpiczak/ESC-50)  
* [Google AudioSet 聲音公開資料集](https://research.google.com/audioset/)  
  * [YAMNet](https://www.tensorflow.org/hub/tutorials/yamnet?hl=zh-cn)  
* 案例分享 ─ [2024 總統盃黑客松卓越團隊](https://youtu.be/0E5gW9PcSgs)  
* 案例分享 ─ Smart Sound Box  
* 案例分享─[水流聲偵測](https://studio.edgeimpulse.com/public/119084/latest)  
* 案例分享─[更多聲音相關應用](https://hackmd.io/@OmniXRI-Jack/tinyML_30_projects)  

## 參考文獻  

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )    https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* 許哲豪，OmniXRI TinyML 小學堂 (2025) 【第 8 講】聲音辨識應用─環境音辨識  
https://www.youtube.com/watch?v=xXD8g-BXriU  
* 許哲豪，如何讓 Arduino 2.0 快速編譯（增量編譯）  
https://omnixri.blogspot.com/2024/10/arduino-20.html  
* Seeed Xiao nRF52840 (Sense) 技術文件  
https://wiki.seeedstudio.com/XIAO_BLE/  
* 許哲豪， TinyML應用大全（30組案例分享）  
https://hackmd.io/@OmniXRI-Jack/tinyML_30_projects  


