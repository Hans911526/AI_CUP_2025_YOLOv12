# AI CUP 2025 Aortic Valve Object Detection (YOLOv12)
-[環境安裝與配置](#環境安裝與配置)
-[資料處理與分割策略](#資料處理與分割策略)
-[模型訓練流程](#模型訓練流程)
-[參數設定](#參數設定)
-[預測與重現結果](#預測與重現結果)

環境安裝與配置
於Google Colab或在具備 NVIDIA GPU的環境下執行。

核心
- Python 3.12+
- PyTorch 2.x
- Ultralytics 8.3.228 (支援 YOLOv12)
- CUDA 12.x (建議)

安裝指令
若在本地端執行，請先安裝必要套件：
```bash
pip install ultralytics gdown
