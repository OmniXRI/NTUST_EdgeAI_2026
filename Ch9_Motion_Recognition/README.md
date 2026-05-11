# 邊緣人工智慧實務（EE5354701）─ Ch9  TinyML 案例實作 ─ 動作辨識

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch9_Motion_Recognition/20260510_NTUST_EdgeAI_Ch9_Motion_Recognition.jpg" width="640">

## 9.1. 運動感測器原理  

* 何謂運動感測器 (Motion Sensor)  
* 加速度計 (G Sensor)  
* 陀螺儀 (Gyro Sensor)  
* 地磁感測器 (Geomagnetic Sensor)  
* 運動感測常見應用  
* [Arduino Nano 33 BLE Sense Rev.2](https://docs.arduino.cc/hardware/nano-33-ble-sense-rev2/)  
* [Seeed Xiao nRF52840 Sense](https://wiki.seeedstudio.com/cn/XIAO_BLE/)  
* 穿戴式智慧人工智慧裝置 ─ 參考電路  
* 穿戴式智慧人工智慧裝置 ─ 參考外形
  * [TinyML新玩法─揮揮手馬上就能變身簡報播放遙控器](https://youtu.be/HxnjNGnKn2Y?list=PLo_tFZGoEZum8b35jClphx5kL8AP1bGut)
* [Xiao nRF52840 Sense IMU使用方法](https://wiki.seeedstudio.com/cn/XIAO-BLE-Sense-IMU-Usage/)  
* Arduino 新增開發板設定  
  * http://files.seeedstudio.com/arduino/package_seeduino_boards_index.json  
* 安裝Seeed nRF52840函式庫  
  * Seeed nRF52 Boards (BLE)  
  * Seeed nRF52 mbed-enagled Boards (PDM, IMU, ML)  
* 指定工作開發板及埠號  
* 安裝運動感測器（IMU）函式庫  
  * [LSM6DS3 Lib](https://github.com/Seeed-Studio/Seeed_Arduino_LSM6DS3)  
* 運動感測器（IMU）取值範例  
* IMU 連續取值輸出至 Edge Impulse  
* 監看運動感測器（IMU）輸出值  
* 案例分享 ─ [Rabboni](https://rabboni.com.tw/)  

## 9.2. 運動手勢辨識  

* 設計自定義操作手勢  
* TinyML 開發流程選項  
* Edge Impulse 資料集建置方式  
* [快速操作指令表](https://github.com/OmniXRI/Edge_AI_TinyML_Course_2024/blob/main/Ch13_Motion_Recognition/IMU_Quick_Guide.md)  
* 下載及安裝必要工具  
  1. [Python 3.x](https://www.python.org/downloads/)  
  2. [Node.js](https://nodejs.org/en/download/package-manager)  
  3. [Arduino CLI](https://arduino.github.io/arduino-cli/0.35/installation/)  
* [安裝 Edge Impulse windows 工作環境](https://docs.edgeimpulse.com/docs/tools/edge-impulse-cli/cli-installation)  
  * 安裝Edge Impulse CLI  
   npm install -g edge-impulse-cli --force  
* 建立 Edge Impulse 新專案  
* 啟動edge-impulse-data-forwarder   
* 檢查裝置是否已連線  
* 從外部裝置取得資料  
* 大量收集樣本並分割成獨立可訓練樣本  
* 原始資料與自動分割  
* 反複收集分割，建立完整資料集  
* 選擇模型及設定必要參數  
* 提取資料特徵  
* 提取特徵結果  
* 設定分類訓練相關參數  
* 開始進行模型訓練及結果顯示  
* 線上測試（從外部裝置取樣）  
* 選擇部署種類及設定參數  
* 導入 Arduino 函式庫並進行推論測試  
* 手勢辨識結果（Arduino部份）  
* [Arduino 2.0 快速(增量)編譯](https://omnixri.blogspot.com/2024/10/arduino-20.html)  
* [nRF52840 基於Edge Impulse 的動作辨識](https://wiki.seeedstudio.com/cn/XIAOEI/)  
* [Edge Impulse Expert 加速度計及活動測案例分享](https://docs.edgeimpulse.com/projects/expert-network/project-list#accelerometer-and-activity-projects)  
* [其它案例分享](https://hackmd.io/@OmniXRI-Jack/tinyML_30_projects)  

## 9.3. 異常振動偵測  

* [時間序列信號預測](https://vocus.cc/article/6927b46cfd897800014271ee)  
  * 傳統時間序列預測模型  
  * 深度學習時間序列預測模型  
* [常見時序信號異常偵測方式](https://docs.edgeimpulse.com/tutorials/end-to-end/motion-recognition)  
  * 特徵樣版分類  
  * 聚類離群偵測  
* Edge Impulse 專案 – Impulse Design  
* [練習案例 ─ 無刷直流馬達異常偵測](https://docs.edgeimpulse.com/projects/expert-network/brushless-dc-motor-anomaly-detection)  
* 複製並建立專案
  * [Public Project Link](https://studio.edgeimpulse.com/public/102584/latest)  
* 建立資料集  
* 建立及設定時間序列模型  
* 頻譜分析、特徵生成  
* 異常偵測模型訓練  
* 線上測試  
* 選擇部署方式  
* Arduino 端建立 Pi Pico 開發環境  
* [Edge Impulse Expert 維護預測案例分享](https://docs.edgeimpulse.com/projects/expert-network/project-list#predictive-maintenance-and-fault-classification-projects)  
 
## 參考文獻  

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )   
https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* OmniXRI's Edge AI & TinyML 小學堂 【第13講】案例實作─運動辨識  
https://github.com/OmniXRI/Edge_AI_TinyML_Course_2024/tree/main/Ch13_Motion_Recognition  
* Seeed Studio XIAO nRF52840 Sense – 硬件使用 - IMU 使用方法  
https://wiki.seeedstudio.com/cn/XIAO-BLE-Sense-IMU-Usage/  
* Seeed Studio XIAO nRF52840 Sense - 嵌入式機器學習 - 基於 Edge Impulse 的動作辨識  
https://wiki.seeedstudio.com/cn/XIAOEI/  
* 許哲豪，TinyML應用大全（30組案例分享）  
https://hackmd.io/@OmniXRI-Jack/tinyML_30_projects  
* Edge Impulse Document – Projects – Expert Network – Accelerometer and Activity Projects  
https://docs.edgeimpulse.com/projects/expert-network/project-list#accelerometer-and-activity-projects  
* Edge Impulse Document – Projects – Expert Network – Predictive Maintenance and Defect Detection Projects  
https://docs.edgeimpulse.com/projects/expert-network/project-list#predictive-maintenance-and-fault-classification-projects  
