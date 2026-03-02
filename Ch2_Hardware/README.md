# 邊緣人工智慧實務（EE5354701）─ Ch2. 邊緣運算硬體架構


<img src="https://raw.githubusercontent.com/OmniXRI/NTUST_EdgeAI_2026/refs/heads/main/Ch2_Hardware/2026_NTUST_EdgeAI_Ch02_Hardware.jpg" width="640">

## 2.1. 基本運算原理

* 卷積神經網路(CNN)
* 卷積神經網路 ─ 卷積
* 卷積神經網路 ─ 池化、平坦化
* 卷積神經網路 ─ 全連結
* 卷積神經網路 ─ 激活函數(1/2)
* 卷積神經網路 ─ 激活函數(2/2)
* 卷積神經網路 ─ 輸出函數
* 卷積神經網路 ─ 權重與計算量
* 數字表示系統 ─ 進制轉換
* 數字表示系統 ─ 整數
* 數字表示系統 ─ 浮點數
* 數字表示系統 ─ AI 常用浮點數
* 資料維度
* 矩陣乘法
* 平行 / 並行運算

## 2.2. 加速運算晶片

* 加速運算晶片 
* CPU ─ 指令集架構(ISA)
* CPU─指令流與資料流
* CPU ─ x86 SIMD
* CPU – Arm Cortex-M 加速指令集
* CPU ─ ARM Cortex-A 加速指令集
* CPU ─ RISC-V 向量指令集
* GPU ─ 主要供應商
* GPU ─ 結構與工作流程
* GPU ─ Nvidia Cuda Core
* GPU ─ Nvidia Tensor Core
* GPU ─ Cuda / Tensor Core (1/2)
* GPU ─ Cuda / Tensor Core (2/2)
* DSP ─ 常見供應商
* DSP ─ 主要功能
* NPU ─ 主要供應商
* NPU ─ MCU級常見供應商
* FPGA
* 其它類型 ─ 記憶體內計算 (CiM)
* 其它類型 ─ 類腦晶片
* 其它類型 ─類腦晶片 IBM TrueNorth
* 其它類型─光子晶片
* 硬體加速方式與限制

## 2.3. 嵌入式級硬體

* 各式開發板外型
* 迷你電腦 ─ INTEL 系列
* 單板微電腦 ─ NVIDIA
* 單板微電腦 ─ GOOGLE
* 單板微電腦 ─ Arm Based
* 單板微電腦 ─ 台灣 AI 開發板 
* 常見單晶片開發板
* MCU 等級主要核心晶片分類
* 智慧感測型開發板(MCU SIMD 指令集)
* MCU / MCU+NPU 開發板
* 視覺型開發板(MCU MVE+NPU)
* 台灣 MCU + NPU 開發板 
* MPU/MCU + DSP 開發板
* MPU + GPU 開發板
* FPGA 開發板

## 2.4. AI PC 級硬體

* 常見 AI PC 主要晶片比較
* Apple AI PC 晶片
* Intel Core Ultra 演進
* Intel NPU 演進
* 台灣生成式 AI 型硬體
* 運算效能 ─ 主要指標
* 運算效能 ─ ML COMMONS

## 參考文獻

* 臺灣科技大學資訊工程系 人工智慧與邊緣運算實務 ( CS5149701）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  
* 許哲豪，MCU攜手NPU讓tinyML邁向新里程碑  
https://omnixri.blogspot.com/2022/10/mcunputinyml.html  
* 許哲豪，有了TinyML加持MCU也能開始玩電腦視覺了  
https://omnixri.blogspot.com/2022/12/tinymlmcu.html  
* 許哲豪，誰說單晶片沒有神經網路加速器NPU就不能玩微型AI應用？  
https://omnixri.blogspot.com/2024/01/vmaker-edge-ai-13-npuai.html  
* 許哲豪， AI晶片發展歷史及最新趨勢  
https://omnixri.blogspot.com/2023/03/vmaker-edge-ai-03-ai.html  
* 許哲豪，要玩AI前，先來認識數字系統  
https://omnixri.blogspot.com/2023/02/vmaker-edge-ai-02-ai.html  
* 許哲豪， Nvidia GTC 2024 提出的 FP8/FP4 如何加速AI訓練及推論  
https://omnixri.blogspot.com/2024/03/nvidia-gtc-2024-fp8fp4-ai.html  

