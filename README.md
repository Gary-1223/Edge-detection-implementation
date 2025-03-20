# 使用 Sobel 邊緣檢測器進行影像邊緣偵測

本專案使用 Python 和 OpenCV 實現了 Sobel 邊緣檢測器，用於檢測影像中的邊緣。透過調整閾值，可以控制檢測到的邊緣數量。

## 相依套件

* `opencv-python`
* `numpy`
* `matplotlib`
* `google-colab` (此程式在 Google Colab 上執行)

## 安裝說明

1.  安裝相依套件：

    pip install opencv-python numpy matplotlib

2.  將 `Lenna_(test_image).png` 影像檔案放置在與程式碼相同的目錄下。

3.  執行 `main.py` 檔案：

    python main.py

## 使用說明

1.  程式碼首先將彩色影像轉換為灰階影像。
2.  然後，它使用 Sobel 運算子計算影像的梯度。
3.  最後，它根據不同的閾值顯示邊緣檢測結果。

## 程式碼說明

* `convolve2d(image, kernel)`: 此函式用於執行 2D 卷積。
* `edge_detection(threshold_value)`: 此函式根據閾值將梯度幅度轉換為二值影像。
* 主程式部分載入影像，計算梯度，並顯示不同閾值的邊緣檢測結果。

## 範例圖片

以下是使用不同閾值進行邊緣檢測的範例圖片：

(在此插入範例圖片，例如使用 `![Original Grayscale Image](path/to/original_grayscale_image.png)` 語法)
(在此是使用lenna作為範例)
