# 邊緣人工智慧實務（EE5354701）─ Ch10  TinyML 案例實作 ─ 智慧影像

<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch10_TinyML_Image/20260518_NTUST_EdgeAI_Ch10_TinyML_Image.jpg" width="640">

## 10.1. 微型視覺系統開發流程  

* TinyML視覺系統開發流程  
  * Grove Vision AI Kit V2 + SenseCraft AI + SSCMA  
  * Grove Vision AI Kit V2 + Edge Impulse + Vela Compiler  
  * Grove Vision AI Kit V2 + Himax SDK   
  * SenseCAP Watcher + SenseCraft APP  
* 常見硬體  
  * [瑞昱(Realtek) AMB82 系列](https://www.amebaiot.com.cn/zh/amebapro2/#rtk_amb82_mini)  
  * 新唐(Nuvoton) M55M1 系列
    * [NuMaker-M55M1D](https://www.nuvoton.com/board/numaker-x-m55m1d/)  
    * [NuMaker-GestureAI-M55M1](https://www.nuvoton.com/board/numaker-gestureai-m55m1/)  
  * OpenMV [AE3](https://openmv.io/products/openmv-ae3) / [N6](https://openmv.io/collections/cameras/products/openmv-n6)  
  * [Seeed Xiao ESP32-S3 Sense](https://wiki.seeedstudio.com/cn/xiao_esp32s3_getting_started/)  
  * [Seeed Grove Vision AI V2 Kit](https://wiki.seeedstudio.com/grove_vision_ai_v2/)  
  * [Seeed SenseCAP Watcher](https://wiki.seeedstudio.com/watcher/)  
* TinyML 開發流程選項  
* [Grove Vision AI Module V2](https://wiki.seeedstudio.com/grove_vision_ai_v2/)  
  * Grove Vision AI Module V2 技術文件 
  * Grove Vision AI Module V2 接腳圖  
  * Grove Vision AI Module V2 元件圖  
  * 開發板組裝 ─ 連接攝影機   
  * 開發板組裝 ─ 連接攝影機（動畫）  
  * 安裝驅動程式 (USB – COM)   
  * 開發板組裝 ─ 連接USB  
* [Seeed SenseCraft AI](https://sensecraft.seeed.cc/ai/) 
  * Seeed SenseCraft AI ─ 功能概述  
  * Seeed SenseCraft AI ─ 註冊與登錄  
  * Seeed SenseCraft AI ─ 預訓練模型  
  * Seeed SenseCraft AI ─ 部署模型  
  * Seeed SenseCraft AI ─ 執行推論  
  * Seeed SenseCraft AI ─ 數據輸出  
  * 燒錄故障排除 ─ ESP32C3  
* [Seeed SenseCraft Web Toolkit](https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process)  

## 10.2. 影像物件偵測  

* 資料集建置  
  * 分類識別 ─ 數據採集  
  * 分類識別 ─ 資料多樣態  
  * 分類識別 ─ 模型訓練部署  
* 建立自定義模型  
  * 第一步基礎信息  
  * 第二步模型  

## 10.3. 模型部署與週邊整合  

* 部署並執行自定義模型  
* [進階補充 ─ 更多自定義模型訓練方式](https://wiki.seeedstudio.com/ModelAssistant_Introduce_Quick_Start/#model-training)  
* 透過 Virtual-COM 以文字方式送出結果  
* [UART AT Protocol JSON 輸出文字格式](https://github.com/Seeed-Studio/SSCMA-Micro/blob/1.0.x/docs/protocol/at_protocol.md)  
* Arduino UART 接收結果範例  
* Xiao 開發板連接 Grove Vision AI V2 (動畫)  
* [Seeed SSCMA](https://sensecraftma.seeed.cc/introduction/quick_start)  
  * [Seeed SSCMA 技術說明文件](https://sensecraftma.seeed.cc/introduction/quick_start)  
  * [下載 Seeed Arduino SSCMA](https://github.com/Seeed-Studio/Seeed_Arduino_SSCMA/)  
  * [Arudiuno 安裝 Seeed SSCMA](https://wiki.seeedstudio.com/grove_vision_ai_v2_software_support/)  
  * [Arudiuno 安裝 ArduinoJSON](https://wiki.seeedstudio.com/grove_vision_ai_v2_software_support/)  
  * Arduino 新增 Xiao ESP32C3 開發板
    * https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
  * Xiao ESP32C3 讀取結果範例程式
  * Xiao ESP32C3 控制 GPIO
* [Grove Vision AI V2 + Edge Impulse](https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch11_Object_Detection)  
  * [採用 Edge Impulse 訓練轉換](https://www.hackster.io/mjrobot/computer-vision-at-the-edge-with-grove-vision-ai-module-v2-0003c7)  
  * 下載 Edge Impulse訓練好的 TFLite 模型  
  * 使用 Google Colab 進行 vela 轉換  
* [Grove Vision AI V2 + Himax SDK](https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch12_Pose_Estimation)  
  * [Github - Himax - Grove Vision AI Module V2](https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2)  
  * [Github ─ Himax ─ Yolov8n on WE2](https://github.com/HimaxWiseEyePlus/YOLOv8_on_WE2)  
* [Seeed SenseCAP Watcher + APP](https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch13_Cloud_Edge)  
  * [SenseCAP Watcher – 硬體方塊圖](https://wiki.seeedstudio.com/watcher_hardware_overview/)  
  * [SenseCAP Watcher – 系統架構](https://wiki.seeedstudio.com/watcher/)  
  * [SenseCAP Watcher ─ 軟體服務框架](https://wiki.seeedstudio.com/cn/watcher_software_service_framework/)  
  * [SenseCAP Watcher – 任務類型](https://wiki.seeedstudio.com/getting_started_with_watcher/)  
  * [SenseCAP Watcher ─ 更多使用案例](https://www.seeedstudio.com/SenseCAP-Watcher-W1-A-p-5979.html)  

## 參考文獻  

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701 )  https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* 許哲豪，OmniXRI TinyML 小學堂 (2025) 第10 ~ 13講  
  * 第10講 https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch10_Image_Classification  
  * 第11講 https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch11_Object_Detection  
  * 第12講 https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch12_Pose_Estimation  
  * 第13講 https://github.com/OmniXRI/TinyML_Course_2025/tree/main/Ch13_Cloud_Edge  
* Seeed SenseCraft AI  
https://sensecraft.seeed.cc/ai/home/  
* Seeed Studio Grove Vision AI Module V2  
https://wiki.seeedstudio.com/grove_vision_ai_v2/  
* Seeed SenseCraft Web Toolkit  
https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process  
* Github – HimaxWiseEyePlus /  Seeed_Grove_Vision_AI_Module_V2  
https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2  
* Github – HimaxWiseEyePlus / YOLOv8_on_WE2  
https://github.com/HimaxWiseEyePlus/YOLOv8_on_WE2  
