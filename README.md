# Colab-and-Jupyter
(深耕計畫) 短期實務集訓課程 :  資工系

# (一) Google Colab 簡介: 
### 1. Google Colaboratory （簡稱 Google Colab）是一個基於 Jupyter Notebook 的免費服務 <br>
###（須註冊一個 Google 帳號、其餘部份此刻仍是免費）
### 2. 前 Google Colab 支援 Python 2 及 Python 3 ，也預先安裝了一些常用的機器學習 Python 函式庫 
### 3. 支援 Python 語言及人工智慧平台如 Tensorflow、Keras、Yolo等
### 4. 提供有一個程式最多12小時的GPU服務
### 5. 所建立的 notebook 都是儲存在帳號的  Google Drive 中


# (二) Colab 基本操作 : ColabTest.ipnb
# (三) 使用 keras 建構卷積內神經網路[CNN] 處理Minst, Cifar10 資料集
#### Colab_Keras_Mnist_CNN.ipynb
#### Colab_Keras_Cifar_Deeper_Conv3.ipynb

![images](https://github.com/GwoChuanLee/images/blob/main/%E5%9C%96%E7%89%871.png?raw=true =100x100)

# Golab 上傳檔案
from google.colab import files <br>
uploaded = files.upload()

# 下載檔案
from google.colab import files <br>
files.download('xxxx.xx')

# (四) Colab 中使用 Yolov3/Darkent :
#### Yolo3 using Darknet on Colab.ipynb
